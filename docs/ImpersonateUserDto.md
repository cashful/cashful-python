# ImpersonateUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user to impersonate | 

## Example

```python
from cashful.models.impersonate_user_dto import ImpersonateUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of ImpersonateUserDto from a JSON string
impersonate_user_dto_instance = ImpersonateUserDto.from_json(json)
# print the JSON string representation of the object
print(ImpersonateUserDto.to_json())

# convert the object into a dict
impersonate_user_dto_dict = impersonate_user_dto_instance.to_dict()
# create an instance of ImpersonateUserDto from a dict
impersonate_user_dto_from_dict = ImpersonateUserDto.from_dict(impersonate_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


