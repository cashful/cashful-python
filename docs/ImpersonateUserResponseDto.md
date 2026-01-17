# ImpersonateUserResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | User impersonated successfully | 

## Example

```python
from cashful.models.impersonate_user_response_dto import ImpersonateUserResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ImpersonateUserResponseDto from a JSON string
impersonate_user_response_dto_instance = ImpersonateUserResponseDto.from_json(json)
# print the JSON string representation of the object
print(ImpersonateUserResponseDto.to_json())

# convert the object into a dict
impersonate_user_response_dto_dict = impersonate_user_response_dto_instance.to_dict()
# create an instance of ImpersonateUserResponseDto from a dict
impersonate_user_response_dto_from_dict = ImpersonateUserResponseDto.from_dict(impersonate_user_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


