# DeleteApiKeyDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**key_id** | **str** | The ID of the API key to delete | 

## Example

```python
from cashful.models.delete_api_key_dto import DeleteApiKeyDto

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteApiKeyDto from a JSON string
delete_api_key_dto_instance = DeleteApiKeyDto.from_json(json)
# print the JSON string representation of the object
print(DeleteApiKeyDto.to_json())

# convert the object into a dict
delete_api_key_dto_dict = delete_api_key_dto_instance.to_dict()
# create an instance of DeleteApiKeyDto from a dict
delete_api_key_dto_from_dict = DeleteApiKeyDto.from_dict(delete_api_key_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


