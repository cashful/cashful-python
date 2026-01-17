# VerifyApiKeyResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**valid** | **bool** | API key verification result | 
**key** | **object** | API key details (without the actual key) | [optional] 

## Example

```python
from cashful.models.verify_api_key_response_dto import VerifyApiKeyResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of VerifyApiKeyResponseDto from a JSON string
verify_api_key_response_dto_instance = VerifyApiKeyResponseDto.from_json(json)
# print the JSON string representation of the object
print(VerifyApiKeyResponseDto.to_json())

# convert the object into a dict
verify_api_key_response_dto_dict = verify_api_key_response_dto_instance.to_dict()
# create an instance of VerifyApiKeyResponseDto from a dict
verify_api_key_response_dto_from_dict = VerifyApiKeyResponseDto.from_dict(verify_api_key_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


