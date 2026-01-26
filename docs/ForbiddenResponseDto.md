# ForbiddenResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status_code** | **float** | HTTP status code | 
**message** | **List[str]** |  | 
**error** | **str** | Error type | 

## Example

```python
from cashful.models.forbidden_response_dto import ForbiddenResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ForbiddenResponseDto from a JSON string
forbidden_response_dto_instance = ForbiddenResponseDto.from_json(json)
# print the JSON string representation of the object
print(ForbiddenResponseDto.to_json())

# convert the object into a dict
forbidden_response_dto_dict = forbidden_response_dto_instance.to_dict()
# create an instance of ForbiddenResponseDto from a dict
forbidden_response_dto_from_dict = ForbiddenResponseDto.from_dict(forbidden_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


