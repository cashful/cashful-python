# VerifyPhoneNumberDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **str** | The phone number to verify | 
**code** | **str** | The OTP code received | 

## Example

```python
from cashful.models.verify_phone_number_dto import VerifyPhoneNumberDto

# TODO update the JSON string below
json = "{}"
# create an instance of VerifyPhoneNumberDto from a JSON string
verify_phone_number_dto_instance = VerifyPhoneNumberDto.from_json(json)
# print the JSON string representation of the object
print(VerifyPhoneNumberDto.to_json())

# convert the object into a dict
verify_phone_number_dto_dict = verify_phone_number_dto_instance.to_dict()
# create an instance of VerifyPhoneNumberDto from a dict
verify_phone_number_dto_from_dict = VerifyPhoneNumberDto.from_dict(verify_phone_number_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


