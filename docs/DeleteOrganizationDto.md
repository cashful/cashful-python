# DeleteOrganizationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization_id** | **str** | The ID of the organization to delete | 

## Example

```python
from cashful.models.delete_organization_dto import DeleteOrganizationDto

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteOrganizationDto from a JSON string
delete_organization_dto_instance = DeleteOrganizationDto.from_json(json)
# print the JSON string representation of the object
print(DeleteOrganizationDto.to_json())

# convert the object into a dict
delete_organization_dto_dict = delete_organization_dto_instance.to_dict()
# create an instance of DeleteOrganizationDto from a dict
delete_organization_dto_from_dict = DeleteOrganizationDto.from_dict(delete_organization_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


