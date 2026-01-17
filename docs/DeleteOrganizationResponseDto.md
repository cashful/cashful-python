# DeleteOrganizationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Organization deleted successfully | 

## Example

```python
from cashful.models.delete_organization_response_dto import DeleteOrganizationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteOrganizationResponseDto from a JSON string
delete_organization_response_dto_instance = DeleteOrganizationResponseDto.from_json(json)
# print the JSON string representation of the object
print(DeleteOrganizationResponseDto.to_json())

# convert the object into a dict
delete_organization_response_dto_dict = delete_organization_response_dto_instance.to_dict()
# create an instance of DeleteOrganizationResponseDto from a dict
delete_organization_response_dto_from_dict = DeleteOrganizationResponseDto.from_dict(delete_organization_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


