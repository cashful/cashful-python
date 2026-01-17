# AdminRemoveUserResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | User removed successfully | 

## Example

```python
from cashful.models.admin_remove_user_response_dto import AdminRemoveUserResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of AdminRemoveUserResponseDto from a JSON string
admin_remove_user_response_dto_instance = AdminRemoveUserResponseDto.from_json(json)
# print the JSON string representation of the object
print(AdminRemoveUserResponseDto.to_json())

# convert the object into a dict
admin_remove_user_response_dto_dict = admin_remove_user_response_dto_instance.to_dict()
# create an instance of AdminRemoveUserResponseDto from a dict
admin_remove_user_response_dto_from_dict = AdminRemoveUserResponseDto.from_dict(admin_remove_user_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


