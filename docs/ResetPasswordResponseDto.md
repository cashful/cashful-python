# ResetPasswordResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Password reset successfully | 

## Example

```python
from cashful.models.reset_password_response_dto import ResetPasswordResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ResetPasswordResponseDto from a JSON string
reset_password_response_dto_instance = ResetPasswordResponseDto.from_json(json)
# print the JSON string representation of the object
print(ResetPasswordResponseDto.to_json())

# convert the object into a dict
reset_password_response_dto_dict = reset_password_response_dto_instance.to_dict()
# create an instance of ResetPasswordResponseDto from a dict
reset_password_response_dto_from_dict = ResetPasswordResponseDto.from_dict(reset_password_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


