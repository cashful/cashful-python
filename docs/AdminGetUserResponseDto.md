# AdminGetUserResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | [**SessionUserDto**](SessionUserDto.md) | User details retrieved successfully | 

## Example

```python
from cashful.models.admin_get_user_response_dto import AdminGetUserResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminGetUserResponseDto from a JSON string
admin_get_user_response_dto_instance = AdminGetUserResponseDto.from_json(json)
# print the JSON string representation of the object
print(AdminGetUserResponseDto.to_json())

# convert the object into a dict
admin_get_user_response_dto_dict = admin_get_user_response_dto_instance.to_dict()
# create an instance of AdminGetUserResponseDto from a dict
admin_get_user_response_dto_from_dict = AdminGetUserResponseDto.from_dict(admin_get_user_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


