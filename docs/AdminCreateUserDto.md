# AdminCreateUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the user | 
**email** | **str** | The email address of the user | 
**password** | **str** | The password for the user account | 
**role** | **str** | Optional role to assign to user | [optional] 
**email_verified** | **bool** | Whether the user should be verified by default | [optional] 

## Example

```python
from cashful.models.admin_create_user_dto import AdminCreateUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminCreateUserDto from a JSON string
admin_create_user_dto_instance = AdminCreateUserDto.from_json(json)
# print the JSON string representation of the object
print(AdminCreateUserDto.to_json())

# convert the object into a dict
admin_create_user_dto_dict = admin_create_user_dto_instance.to_dict()
# create an instance of AdminCreateUserDto from a dict
admin_create_user_dto_from_dict = AdminCreateUserDto.from_dict(admin_create_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


