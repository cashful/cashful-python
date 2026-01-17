# ResetPasswordCallbackResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**token** | **str** | Password reset token | 

## Example

```python
from cashful.models.reset_password_callback_response_dto import ResetPasswordCallbackResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ResetPasswordCallbackResponseDto from a JSON string
reset_password_callback_response_dto_instance = ResetPasswordCallbackResponseDto.from_json(json)
# print the JSON string representation of the object
print(ResetPasswordCallbackResponseDto.to_json())

# convert the object into a dict
reset_password_callback_response_dto_dict = reset_password_callback_response_dto_instance.to_dict()
# create an instance of ResetPasswordCallbackResponseDto from a dict
reset_password_callback_response_dto_from_dict = ResetPasswordCallbackResponseDto.from_dict(reset_password_callback_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


