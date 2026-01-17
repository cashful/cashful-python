# RefreshTokenResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**token** | **str** | New access token | 
**refresh_token** | **str** | New refresh token | [optional] 
**user** | [**SessionUserDto**](SessionUserDto.md) | User information | 

## Example

```python
from cashful.models.refresh_token_response_dto import RefreshTokenResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of RefreshTokenResponseDto from a JSON string
refresh_token_response_dto_instance = RefreshTokenResponseDto.from_json(json)
# print the JSON string representation of the object
print(RefreshTokenResponseDto.to_json())

# convert the object into a dict
refresh_token_response_dto_dict = refresh_token_response_dto_instance.to_dict()
# create an instance of RefreshTokenResponseDto from a dict
refresh_token_response_dto_from_dict = RefreshTokenResponseDto.from_dict(refresh_token_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


