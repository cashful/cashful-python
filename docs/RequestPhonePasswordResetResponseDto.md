# RequestPhonePasswordResetResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Password reset requested successfully | 

## Example

```python
from cashful.models.request_phone_password_reset_response_dto import RequestPhonePasswordResetResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of RequestPhonePasswordResetResponseDto from a JSON string
request_phone_password_reset_response_dto_instance = RequestPhonePasswordResetResponseDto.from_json(json)
# print the JSON string representation of the object
print(RequestPhonePasswordResetResponseDto.to_json())

# convert the object into a dict
request_phone_password_reset_response_dto_dict = request_phone_password_reset_response_dto_instance.to_dict()
# create an instance of RequestPhonePasswordResetResponseDto from a dict
request_phone_password_reset_response_dto_from_dict = RequestPhonePasswordResetResponseDto.from_dict(request_phone_password_reset_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


