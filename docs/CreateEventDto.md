# CreateEventDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | Merchant ID associated with the event | 
**type** | **str** | Event type identifier (e.g., &#39;checkout.loaded&#39;) | 
**data** | **object** | Event payload data | 
**related_entity_id** | **str** | ID of the related entity | [optional] 
**related_entity_type** | **str** | Type of the related entity | [optional] 

## Example

```python
from cashful.models.create_event_dto import CreateEventDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateEventDto from a JSON string
create_event_dto_instance = CreateEventDto.from_json(json)
# print the JSON string representation of the object
print(CreateEventDto.to_json())

# convert the object into a dict
create_event_dto_dict = create_event_dto_instance.to_dict()
# create an instance of CreateEventDto from a dict
create_event_dto_from_dict = CreateEventDto.from_dict(create_event_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


