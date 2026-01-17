# SetRoleResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Role set successfully | 

## Example

```python
from cashful.models.set_role_response_dto import SetRoleResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of SetRoleResponseDto from a JSON string
set_role_response_dto_instance = SetRoleResponseDto.from_json(json)
# print the JSON string representation of the object
print(SetRoleResponseDto.to_json())

# convert the object into a dict
set_role_response_dto_dict = set_role_response_dto_instance.to_dict()
# create an instance of SetRoleResponseDto from a dict
set_role_response_dto_from_dict = SetRoleResponseDto.from_dict(set_role_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


