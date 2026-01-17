# RejectInvitationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invitation_id** | **str** | The ID of the invitation to reject | 

## Example

```python
from cashful.models.reject_invitation_dto import RejectInvitationDto

# TODO update the JSON string below
json = "{}"
# create an instance of RejectInvitationDto from a JSON string
reject_invitation_dto_instance = RejectInvitationDto.from_json(json)
# print the JSON string representation of the object
print(RejectInvitationDto.to_json())

# convert the object into a dict
reject_invitation_dto_dict = reject_invitation_dto_instance.to_dict()
# create an instance of RejectInvitationDto from a dict
reject_invitation_dto_from_dict = RejectInvitationDto.from_dict(reject_invitation_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


