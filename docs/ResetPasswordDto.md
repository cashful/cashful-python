# ResetPasswordDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**new_password** | **str** | The new password to set | 
**token** | **str** | The token to reset password | [optional] 

## Example

```python
from cashful.models.reset_password_dto import ResetPasswordDto

# TODO update the JSON string below
json = "{}"
# create an instance of ResetPasswordDto from a JSON string
reset_password_dto_instance = ResetPasswordDto.from_json(json)
# print the JSON string representation of the object
print(ResetPasswordDto.to_json())

# convert the object into a dict
reset_password_dto_dict = reset_password_dto_instance.to_dict()
# create an instance of ResetPasswordDto from a dict
reset_password_dto_from_dict = ResetPasswordDto.from_dict(reset_password_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


