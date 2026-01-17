# IVeriHealthCheckResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Service health status | 
**timestamp** | **str** | Current server timestamp in ISO format | 

## Example

```python
from cashful.models.i_veri_health_check_response_dto import IVeriHealthCheckResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of IVeriHealthCheckResponseDto from a JSON string
i_veri_health_check_response_dto_instance = IVeriHealthCheckResponseDto.from_json(json)
# print the JSON string representation of the object
print(IVeriHealthCheckResponseDto.to_json())

# convert the object into a dict
i_veri_health_check_response_dto_dict = i_veri_health_check_response_dto_instance.to_dict()
# create an instance of IVeriHealthCheckResponseDto from a dict
i_veri_health_check_response_dto_from_dict = IVeriHealthCheckResponseDto.from_dict(i_veri_health_check_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


