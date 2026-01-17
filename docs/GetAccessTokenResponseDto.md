# GetAccessTokenResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**token** | **str** | Current access token | 
**expires_at** | **str** | Token expiration time | [optional] 

## Example

```python
from cashful.models.get_access_token_response_dto import GetAccessTokenResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetAccessTokenResponseDto from a JSON string
get_access_token_response_dto_instance = GetAccessTokenResponseDto.from_json(json)
# print the JSON string representation of the object
print(GetAccessTokenResponseDto.to_json())

# convert the object into a dict
get_access_token_response_dto_dict = get_access_token_response_dto_instance.to_dict()
# create an instance of GetAccessTokenResponseDto from a dict
get_access_token_response_dto_from_dict = GetAccessTokenResponseDto.from_dict(get_access_token_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


