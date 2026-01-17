# CreateApiKeyResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**api_key** | [**ApiKey**](ApiKey.md) | API key created successfully | 

## Example

```python
from cashful.models.create_api_key_response_dto import CreateApiKeyResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateApiKeyResponseDto from a JSON string
create_api_key_response_dto_instance = CreateApiKeyResponseDto.from_json(json)
# print the JSON string representation of the object
print(CreateApiKeyResponseDto.to_json())

# convert the object into a dict
create_api_key_response_dto_dict = create_api_key_response_dto_instance.to_dict()
# create an instance of CreateApiKeyResponseDto from a dict
create_api_key_response_dto_from_dict = CreateApiKeyResponseDto.from_dict(create_api_key_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


