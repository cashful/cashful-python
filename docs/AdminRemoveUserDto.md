# AdminRemoveUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user to remove | 

## Example

```python
from cashful.models.admin_remove_user_dto import AdminRemoveUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminRemoveUserDto from a JSON string
admin_remove_user_dto_instance = AdminRemoveUserDto.from_json(json)
# print the JSON string representation of the object
print(AdminRemoveUserDto.to_json())

# convert the object into a dict
admin_remove_user_dto_dict = admin_remove_user_dto_instance.to_dict()
# create an instance of AdminRemoveUserDto from a dict
admin_remove_user_dto_from_dict = AdminRemoveUserDto.from_dict(admin_remove_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


