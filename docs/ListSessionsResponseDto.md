# ListSessionsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sessions** | [**List[SessionDto]**](SessionDto.md) | List of user sessions | 

## Example

```python
from cashful.models.list_sessions_response_dto import ListSessionsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListSessionsResponseDto from a JSON string
list_sessions_response_dto_instance = ListSessionsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListSessionsResponseDto.to_json())

# convert the object into a dict
list_sessions_response_dto_dict = list_sessions_response_dto_instance.to_dict()
# create an instance of ListSessionsResponseDto from a dict
list_sessions_response_dto_from_dict = ListSessionsResponseDto.from_dict(list_sessions_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


