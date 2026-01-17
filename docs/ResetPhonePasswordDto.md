# ResetPhonePasswordDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **str** | The phone number | 
**code** | **str** | The OTP code received | 
**new_password** | **str** | The new password | 

## Example

```python
from cashful.models.reset_phone_password_dto import ResetPhonePasswordDto

# TODO update the JSON string below
json = "{}"
# create an instance of ResetPhonePasswordDto from a JSON string
reset_phone_password_dto_instance = ResetPhonePasswordDto.from_json(json)
# print the JSON string representation of the object
print(ResetPhonePasswordDto.to_json())

# convert the object into a dict
reset_phone_password_dto_dict = reset_phone_password_dto_instance.to_dict()
# create an instance of ResetPhonePasswordDto from a dict
reset_phone_password_dto_from_dict = ResetPhonePasswordDto.from_dict(reset_phone_password_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


