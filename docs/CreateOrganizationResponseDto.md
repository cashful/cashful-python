# CreateOrganizationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization** | [**OrganizationDto**](OrganizationDto.md) | Organization created successfully | 

## Example

```python
from cashful.models.create_organization_response_dto import CreateOrganizationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateOrganizationResponseDto from a JSON string
create_organization_response_dto_instance = CreateOrganizationResponseDto.from_json(json)
# print the JSON string representation of the object
print(CreateOrganizationResponseDto.to_json())

# convert the object into a dict
create_organization_response_dto_dict = create_organization_response_dto_instance.to_dict()
# create an instance of CreateOrganizationResponseDto from a dict
create_organization_response_dto_from_dict = CreateOrganizationResponseDto.from_dict(create_organization_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


