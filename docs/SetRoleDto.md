# SetRoleDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user | 
**role** | **str** | The role to assign | 

## Example

```python
from cashful.models.set_role_dto import SetRoleDto

# TODO update the JSON string below
json = "{}"
# create an instance of SetRoleDto from a JSON string
set_role_dto_instance = SetRoleDto.from_json(json)
# print the JSON string representation of the object
print(SetRoleDto.to_json())

# convert the object into a dict
set_role_dto_dict = set_role_dto_instance.to_dict()
# create an instance of SetRoleDto from a dict
set_role_dto_from_dict = SetRoleDto.from_dict(set_role_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


