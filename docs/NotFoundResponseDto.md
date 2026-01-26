# NotFoundResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status_code** | **float** | HTTP status code | 
**message** | **List[str]** |  | 
**error** | **str** | Error type | 

## Example

```python
from cashful.models.not_found_response_dto import NotFoundResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of NotFoundResponseDto from a JSON string
not_found_response_dto_instance = NotFoundResponseDto.from_json(json)
# print the JSON string representation of the object
print(NotFoundResponseDto.to_json())

# convert the object into a dict
not_found_response_dto_dict = not_found_response_dto_instance.to_dict()
# create an instance of NotFoundResponseDto from a dict
not_found_response_dto_from_dict = NotFoundResponseDto.from_dict(not_found_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


