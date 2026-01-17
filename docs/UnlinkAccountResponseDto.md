# UnlinkAccountResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Social account unlinked successfully | 

## Example

```python
from cashful.models.unlink_account_response_dto import UnlinkAccountResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of UnlinkAccountResponseDto from a JSON string
unlink_account_response_dto_instance = UnlinkAccountResponseDto.from_json(json)
# print the JSON string representation of the object
print(UnlinkAccountResponseDto.to_json())

# convert the object into a dict
unlink_account_response_dto_dict = unlink_account_response_dto_instance.to_dict()
# create an instance of UnlinkAccountResponseDto from a dict
unlink_account_response_dto_from_dict = UnlinkAccountResponseDto.from_dict(unlink_account_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


