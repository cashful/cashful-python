# GetJsonWebTokenResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**token** | **str** | The JWT token | 

## Example

```python
from cashful.models.get_json_web_token_response_dto import GetJsonWebTokenResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetJsonWebTokenResponseDto from a JSON string
get_json_web_token_response_dto_instance = GetJsonWebTokenResponseDto.from_json(json)
# print the JSON string representation of the object
print(GetJsonWebTokenResponseDto.to_json())

# convert the object into a dict
get_json_web_token_response_dto_dict = get_json_web_token_response_dto_instance.to_dict()
# create an instance of GetJsonWebTokenResponseDto from a dict
get_json_web_token_response_dto_from_dict = GetJsonWebTokenResponseDto.from_dict(get_json_web_token_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


