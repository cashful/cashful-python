# SignInResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | [**SessionUserDto**](SessionUserDto.md) | User object | 
**token** | **str** | Session token | 
**redirect** | **float** | Whether to redirect | 
**url** | **str** | Redirect URL | [optional] 

## Example

```python
from cashful.models.sign_in_response_dto import SignInResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of SignInResponseDto from a JSON string
sign_in_response_dto_instance = SignInResponseDto.from_json(json)
# print the JSON string representation of the object
print(SignInResponseDto.to_json())

# convert the object into a dict
sign_in_response_dto_dict = sign_in_response_dto_instance.to_dict()
# create an instance of SignInResponseDto from a dict
sign_in_response_dto_from_dict = SignInResponseDto.from_dict(sign_in_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


