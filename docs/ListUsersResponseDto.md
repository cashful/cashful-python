# ListUsersResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**users** | **List[object]** | List of users | 

## Example

```python
from cashful.models.list_users_response_dto import ListUsersResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListUsersResponseDto from a JSON string
list_users_response_dto_instance = ListUsersResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListUsersResponseDto.to_json())

# convert the object into a dict
list_users_response_dto_dict = list_users_response_dto_instance.to_dict()
# create an instance of ListUsersResponseDto from a dict
list_users_response_dto_from_dict = ListUsersResponseDto.from_dict(list_users_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


