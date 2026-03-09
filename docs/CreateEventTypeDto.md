# CreateEventTypeDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the event type | 
**description** | **str** | Description of the event type | [optional] 

## Example

```python
from cashful.models.create_event_type_dto import CreateEventTypeDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateEventTypeDto from a JSON string
create_event_type_dto_instance = CreateEventTypeDto.from_json(json)
# print the JSON string representation of the object
print(CreateEventTypeDto.to_json())

# convert the object into a dict
create_event_type_dto_dict = create_event_type_dto_instance.to_dict()
# create an instance of CreateEventTypeDto from a dict
create_event_type_dto_from_dict = CreateEventTypeDto.from_dict(create_event_type_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


