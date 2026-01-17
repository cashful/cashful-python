# ResetPhonePasswordResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Password reset successfully | 

## Example

```python
from cashful.models.reset_phone_password_response_dto import ResetPhonePasswordResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ResetPhonePasswordResponseDto from a JSON string
reset_phone_password_response_dto_instance = ResetPhonePasswordResponseDto.from_json(json)
# print the JSON string representation of the object
print(ResetPhonePasswordResponseDto.to_json())

# convert the object into a dict
reset_phone_password_response_dto_dict = reset_phone_password_response_dto_instance.to_dict()
# create an instance of ResetPhonePasswordResponseDto from a dict
reset_phone_password_response_dto_from_dict = ResetPhonePasswordResponseDto.from_dict(reset_phone_password_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


