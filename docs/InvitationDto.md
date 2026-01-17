# InvitationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Invitation ID | 
**organization_id** | **str** | Organization ID | 
**email** | **str** | Invited email | 
**role** | **str** | Invitation role | 
**status** | **str** | Invitation status | 
**expires_at** | **str** | Invitation expiration date | 
**created_at** | **str** | Invitation creation date | 
**inviter_id** | **str** | Inviter ID | 

## Example

```python
from cashful.models.invitation_dto import InvitationDto

# TODO update the JSON string below
json = "{}"
# create an instance of InvitationDto from a JSON string
invitation_dto_instance = InvitationDto.from_json(json)
# print the JSON string representation of the object
print(InvitationDto.to_json())

# convert the object into a dict
invitation_dto_dict = invitation_dto_instance.to_dict()
# create an instance of InvitationDto from a dict
invitation_dto_from_dict = InvitationDto.from_dict(invitation_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


