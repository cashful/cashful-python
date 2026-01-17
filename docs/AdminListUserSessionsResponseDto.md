# AdminListUserSessionsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sessions** | [**List[SessionDto]**](SessionDto.md) | User sessions listed successfully | 

## Example

```python
from cashful.models.admin_list_user_sessions_response_dto import AdminListUserSessionsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminListUserSessionsResponseDto from a JSON string
admin_list_user_sessions_response_dto_instance = AdminListUserSessionsResponseDto.from_json(json)
# print the JSON string representation of the object
print(AdminListUserSessionsResponseDto.to_json())

# convert the object into a dict
admin_list_user_sessions_response_dto_dict = admin_list_user_sessions_response_dto_instance.to_dict()
# create an instance of AdminListUserSessionsResponseDto from a dict
admin_list_user_sessions_response_dto_from_dict = AdminListUserSessionsResponseDto.from_dict(admin_list_user_sessions_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


