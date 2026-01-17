# SendPhoneOTPResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | OTP sent successfully | 

## Example

```python
from cashful.models.send_phone_otp_response_dto import SendPhoneOTPResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of SendPhoneOTPResponseDto from a JSON string
send_phone_otp_response_dto_instance = SendPhoneOTPResponseDto.from_json(json)
# print the JSON string representation of the object
print(SendPhoneOTPResponseDto.to_json())

# convert the object into a dict
send_phone_otp_response_dto_dict = send_phone_otp_response_dto_instance.to_dict()
# create an instance of SendPhoneOTPResponseDto from a dict
send_phone_otp_response_dto_from_dict = SendPhoneOTPResponseDto.from_dict(send_phone_otp_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


