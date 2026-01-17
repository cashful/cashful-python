# CreateOrganizationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the organization | 
**slug** | **str** | The slug of the organization | 
**logo** | **str** | The logo of the organization | [optional] 
**metadata** | **object** | Metadata for the organization | [optional] 

## Example

```python
from cashful.models.create_organization_dto import CreateOrganizationDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateOrganizationDto from a JSON string
create_organization_dto_instance = CreateOrganizationDto.from_json(json)
# print the JSON string representation of the object
print(CreateOrganizationDto.to_json())

# convert the object into a dict
create_organization_dto_dict = create_organization_dto_instance.to_dict()
# create an instance of CreateOrganizationDto from a dict
create_organization_dto_from_dict = CreateOrganizationDto.from_dict(create_organization_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


