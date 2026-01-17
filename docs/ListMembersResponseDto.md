# ListMembersResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**members** | [**List[MemberDto]**](MemberDto.md) | List of organization members | 

## Example

```python
from cashful.models.list_members_response_dto import ListMembersResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListMembersResponseDto from a JSON string
list_members_response_dto_instance = ListMembersResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListMembersResponseDto.to_json())

# convert the object into a dict
list_members_response_dto_dict = list_members_response_dto_instance.to_dict()
# create an instance of ListMembersResponseDto from a dict
list_members_response_dto_from_dict = ListMembersResponseDto.from_dict(list_members_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


