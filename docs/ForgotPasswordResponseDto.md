# ForgotPasswordResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Password reset email sent | 

## Example

```python
from cashful.models.forgot_password_response_dto import ForgotPasswordResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ForgotPasswordResponseDto from a JSON string
forgot_password_response_dto_instance = ForgotPasswordResponseDto.from_json(json)
# print the JSON string representation of the object
print(ForgotPasswordResponseDto.to_json())

# convert the object into a dict
forgot_password_response_dto_dict = forgot_password_response_dto_instance.to_dict()
# create an instance of ForgotPasswordResponseDto from a dict
forgot_password_response_dto_from_dict = ForgotPasswordResponseDto.from_dict(forgot_password_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


