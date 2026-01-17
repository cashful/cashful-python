# AdminUpdateUserResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | [**SessionUserDto**](SessionUserDto.md) | User updated successfully | 

## Example

```python
from cashful.models.admin_update_user_response_dto import AdminUpdateUserResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminUpdateUserResponseDto from a JSON string
admin_update_user_response_dto_instance = AdminUpdateUserResponseDto.from_json(json)
# print the JSON string representation of the object
print(AdminUpdateUserResponseDto.to_json())

# convert the object into a dict
admin_update_user_response_dto_dict = admin_update_user_response_dto_instance.to_dict()
# create an instance of AdminUpdateUserResponseDto from a dict
admin_update_user_response_dto_from_dict = AdminUpdateUserResponseDto.from_dict(admin_update_user_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


