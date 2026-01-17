# AdminGetUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user to get | 

## Example

```python
from cashful.models.admin_get_user_dto import AdminGetUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminGetUserDto from a JSON string
admin_get_user_dto_instance = AdminGetUserDto.from_json(json)
# print the JSON string representation of the object
print(AdminGetUserDto.to_json())

# convert the object into a dict
admin_get_user_dto_dict = admin_get_user_dto_instance.to_dict()
# create an instance of AdminGetUserDto from a dict
admin_get_user_dto_from_dict = AdminGetUserDto.from_dict(admin_get_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


