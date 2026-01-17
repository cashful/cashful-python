# UpdateApiKeyDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**key_id** | **str** | The ID of the API key to update | 
**name** | **str** | The new name of the API key | [optional] 
**enabled** | **bool** | Whether the API key is enabled | [optional] 
**metadata** | **object** | Metadata for the API key | [optional] 

## Example

```python
from cashful.models.update_api_key_dto import UpdateApiKeyDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateApiKeyDto from a JSON string
update_api_key_dto_instance = UpdateApiKeyDto.from_json(json)
# print the JSON string representation of the object
print(UpdateApiKeyDto.to_json())

# convert the object into a dict
update_api_key_dto_dict = update_api_key_dto_instance.to_dict()
# create an instance of UpdateApiKeyDto from a dict
update_api_key_dto_from_dict = UpdateApiKeyDto.from_dict(update_api_key_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


