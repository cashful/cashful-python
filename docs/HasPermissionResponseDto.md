# HasPermissionResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**has_permission** | **bool** | Whether user has permission | 

## Example

```python
from cashful.models.has_permission_response_dto import HasPermissionResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of HasPermissionResponseDto from a JSON string
has_permission_response_dto_instance = HasPermissionResponseDto.from_json(json)
# print the JSON string representation of the object
print(HasPermissionResponseDto.to_json())

# convert the object into a dict
has_permission_response_dto_dict = has_permission_response_dto_instance.to_dict()
# create an instance of HasPermissionResponseDto from a dict
has_permission_response_dto_from_dict = HasPermissionResponseDto.from_dict(has_permission_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


