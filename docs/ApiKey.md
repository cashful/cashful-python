# ApiKey


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**name** | **str** |  | 
**prefix** | **str** |  | 
**user_id** | **str** |  | 
**enabled** | **bool** |  | 
**rate_limit_enabled** | **bool** |  | 
**rate_limit_time_window** | **float** |  | 
**rate_limit_max** | **float** |  | 
**request_count** | **float** |  | 
**remaining** | **float** |  | 
**last_request** | **datetime** |  | [optional] 
**expires_at** | **datetime** |  | [optional] 
**metadata** | **object** |  | [optional] 
**permissions** | **str** |  | [optional] 

## Example

```python
from cashful.models.api_key import ApiKey

# TODO update the JSON string below
json = "{}"
# create an instance of ApiKey from a JSON string
api_key_instance = ApiKey.from_json(json)
# print the JSON string representation of the object
print(ApiKey.to_json())

# convert the object into a dict
api_key_dict = api_key_instance.to_dict()
# create an instance of ApiKey from a dict
api_key_from_dict = ApiKey.from_dict(api_key_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


