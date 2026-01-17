# EventResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the event | 
**merchant_id** | **str** | ID of the merchant this event belongs to | 
**webhook_endpoint_id** | **str** | ID of the webhook endpoint this event was sent to | 
**type** | **str** | Event type name | 
**data** | **object** | Event data payload | 
**status** | **str** | Current delivery status of the event | 
**attempts** | **float** | Number of delivery attempts | 
**related_entity_id** | **str** | ID of the related entity | [optional] 
**related_entity_type** | **str** | Type of the related entity | [optional] 
**last_attempt_at** | **datetime** | Timestamp of the last delivery attempt | [optional] 
**next_retry_at** | **datetime** | Timestamp for the next retry attempt | [optional] 
**delivered_at** | **datetime** | Timestamp when the event was successfully delivered | [optional] 
**created_at** | **datetime** | Timestamp when the event was created | 
**updated_at** | **datetime** | Timestamp when the event was last updated | 

## Example

```python
from cashful.models.event_response_dto import EventResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of EventResponseDto from a JSON string
event_response_dto_instance = EventResponseDto.from_json(json)
# print the JSON string representation of the object
print(EventResponseDto.to_json())

# convert the object into a dict
event_response_dto_dict = event_response_dto_instance.to_dict()
# create an instance of EventResponseDto from a dict
event_response_dto_from_dict = EventResponseDto.from_dict(event_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


