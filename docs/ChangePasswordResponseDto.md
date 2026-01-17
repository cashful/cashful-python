# ChangePasswordResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**token** | **str** | New session token if other sessions were revoked | [optional] 
**user** | [**SessionUserDto**](SessionUserDto.md) | User object | 

## Example

```python
from cashful.models.change_password_response_dto import ChangePasswordResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ChangePasswordResponseDto from a JSON string
change_password_response_dto_instance = ChangePasswordResponseDto.from_json(json)
# print the JSON string representation of the object
print(ChangePasswordResponseDto.to_json())

# convert the object into a dict
change_password_response_dto_dict = change_password_response_dto_instance.to_dict()
# create an instance of ChangePasswordResponseDto from a dict
change_password_response_dto_from_dict = ChangePasswordResponseDto.from_dict(change_password_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


