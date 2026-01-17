# AdminListUserSessionsDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user whose sessions to list | 

## Example

```python
from cashful.models.admin_list_user_sessions_dto import AdminListUserSessionsDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminListUserSessionsDto from a JSON string
admin_list_user_sessions_dto_instance = AdminListUserSessionsDto.from_json(json)
# print the JSON string representation of the object
print(AdminListUserSessionsDto.to_json())

# convert the object into a dict
admin_list_user_sessions_dto_dict = admin_list_user_sessions_dto_instance.to_dict()
# create an instance of AdminListUserSessionsDto from a dict
admin_list_user_sessions_dto_from_dict = AdminListUserSessionsDto.from_dict(admin_list_user_sessions_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


