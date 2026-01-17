# VerifyPhoneNumberResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Phone verified successfully | 
**user** | [**SessionUserDto**](SessionUserDto.md) | User information if verification successful | [optional] 

## Example

```python
from cashful.models.verify_phone_number_response_dto import VerifyPhoneNumberResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of VerifyPhoneNumberResponseDto from a JSON string
verify_phone_number_response_dto_instance = VerifyPhoneNumberResponseDto.from_json(json)
# print the JSON string representation of the object
print(VerifyPhoneNumberResponseDto.to_json())

# convert the object into a dict
verify_phone_number_response_dto_dict = verify_phone_number_response_dto_instance.to_dict()
# create an instance of VerifyPhoneNumberResponseDto from a dict
verify_phone_number_response_dto_from_dict = VerifyPhoneNumberResponseDto.from_dict(verify_phone_number_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


