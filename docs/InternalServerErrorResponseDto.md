# InternalServerErrorResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status_code** | **float** | HTTP status code | 
**message** | **List[str]** |  | 
**error** | **str** | Error type | 

## Example

```python
from cashful.models.internal_server_error_response_dto import InternalServerErrorResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of InternalServerErrorResponseDto from a JSON string
internal_server_error_response_dto_instance = InternalServerErrorResponseDto.from_json(json)
# print the JSON string representation of the object
print(InternalServerErrorResponseDto.to_json())

# convert the object into a dict
internal_server_error_response_dto_dict = internal_server_error_response_dto_instance.to_dict()
# create an instance of InternalServerErrorResponseDto from a dict
internal_server_error_response_dto_from_dict = InternalServerErrorResponseDto.from_dict(internal_server_error_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


