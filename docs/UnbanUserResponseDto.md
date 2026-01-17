# UnbanUserResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | User unbanned successfully | 

## Example

```python
from cashful.models.unban_user_response_dto import UnbanUserResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of UnbanUserResponseDto from a JSON string
unban_user_response_dto_instance = UnbanUserResponseDto.from_json(json)
# print the JSON string representation of the object
print(UnbanUserResponseDto.to_json())

# convert the object into a dict
unban_user_response_dto_dict = unban_user_response_dto_instance.to_dict()
# create an instance of UnbanUserResponseDto from a dict
unban_user_response_dto_from_dict = UnbanUserResponseDto.from_dict(unban_user_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


