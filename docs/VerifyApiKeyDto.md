# VerifyApiKeyDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**key** | **str** | The API key to verify | 

## Example

```python
from cashful.models.verify_api_key_dto import VerifyApiKeyDto

# TODO update the JSON string below
json = "{}"
# create an instance of VerifyApiKeyDto from a JSON string
verify_api_key_dto_instance = VerifyApiKeyDto.from_json(json)
# print the JSON string representation of the object
print(VerifyApiKeyDto.to_json())

# convert the object into a dict
verify_api_key_dto_dict = verify_api_key_dto_instance.to_dict()
# create an instance of VerifyApiKeyDto from a dict
verify_api_key_dto_from_dict = VerifyApiKeyDto.from_dict(verify_api_key_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


