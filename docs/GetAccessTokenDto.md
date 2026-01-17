# GetAccessTokenDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to get token for | [optional] 
**force_refresh** | **bool** | Whether to force token refresh | [optional] 

## Example

```python
from cashful.models.get_access_token_dto import GetAccessTokenDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetAccessTokenDto from a JSON string
get_access_token_dto_instance = GetAccessTokenDto.from_json(json)
# print the JSON string representation of the object
print(GetAccessTokenDto.to_json())

# convert the object into a dict
get_access_token_dto_dict = get_access_token_dto_instance.to_dict()
# create an instance of GetAccessTokenDto from a dict
get_access_token_dto_from_dict = GetAccessTokenDto.from_dict(get_access_token_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


