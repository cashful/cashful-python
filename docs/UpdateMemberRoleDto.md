# UpdateMemberRoleDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**member_id** | **str** | The ID of the member to update | 
**role** | **str** | The new role | 
**organization_id** | **str** | The ID of the organization | 

## Example

```python
from cashful.models.update_member_role_dto import UpdateMemberRoleDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateMemberRoleDto from a JSON string
update_member_role_dto_instance = UpdateMemberRoleDto.from_json(json)
# print the JSON string representation of the object
print(UpdateMemberRoleDto.to_json())

# convert the object into a dict
update_member_role_dto_dict = update_member_role_dto_instance.to_dict()
# create an instance of UpdateMemberRoleDto from a dict
update_member_role_dto_from_dict = UpdateMemberRoleDto.from_dict(update_member_role_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


