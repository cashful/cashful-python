# OrganizationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Organization ID | 
**name** | **str** | Organization name | 
**slug** | **str** | Organization slug | 
**logo** | **str** | Organization logo | [optional] 
**created_at** | **str** | Organization creation date | 
**metadata** | **object** | Organization metadata | [optional] 

## Example

```python
from cashful.models.organization_dto import OrganizationDto

# TODO update the JSON string below
json = "{}"
# create an instance of OrganizationDto from a JSON string
organization_dto_instance = OrganizationDto.from_json(json)
# print the JSON string representation of the object
print(OrganizationDto.to_json())

# convert the object into a dict
organization_dto_dict = organization_dto_instance.to_dict()
# create an instance of OrganizationDto from a dict
organization_dto_from_dict = OrganizationDto.from_dict(organization_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


