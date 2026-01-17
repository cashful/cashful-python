# AdminRevokeUserSessionDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user whose session to revoke | 
**session_id** | **str** | The ID of the session to revoke | 

## Example

```python
from cashful.models.admin_revoke_user_session_dto import AdminRevokeUserSessionDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminRevokeUserSessionDto from a JSON string
admin_revoke_user_session_dto_instance = AdminRevokeUserSessionDto.from_json(json)
# print the JSON string representation of the object
print(AdminRevokeUserSessionDto.to_json())

# convert the object into a dict
admin_revoke_user_session_dto_dict = admin_revoke_user_session_dto_instance.to_dict()
# create an instance of AdminRevokeUserSessionDto from a dict
admin_revoke_user_session_dto_from_dict = AdminRevokeUserSessionDto.from_dict(admin_revoke_user_session_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


