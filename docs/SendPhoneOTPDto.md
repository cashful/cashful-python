# SendPhoneOTPDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **str** | The phone number to send OTP to | 

## Example

```python
from cashful.models.send_phone_otp_dto import SendPhoneOTPDto

# TODO update the JSON string below
json = "{}"
# create an instance of SendPhoneOTPDto from a JSON string
send_phone_otp_dto_instance = SendPhoneOTPDto.from_json(json)
# print the JSON string representation of the object
print(SendPhoneOTPDto.to_json())

# convert the object into a dict
send_phone_otp_dto_dict = send_phone_otp_dto_instance.to_dict()
# create an instance of SendPhoneOTPDto from a dict
send_phone_otp_dto_from_dict = SendPhoneOTPDto.from_dict(send_phone_otp_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


