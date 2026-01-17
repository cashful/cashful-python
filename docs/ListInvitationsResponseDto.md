# ListInvitationsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invitations** | [**List[InvitationDto]**](InvitationDto.md) | List of invitations | 

## Example

```python
from cashful.models.list_invitations_response_dto import ListInvitationsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListInvitationsResponseDto from a JSON string
list_invitations_response_dto_instance = ListInvitationsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListInvitationsResponseDto.to_json())

# convert the object into a dict
list_invitations_response_dto_dict = list_invitations_response_dto_instance.to_dict()
# create an instance of ListInvitationsResponseDto from a dict
list_invitations_response_dto_from_dict = ListInvitationsResponseDto.from_dict(list_invitations_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


