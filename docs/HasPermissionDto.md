# HasPermissionDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**permission** | **object** | The permission to check | 
**resource** | **str** | The resource to check permission on | [optional] 
**organization_id** | **str** | The organization ID to check permission in | [optional] 

## Example

```python
from cashful.models.has_permission_dto import HasPermissionDto

# TODO update the JSON string below
json = "{}"
# create an instance of HasPermissionDto from a JSON string
has_permission_dto_instance = HasPermissionDto.from_json(json)
# print the JSON string representation of the object
print(HasPermissionDto.to_json())

# convert the object into a dict
has_permission_dto_dict = has_permission_dto_instance.to_dict()
# create an instance of HasPermissionDto from a dict
has_permission_dto_from_dict = HasPermissionDto.from_dict(has_permission_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


