# SignInPhoneNumberDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **str** | The phone number | 
**password** | **str** | The password for the account | 
**callback_url** | **str** | Callback URL after sign in | [optional] 

## Example

```python
from cashful.models.sign_in_phone_number_dto import SignInPhoneNumberDto

# TODO update the JSON string below
json = "{}"
# create an instance of SignInPhoneNumberDto from a JSON string
sign_in_phone_number_dto_instance = SignInPhoneNumberDto.from_json(json)
# print the JSON string representation of the object
print(SignInPhoneNumberDto.to_json())

# convert the object into a dict
sign_in_phone_number_dto_dict = sign_in_phone_number_dto_instance.to_dict()
# create an instance of SignInPhoneNumberDto from a dict
sign_in_phone_number_dto_from_dict = SignInPhoneNumberDto.from_dict(sign_in_phone_number_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


