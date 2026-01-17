# AdminUpdateUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user to update | 
**data** | **object** | Data to update | 

## Example

```python
from cashful.models.admin_update_user_dto import AdminUpdateUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminUpdateUserDto from a JSON string
admin_update_user_dto_instance = AdminUpdateUserDto.from_json(json)
# print the JSON string representation of the object
print(AdminUpdateUserDto.to_json())

# convert the object into a dict
admin_update_user_dto_dict = admin_update_user_dto_instance.to_dict()
# create an instance of AdminUpdateUserDto from a dict
admin_update_user_dto_from_dict = AdminUpdateUserDto.from_dict(admin_update_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


