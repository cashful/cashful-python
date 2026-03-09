# ListOrganizationsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[OrganizationDto]**](OrganizationDto.md) | List of organizations | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) | Pagination metadata | 

## Example

```python
from cashful.models.list_organizations_response_dto import ListOrganizationsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListOrganizationsResponseDto from a JSON string
list_organizations_response_dto_instance = ListOrganizationsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListOrganizationsResponseDto.to_json())

# convert the object into a dict
list_organizations_response_dto_dict = list_organizations_response_dto_instance.to_dict()
# create an instance of ListOrganizationsResponseDto from a dict
list_organizations_response_dto_from_dict = ListOrganizationsResponseDto.from_dict(list_organizations_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


