# SignUpResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**token** | **str** | Authentication token for the session | [optional] 
**user** | [**SessionUserDto**](SessionUserDto.md) | User object created successfully | 

## Example

```python
from cashful.models.sign_up_response_dto import SignUpResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of SignUpResponseDto from a JSON string
sign_up_response_dto_instance = SignUpResponseDto.from_json(json)
# print the JSON string representation of the object
print(SignUpResponseDto.to_json())

# convert the object into a dict
sign_up_response_dto_dict = sign_up_response_dto_instance.to_dict()
# create an instance of SignUpResponseDto from a dict
sign_up_response_dto_from_dict = SignUpResponseDto.from_dict(sign_up_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


