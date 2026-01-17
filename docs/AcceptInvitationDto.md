# AcceptInvitationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invitation_id** | **str** | The ID of the invitation to accept | 

## Example

```python
from cashful.models.accept_invitation_dto import AcceptInvitationDto

# TODO update the JSON string below
json = "{}"
# create an instance of AcceptInvitationDto from a JSON string
accept_invitation_dto_instance = AcceptInvitationDto.from_json(json)
# print the JSON string representation of the object
print(AcceptInvitationDto.to_json())

# convert the object into a dict
accept_invitation_dto_dict = accept_invitation_dto_instance.to_dict()
# create an instance of AcceptInvitationDto from a dict
accept_invitation_dto_from_dict = AcceptInvitationDto.from_dict(accept_invitation_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


