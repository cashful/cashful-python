# ListUserInvitationsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invitations** | [**List[InvitationDto]**](InvitationDto.md) | List of user invitations | 

## Example

```python
from cashful.models.list_user_invitations_response_dto import ListUserInvitationsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListUserInvitationsResponseDto from a JSON string
list_user_invitations_response_dto_instance = ListUserInvitationsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListUserInvitationsResponseDto.to_json())

# convert the object into a dict
list_user_invitations_response_dto_dict = list_user_invitations_response_dto_instance.to_dict()
# create an instance of ListUserInvitationsResponseDto from a dict
list_user_invitations_response_dto_from_dict = ListUserInvitationsResponseDto.from_dict(list_user_invitations_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


