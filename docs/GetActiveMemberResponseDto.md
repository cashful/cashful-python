# GetActiveMemberResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**member** | [**MemberDto**](MemberDto.md) | Active member details | 

## Example

```python
from cashful.models.get_active_member_response_dto import GetActiveMemberResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetActiveMemberResponseDto from a JSON string
get_active_member_response_dto_instance = GetActiveMemberResponseDto.from_json(json)
# print the JSON string representation of the object
print(GetActiveMemberResponseDto.to_json())

# convert the object into a dict
get_active_member_response_dto_dict = get_active_member_response_dto_instance.to_dict()
# create an instance of GetActiveMemberResponseDto from a dict
get_active_member_response_dto_from_dict = GetActiveMemberResponseDto.from_dict(get_active_member_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


