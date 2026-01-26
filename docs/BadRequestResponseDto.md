# BadRequestResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status_code** | **float** | HTTP status code | 
**message** | **List[str]** |  | 
**error** | **str** | Error type | 

## Example

```python
from cashful.models.bad_request_response_dto import BadRequestResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of BadRequestResponseDto from a JSON string
bad_request_response_dto_instance = BadRequestResponseDto.from_json(json)
# print the JSON string representation of the object
print(BadRequestResponseDto.to_json())

# convert the object into a dict
bad_request_response_dto_dict = bad_request_response_dto_instance.to_dict()
# create an instance of BadRequestResponseDto from a dict
bad_request_response_dto_from_dict = BadRequestResponseDto.from_dict(bad_request_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


