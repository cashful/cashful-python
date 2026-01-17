# UpdateOrganizationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization** | [**OrganizationDto**](OrganizationDto.md) | Organization updated successfully | 

## Example

```python
from cashful.models.update_organization_response_dto import UpdateOrganizationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateOrganizationResponseDto from a JSON string
update_organization_response_dto_instance = UpdateOrganizationResponseDto.from_json(json)
# print the JSON string representation of the object
print(UpdateOrganizationResponseDto.to_json())

# convert the object into a dict
update_organization_response_dto_dict = update_organization_response_dto_instance.to_dict()
# create an instance of UpdateOrganizationResponseDto from a dict
update_organization_response_dto_from_dict = UpdateOrganizationResponseDto.from_dict(update_organization_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


