# UnauthorizedResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status_code** | **float** | HTTP status code | 
**message** | **List[str]** |  | 
**error** | **str** | Error type | 

## Example

```python
from cashful.models.unauthorized_response_dto import UnauthorizedResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of UnauthorizedResponseDto from a JSON string
unauthorized_response_dto_instance = UnauthorizedResponseDto.from_json(json)
# print the JSON string representation of the object
print(UnauthorizedResponseDto.to_json())

# convert the object into a dict
unauthorized_response_dto_dict = unauthorized_response_dto_instance.to_dict()
# create an instance of UnauthorizedResponseDto from a dict
unauthorized_response_dto_from_dict = UnauthorizedResponseDto.from_dict(unauthorized_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


