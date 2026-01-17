# RejectInvitationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Invitation rejected successfully | 

## Example

```python
from cashful.models.reject_invitation_response_dto import RejectInvitationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of RejectInvitationResponseDto from a JSON string
reject_invitation_response_dto_instance = RejectInvitationResponseDto.from_json(json)
# print the JSON string representation of the object
print(RejectInvitationResponseDto.to_json())

# convert the object into a dict
reject_invitation_response_dto_dict = reject_invitation_response_dto_instance.to_dict()
# create an instance of RejectInvitationResponseDto from a dict
reject_invitation_response_dto_from_dict = RejectInvitationResponseDto.from_dict(reject_invitation_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


