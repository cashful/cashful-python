# ListOrganizationComplianceResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[OrganizationComplianceResponseDto]**](OrganizationComplianceResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_organization_compliance_response_dto import ListOrganizationComplianceResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListOrganizationComplianceResponseDto from a JSON string
list_organization_compliance_response_dto_instance = ListOrganizationComplianceResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListOrganizationComplianceResponseDto.to_json())

# convert the object into a dict
list_organization_compliance_response_dto_dict = list_organization_compliance_response_dto_instance.to_dict()
# create an instance of ListOrganizationComplianceResponseDto from a dict
list_organization_compliance_response_dto_from_dict = ListOrganizationComplianceResponseDto.from_dict(list_organization_compliance_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


