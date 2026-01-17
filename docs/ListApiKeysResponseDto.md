# ListApiKeysResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**api_keys** | [**List[ApiKey]**](ApiKey.md) | List of API keys | 

## Example

```python
from cashful.models.list_api_keys_response_dto import ListApiKeysResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListApiKeysResponseDto from a JSON string
list_api_keys_response_dto_instance = ListApiKeysResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListApiKeysResponseDto.to_json())

# convert the object into a dict
list_api_keys_response_dto_dict = list_api_keys_response_dto_instance.to_dict()
# create an instance of ListApiKeysResponseDto from a dict
list_api_keys_response_dto_from_dict = ListApiKeysResponseDto.from_dict(list_api_keys_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


