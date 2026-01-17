# SignUpDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the user | 
**email** | **str** | The email address of the user | 
**password** | **str** | The password for the user account | 
**image** | **str** | Optional URL to the user&#39;s profile image | [optional] 
**callback_url** | **str** | Optional callback URL after successful sign-up | [optional] 
**remember_me** | **bool** | Optional flag to indicate if the user should be remembered | [optional] 

## Example

```python
from cashful.models.sign_up_dto import SignUpDto

# TODO update the JSON string below
json = "{}"
# create an instance of SignUpDto from a JSON string
sign_up_dto_instance = SignUpDto.from_json(json)
# print the JSON string representation of the object
print(SignUpDto.to_json())

# convert the object into a dict
sign_up_dto_dict = sign_up_dto_instance.to_dict()
# create an instance of SignUpDto from a dict
sign_up_dto_from_dict = SignUpDto.from_dict(sign_up_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


