# AdminSetUserPasswordResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | User password set successfully | 

## Example

```python
from cashful.models.admin_set_user_password_response_dto import AdminSetUserPasswordResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminSetUserPasswordResponseDto from a JSON string
admin_set_user_password_response_dto_instance = AdminSetUserPasswordResponseDto.from_json(json)
# print the JSON string representation of the object
print(AdminSetUserPasswordResponseDto.to_json())

# convert the object into a dict
admin_set_user_password_response_dto_dict = admin_set_user_password_response_dto_instance.to_dict()
# create an instance of AdminSetUserPasswordResponseDto from a dict
admin_set_user_password_response_dto_from_dict = AdminSetUserPasswordResponseDto.from_dict(admin_set_user_password_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


