# SendVerificationEmailDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** | The email to send verification email to | 
**callback_url** | **str** | The URL to use for email verification callback | [optional] 

## Example

```python
from cashful.models.send_verification_email_dto import SendVerificationEmailDto

# TODO update the JSON string below
json = "{}"
# create an instance of SendVerificationEmailDto from a JSON string
send_verification_email_dto_instance = SendVerificationEmailDto.from_json(json)
# print the JSON string representation of the object
print(SendVerificationEmailDto.to_json())

# convert the object into a dict
send_verification_email_dto_dict = send_verification_email_dto_instance.to_dict()
# create an instance of SendVerificationEmailDto from a dict
send_verification_email_dto_from_dict = SendVerificationEmailDto.from_dict(send_verification_email_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


