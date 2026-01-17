# ListEventsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[EventResponseDto]**](EventResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_events_response_dto import ListEventsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListEventsResponseDto from a JSON string
list_events_response_dto_instance = ListEventsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListEventsResponseDto.to_json())

# convert the object into a dict
list_events_response_dto_dict = list_events_response_dto_instance.to_dict()
# create an instance of ListEventsResponseDto from a dict
list_events_response_dto_from_dict = ListEventsResponseDto.from_dict(list_events_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


