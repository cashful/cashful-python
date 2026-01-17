# AcceptInvitationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Invitation accepted successfully | 

## Example

```python
from cashful.models.accept_invitation_response_dto import AcceptInvitationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of AcceptInvitationResponseDto from a JSON string
accept_invitation_response_dto_instance = AcceptInvitationResponseDto.from_json(json)
# print the JSON string representation of the object
print(AcceptInvitationResponseDto.to_json())

# convert the object into a dict
accept_invitation_response_dto_dict = accept_invitation_response_dto_instance.to_dict()
# create an instance of AcceptInvitationResponseDto from a dict
accept_invitation_response_dto_from_dict = AcceptInvitationResponseDto.from_dict(accept_invitation_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


