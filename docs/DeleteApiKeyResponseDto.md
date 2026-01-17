# DeleteApiKeyResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | API key deleted successfully | 

## Example

```python
from cashful.models.delete_api_key_response_dto import DeleteApiKeyResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteApiKeyResponseDto from a JSON string
delete_api_key_response_dto_instance = DeleteApiKeyResponseDto.from_json(json)
# print the JSON string representation of the object
print(DeleteApiKeyResponseDto.to_json())

# convert the object into a dict
delete_api_key_response_dto_dict = delete_api_key_response_dto_instance.to_dict()
# create an instance of DeleteApiKeyResponseDto from a dict
delete_api_key_response_dto_from_dict = DeleteApiKeyResponseDto.from_dict(delete_api_key_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


