# RefreshTokenDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**refresh_token** | **str** | The refresh token | 
**rotate** | **bool** | Whether to rotate the token | [optional] 

## Example

```python
from cashful.models.refresh_token_dto import RefreshTokenDto

# TODO update the JSON string below
json = "{}"
# create an instance of RefreshTokenDto from a JSON string
refresh_token_dto_instance = RefreshTokenDto.from_json(json)
# print the JSON string representation of the object
print(RefreshTokenDto.to_json())

# convert the object into a dict
refresh_token_dto_dict = refresh_token_dto_instance.to_dict()
# create an instance of RefreshTokenDto from a dict
refresh_token_dto_from_dict = RefreshTokenDto.from_dict(refresh_token_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


