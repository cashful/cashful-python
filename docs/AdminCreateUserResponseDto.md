# AdminCreateUserResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | [**SessionUserDto**](SessionUserDto.md) | User created successfully | 

## Example

```python
from cashful.models.admin_create_user_response_dto import AdminCreateUserResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminCreateUserResponseDto from a JSON string
admin_create_user_response_dto_instance = AdminCreateUserResponseDto.from_json(json)
# print the JSON string representation of the object
print(AdminCreateUserResponseDto.to_json())

# convert the object into a dict
admin_create_user_response_dto_dict = admin_create_user_response_dto_instance.to_dict()
# create an instance of AdminCreateUserResponseDto from a dict
admin_create_user_response_dto_from_dict = AdminCreateUserResponseDto.from_dict(admin_create_user_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


