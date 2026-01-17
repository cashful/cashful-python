# UpdateApiKeyResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**api_key** | [**ApiKey**](ApiKey.md) | API key updated successfully | 

## Example

```python
from cashful.models.update_api_key_response_dto import UpdateApiKeyResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateApiKeyResponseDto from a JSON string
update_api_key_response_dto_instance = UpdateApiKeyResponseDto.from_json(json)
# print the JSON string representation of the object
print(UpdateApiKeyResponseDto.to_json())

# convert the object into a dict
update_api_key_response_dto_dict = update_api_key_response_dto_instance.to_dict()
# create an instance of UpdateApiKeyResponseDto from a dict
update_api_key_response_dto_from_dict = UpdateApiKeyResponseDto.from_dict(update_api_key_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


