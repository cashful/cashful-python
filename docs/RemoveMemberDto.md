# RemoveMemberDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**member_id** | **str** | The ID of the member to remove | 
**organization_id** | **str** | The ID of the organization | 

## Example

```python
from cashful.models.remove_member_dto import RemoveMemberDto

# TODO update the JSON string below
json = "{}"
# create an instance of RemoveMemberDto from a JSON string
remove_member_dto_instance = RemoveMemberDto.from_json(json)
# print the JSON string representation of the object
print(RemoveMemberDto.to_json())

# convert the object into a dict
remove_member_dto_dict = remove_member_dto_instance.to_dict()
# create an instance of RemoveMemberDto from a dict
remove_member_dto_from_dict = RemoveMemberDto.from_dict(remove_member_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


