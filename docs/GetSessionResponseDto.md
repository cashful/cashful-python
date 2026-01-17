# GetSessionResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**session** | [**SessionDto**](SessionDto.md) |  | 
**user** | [**SessionUserDto**](SessionUserDto.md) |  | 

## Example

```python
from cashful.models.get_session_response_dto import GetSessionResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetSessionResponseDto from a JSON string
get_session_response_dto_instance = GetSessionResponseDto.from_json(json)
# print the JSON string representation of the object
print(GetSessionResponseDto.to_json())

# convert the object into a dict
get_session_response_dto_dict = get_session_response_dto_instance.to_dict()
# create an instance of GetSessionResponseDto from a dict
get_session_response_dto_from_dict = GetSessionResponseDto.from_dict(get_session_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


