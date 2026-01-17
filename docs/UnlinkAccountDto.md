# UnlinkAccountDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The social provider to unlink | 
**account_id** | **str** | The provider account ID to unlink | 

## Example

```python
from cashful.models.unlink_account_dto import UnlinkAccountDto

# TODO update the JSON string below
json = "{}"
# create an instance of UnlinkAccountDto from a JSON string
unlink_account_dto_instance = UnlinkAccountDto.from_json(json)
# print the JSON string representation of the object
print(UnlinkAccountDto.to_json())

# convert the object into a dict
unlink_account_dto_dict = unlink_account_dto_instance.to_dict()
# create an instance of UnlinkAccountDto from a dict
unlink_account_dto_from_dict = UnlinkAccountDto.from_dict(unlink_account_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


