# AdminRevokeUserSessionsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | All user sessions revoked successfully | 

## Example

```python
from cashful.models.admin_revoke_user_sessions_response_dto import AdminRevokeUserSessionsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminRevokeUserSessionsResponseDto from a JSON string
admin_revoke_user_sessions_response_dto_instance = AdminRevokeUserSessionsResponseDto.from_json(json)
# print the JSON string representation of the object
print(AdminRevokeUserSessionsResponseDto.to_json())

# convert the object into a dict
admin_revoke_user_sessions_response_dto_dict = admin_revoke_user_sessions_response_dto_instance.to_dict()
# create an instance of AdminRevokeUserSessionsResponseDto from a dict
admin_revoke_user_sessions_response_dto_from_dict = AdminRevokeUserSessionsResponseDto.from_dict(admin_revoke_user_sessions_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


