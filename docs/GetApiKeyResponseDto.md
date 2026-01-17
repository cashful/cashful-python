# GetApiKeyResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**api_key** | [**ApiKey**](ApiKey.md) | API key retrieved successfully | 

## Example

```python
from cashful.models.get_api_key_response_dto import GetApiKeyResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetApiKeyResponseDto from a JSON string
get_api_key_response_dto_instance = GetApiKeyResponseDto.from_json(json)
# print the JSON string representation of the object
print(GetApiKeyResponseDto.to_json())

# convert the object into a dict
get_api_key_response_dto_dict = get_api_key_response_dto_instance.to_dict()
# create an instance of GetApiKeyResponseDto from a dict
get_api_key_response_dto_from_dict = GetApiKeyResponseDto.from_dict(get_api_key_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


