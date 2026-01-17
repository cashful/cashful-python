# GetInvitationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invitation** | [**InvitationDto**](InvitationDto.md) | Invitation details | 

## Example

```python
from cashful.models.get_invitation_response_dto import GetInvitationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvitationResponseDto from a JSON string
get_invitation_response_dto_instance = GetInvitationResponseDto.from_json(json)
# print the JSON string representation of the object
print(GetInvitationResponseDto.to_json())

# convert the object into a dict
get_invitation_response_dto_dict = get_invitation_response_dto_instance.to_dict()
# create an instance of GetInvitationResponseDto from a dict
get_invitation_response_dto_from_dict = GetInvitationResponseDto.from_dict(get_invitation_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


