# CancelInvitationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Invitation cancelled successfully | 

## Example

```python
from cashful.models.cancel_invitation_response_dto import CancelInvitationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of CancelInvitationResponseDto from a JSON string
cancel_invitation_response_dto_instance = CancelInvitationResponseDto.from_json(json)
# print the JSON string representation of the object
print(CancelInvitationResponseDto.to_json())

# convert the object into a dict
cancel_invitation_response_dto_dict = cancel_invitation_response_dto_instance.to_dict()
# create an instance of CancelInvitationResponseDto from a dict
cancel_invitation_response_dto_from_dict = CancelInvitationResponseDto.from_dict(cancel_invitation_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


