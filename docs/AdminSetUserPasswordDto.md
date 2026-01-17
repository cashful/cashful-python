# AdminSetUserPasswordDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user whose password to set | 
**new_password** | **str** | The new password to set | 

## Example

```python
from cashful.models.admin_set_user_password_dto import AdminSetUserPasswordDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminSetUserPasswordDto from a JSON string
admin_set_user_password_dto_instance = AdminSetUserPasswordDto.from_json(json)
# print the JSON string representation of the object
print(AdminSetUserPasswordDto.to_json())

# convert the object into a dict
admin_set_user_password_dto_dict = admin_set_user_password_dto_instance.to_dict()
# create an instance of AdminSetUserPasswordDto from a dict
admin_set_user_password_dto_from_dict = AdminSetUserPasswordDto.from_dict(admin_set_user_password_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


