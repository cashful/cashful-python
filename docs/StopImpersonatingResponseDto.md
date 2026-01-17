# StopImpersonatingResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Stopped impersonating successfully | 

## Example

```python
from cashful.models.stop_impersonating_response_dto import StopImpersonatingResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of StopImpersonatingResponseDto from a JSON string
stop_impersonating_response_dto_instance = StopImpersonatingResponseDto.from_json(json)
# print the JSON string representation of the object
print(StopImpersonatingResponseDto.to_json())

# convert the object into a dict
stop_impersonating_response_dto_dict = stop_impersonating_response_dto_instance.to_dict()
# create an instance of StopImpersonatingResponseDto from a dict
stop_impersonating_response_dto_from_dict = StopImpersonatingResponseDto.from_dict(stop_impersonating_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


