# SetActiveOrganizationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization_id** | **str** | The ID of the organization to set as active | 

## Example

```python
from cashful.models.set_active_organization_dto import SetActiveOrganizationDto

# TODO update the JSON string below
json = "{}"
# create an instance of SetActiveOrganizationDto from a JSON string
set_active_organization_dto_instance = SetActiveOrganizationDto.from_json(json)
# print the JSON string representation of the object
print(SetActiveOrganizationDto.to_json())

# convert the object into a dict
set_active_organization_dto_dict = set_active_organization_dto_instance.to_dict()
# create an instance of SetActiveOrganizationDto from a dict
set_active_organization_dto_from_dict = SetActiveOrganizationDto.from_dict(set_active_organization_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


