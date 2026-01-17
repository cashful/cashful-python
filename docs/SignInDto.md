# SignInDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** | The email address of the user | 
**password** | **str** | The password for the user account | 
**callback_url** | **str** | The URL to use for email verification callback | [optional] 
**remember_me** | **bool** | If this is false, the session will not be remembered. Default is &#x60;true&#x60;. | [optional] 

## Example

```python
from cashful.models.sign_in_dto import SignInDto

# TODO update the JSON string below
json = "{}"
# create an instance of SignInDto from a JSON string
sign_in_dto_instance = SignInDto.from_json(json)
# print the JSON string representation of the object
print(SignInDto.to_json())

# convert the object into a dict
sign_in_dto_dict = sign_in_dto_instance.to_dict()
# create an instance of SignInDto from a dict
sign_in_dto_from_dict = SignInDto.from_dict(sign_in_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


