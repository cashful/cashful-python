# InviteMemberResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invitation** | **object** | Member invited successfully | 

## Example

```python
from cashful.models.invite_member_response_dto import InviteMemberResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of InviteMemberResponseDto from a JSON string
invite_member_response_dto_instance = InviteMemberResponseDto.from_json(json)
# print the JSON string representation of the object
print(InviteMemberResponseDto.to_json())

# convert the object into a dict
invite_member_response_dto_dict = invite_member_response_dto_instance.to_dict()
# create an instance of InviteMemberResponseDto from a dict
invite_member_response_dto_from_dict = InviteMemberResponseDto.from_dict(invite_member_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


