# RequestPhonePasswordResetDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **str** | The phone number to send reset to | 
**callback_url** | **str** | Callback URL for password reset | [optional] 

## Example

```python
from cashful.models.request_phone_password_reset_dto import RequestPhonePasswordResetDto

# TODO update the JSON string below
json = "{}"
# create an instance of RequestPhonePasswordResetDto from a JSON string
request_phone_password_reset_dto_instance = RequestPhonePasswordResetDto.from_json(json)
# print the JSON string representation of the object
print(RequestPhonePasswordResetDto.to_json())

# convert the object into a dict
request_phone_password_reset_dto_dict = request_phone_password_reset_dto_instance.to_dict()
# create an instance of RequestPhonePasswordResetDto from a dict
request_phone_password_reset_dto_from_dict = RequestPhonePasswordResetDto.from_dict(request_phone_password_reset_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


