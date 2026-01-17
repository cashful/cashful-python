# RemoveMemberResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Member removed successfully | 

## Example

```python
from cashful.models.remove_member_response_dto import RemoveMemberResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of RemoveMemberResponseDto from a JSON string
remove_member_response_dto_instance = RemoveMemberResponseDto.from_json(json)
# print the JSON string representation of the object
print(RemoveMemberResponseDto.to_json())

# convert the object into a dict
remove_member_response_dto_dict = remove_member_response_dto_instance.to_dict()
# create an instance of RemoveMemberResponseDto from a dict
remove_member_response_dto_from_dict = RemoveMemberResponseDto.from_dict(remove_member_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


