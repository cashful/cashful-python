# UpdateOrganizationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization_id** | **str** | The ID of the organization to update | 
**data** | **object** | Data to update | 

## Example

```python
from cashful.models.update_organization_dto import UpdateOrganizationDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateOrganizationDto from a JSON string
update_organization_dto_instance = UpdateOrganizationDto.from_json(json)
# print the JSON string representation of the object
print(UpdateOrganizationDto.to_json())

# convert the object into a dict
update_organization_dto_dict = update_organization_dto_instance.to_dict()
# create an instance of UpdateOrganizationDto from a dict
update_organization_dto_from_dict = UpdateOrganizationDto.from_dict(update_organization_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


