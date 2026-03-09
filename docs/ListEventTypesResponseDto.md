# ListEventTypesResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[EventTypeResponseDto]**](EventTypeResponseDto.md) |  | 

## Example

```python
from cashful.models.list_event_types_response_dto import ListEventTypesResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListEventTypesResponseDto from a JSON string
list_event_types_response_dto_instance = ListEventTypesResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListEventTypesResponseDto.to_json())

# convert the object into a dict
list_event_types_response_dto_dict = list_event_types_response_dto_instance.to_dict()
# create an instance of ListEventTypesResponseDto from a dict
list_event_types_response_dto_from_dict = ListEventTypesResponseDto.from_dict(list_event_types_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


