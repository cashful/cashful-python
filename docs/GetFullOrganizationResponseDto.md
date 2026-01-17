# GetFullOrganizationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization** | [**OrganizationDto**](OrganizationDto.md) | The full organization object | 

## Example

```python
from cashful.models.get_full_organization_response_dto import GetFullOrganizationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetFullOrganizationResponseDto from a JSON string
get_full_organization_response_dto_instance = GetFullOrganizationResponseDto.from_json(json)
# print the JSON string representation of the object
print(GetFullOrganizationResponseDto.to_json())

# convert the object into a dict
get_full_organization_response_dto_dict = get_full_organization_response_dto_instance.to_dict()
# create an instance of GetFullOrganizationResponseDto from a dict
get_full_organization_response_dto_from_dict = GetFullOrganizationResponseDto.from_dict(get_full_organization_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


