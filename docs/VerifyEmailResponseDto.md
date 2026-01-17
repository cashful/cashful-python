# VerifyEmailResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | [**SessionUserDto**](SessionUserDto.md) | User object | 
**status** | **bool** | Indicates if email was verified successfully | 

## Example

```python
from cashful.models.verify_email_response_dto import VerifyEmailResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of VerifyEmailResponseDto from a JSON string
verify_email_response_dto_instance = VerifyEmailResponseDto.from_json(json)
# print the JSON string representation of the object
print(VerifyEmailResponseDto.to_json())

# convert the object into a dict
verify_email_response_dto_dict = verify_email_response_dto_instance.to_dict()
# create an instance of VerifyEmailResponseDto from a dict
verify_email_response_dto_from_dict = VerifyEmailResponseDto.from_dict(verify_email_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


