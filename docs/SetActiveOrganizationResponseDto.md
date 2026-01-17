# SetActiveOrganizationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Active organization set successfully | 

## Example

```python
from cashful.models.set_active_organization_response_dto import SetActiveOrganizationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of SetActiveOrganizationResponseDto from a JSON string
set_active_organization_response_dto_instance = SetActiveOrganizationResponseDto.from_json(json)
# print the JSON string representation of the object
print(SetActiveOrganizationResponseDto.to_json())

# convert the object into a dict
set_active_organization_response_dto_dict = set_active_organization_response_dto_instance.to_dict()
# create an instance of SetActiveOrganizationResponseDto from a dict
set_active_organization_response_dto_from_dict = SetActiveOrganizationResponseDto.from_dict(set_active_organization_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


