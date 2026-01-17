# LeaveOrganizationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Leave operation result | 

## Example

```python
from cashful.models.leave_organization_response_dto import LeaveOrganizationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of LeaveOrganizationResponseDto from a JSON string
leave_organization_response_dto_instance = LeaveOrganizationResponseDto.from_json(json)
# print the JSON string representation of the object
print(LeaveOrganizationResponseDto.to_json())

# convert the object into a dict
leave_organization_response_dto_dict = leave_organization_response_dto_instance.to_dict()
# create an instance of LeaveOrganizationResponseDto from a dict
leave_organization_response_dto_from_dict = LeaveOrganizationResponseDto.from_dict(leave_organization_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


