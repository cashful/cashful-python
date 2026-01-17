# UpdateMemberRoleResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Member role updated successfully | 

## Example

```python
from cashful.models.update_member_role_response_dto import UpdateMemberRoleResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateMemberRoleResponseDto from a JSON string
update_member_role_response_dto_instance = UpdateMemberRoleResponseDto.from_json(json)
# print the JSON string representation of the object
print(UpdateMemberRoleResponseDto.to_json())

# convert the object into a dict
update_member_role_response_dto_dict = update_member_role_response_dto_instance.to_dict()
# create an instance of UpdateMemberRoleResponseDto from a dict
update_member_role_response_dto_from_dict = UpdateMemberRoleResponseDto.from_dict(update_member_role_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


