# InviteMemberDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** | The email of the user to invite | 
**role** | **str** | The role to assign to the user | 
**organization_id** | **str** | The ID of the organization | 

## Example

```python
from cashful.models.invite_member_dto import InviteMemberDto

# TODO update the JSON string below
json = "{}"
# create an instance of InviteMemberDto from a JSON string
invite_member_dto_instance = InviteMemberDto.from_json(json)
# print the JSON string representation of the object
print(InviteMemberDto.to_json())

# convert the object into a dict
invite_member_dto_dict = invite_member_dto_instance.to_dict()
# create an instance of InviteMemberDto from a dict
invite_member_dto_from_dict = InviteMemberDto.from_dict(invite_member_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


