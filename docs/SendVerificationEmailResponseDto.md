# SendVerificationEmailResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **bool** | Indicates if email was sent successfully | 

## Example

```python
from cashful.models.send_verification_email_response_dto import SendVerificationEmailResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of SendVerificationEmailResponseDto from a JSON string
send_verification_email_response_dto_instance = SendVerificationEmailResponseDto.from_json(json)
# print the JSON string representation of the object
print(SendVerificationEmailResponseDto.to_json())

# convert the object into a dict
send_verification_email_response_dto_dict = send_verification_email_response_dto_instance.to_dict()
# create an instance of SendVerificationEmailResponseDto from a dict
send_verification_email_response_dto_from_dict = SendVerificationEmailResponseDto.from_dict(send_verification_email_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


