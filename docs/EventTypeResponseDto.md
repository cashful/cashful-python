# EventTypeResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the event type | 
**name** | **str** | Name of the event type | 
**description** | **str** | Description of the event type | [optional] 
**is_active** | **bool** | Whether the event type is active | 

## Example

```python
from cashful.models.event_type_response_dto import EventTypeResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of EventTypeResponseDto from a JSON string
event_type_response_dto_instance = EventTypeResponseDto.from_json(json)
# print the JSON string representation of the object
print(EventTypeResponseDto.to_json())

# convert the object into a dict
event_type_response_dto_dict = event_type_response_dto_instance.to_dict()
# create an instance of EventTypeResponseDto from a dict
event_type_response_dto_from_dict = EventTypeResponseDto.from_dict(event_type_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


