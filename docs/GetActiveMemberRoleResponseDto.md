# GetActiveMemberRoleResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**role** | **str** | Active member role information | 

## Example

```python
from cashful.models.get_active_member_role_response_dto import GetActiveMemberRoleResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetActiveMemberRoleResponseDto from a JSON string
get_active_member_role_response_dto_instance = GetActiveMemberRoleResponseDto.from_json(json)
# print the JSON string representation of the object
print(GetActiveMemberRoleResponseDto.to_json())

# convert the object into a dict
get_active_member_role_response_dto_dict = get_active_member_role_response_dto_instance.to_dict()
# create an instance of GetActiveMemberRoleResponseDto from a dict
get_active_member_role_response_dto_from_dict = GetActiveMemberRoleResponseDto.from_dict(get_active_member_role_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


