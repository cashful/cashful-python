# WebhookEndpointResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the webhook endpoint | 
**merchant_id** | **str** | The merchant ID this webhook belongs to | 
**url** | **str** | The URL where webhook events are sent | 
**events** | **List[str]** | Array of event types subscribed to | 
**active** | **bool** | Whether the webhook endpoint is active | 
**metadata** | **Dict[str, object]** | Custom metadata attached to the webhook endpoint | [optional] 
**created_at** | **datetime** | When the webhook endpoint was created | 
**updated_at** | **datetime** | When the webhook endpoint was last updated | 
**deleted_at** | **datetime** | When the webhook endpoint was deleted (soft delete) | [optional] 

## Example

```python
from cashful.models.webhook_endpoint_response_dto import WebhookEndpointResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of WebhookEndpointResponseDto from a JSON string
webhook_endpoint_response_dto_instance = WebhookEndpointResponseDto.from_json(json)
# print the JSON string representation of the object
print(WebhookEndpointResponseDto.to_json())

# convert the object into a dict
webhook_endpoint_response_dto_dict = webhook_endpoint_response_dto_instance.to_dict()
# create an instance of WebhookEndpointResponseDto from a dict
webhook_endpoint_response_dto_from_dict = WebhookEndpointResponseDto.from_dict(webhook_endpoint_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


