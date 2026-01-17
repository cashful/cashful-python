# CancelInvitationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invitation_id** | **str** | The ID of the invitation to cancel | 

## Example

```python
from cashful.models.cancel_invitation_dto import CancelInvitationDto

# TODO update the JSON string below
json = "{}"
# create an instance of CancelInvitationDto from a JSON string
cancel_invitation_dto_instance = CancelInvitationDto.from_json(json)
# print the JSON string representation of the object
print(CancelInvitationDto.to_json())

# convert the object into a dict
cancel_invitation_dto_dict = cancel_invitation_dto_instance.to_dict()
# create an instance of CancelInvitationDto from a dict
cancel_invitation_dto_from_dict = CancelInvitationDto.from_dict(cancel_invitation_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


