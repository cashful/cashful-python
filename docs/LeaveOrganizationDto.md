# LeaveOrganizationDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization_id** | **str** | The organization ID to leave | 

## Example

```python
from cashful.models.leave_organization_dto import LeaveOrganizationDto

# TODO update the JSON string below
json = "{}"
# create an instance of LeaveOrganizationDto from a JSON string
leave_organization_dto_instance = LeaveOrganizationDto.from_json(json)
# print the JSON string representation of the object
print(LeaveOrganizationDto.to_json())

# convert the object into a dict
leave_organization_dto_dict = leave_organization_dto_instance.to_dict()
# create an instance of LeaveOrganizationDto from a dict
leave_organization_dto_from_dict = LeaveOrganizationDto.from_dict(leave_organization_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


