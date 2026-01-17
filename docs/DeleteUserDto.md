# DeleteUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**callback_url** | **str** | The callback URL to redirect to after user is deleted | [optional] 
**password** | **str** | The user&#39;s password. Required if session is not fresh | [optional] 
**token** | **str** | The deletion verification token | [optional] 

## Example

```python
from cashful.models.delete_user_dto import DeleteUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteUserDto from a JSON string
delete_user_dto_instance = DeleteUserDto.from_json(json)
# print the JSON string representation of the object
print(DeleteUserDto.to_json())

# convert the object into a dict
delete_user_dto_dict = delete_user_dto_instance.to_dict()
# create an instance of DeleteUserDto from a dict
delete_user_dto_from_dict = DeleteUserDto.from_dict(delete_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


