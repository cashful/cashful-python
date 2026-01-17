# AdminRevokeUserSessionsDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user whose sessions to revoke | 

## Example

```python
from cashful.models.admin_revoke_user_sessions_dto import AdminRevokeUserSessionsDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminRevokeUserSessionsDto from a JSON string
admin_revoke_user_sessions_dto_instance = AdminRevokeUserSessionsDto.from_json(json)
# print the JSON string representation of the object
print(AdminRevokeUserSessionsDto.to_json())

# convert the object into a dict
admin_revoke_user_sessions_dto_dict = admin_revoke_user_sessions_dto_instance.to_dict()
# create an instance of AdminRevokeUserSessionsDto from a dict
admin_revoke_user_sessions_dto_from_dict = AdminRevokeUserSessionsDto.from_dict(admin_revoke_user_sessions_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


