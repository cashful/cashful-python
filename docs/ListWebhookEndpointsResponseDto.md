# ListWebhookEndpointsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[WebhookEndpointResponseDto]**](WebhookEndpointResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_webhook_endpoints_response_dto import ListWebhookEndpointsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListWebhookEndpointsResponseDto from a JSON string
list_webhook_endpoints_response_dto_instance = ListWebhookEndpointsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListWebhookEndpointsResponseDto.to_json())

# convert the object into a dict
list_webhook_endpoints_response_dto_dict = list_webhook_endpoints_response_dto_instance.to_dict()
# create an instance of ListWebhookEndpointsResponseDto from a dict
list_webhook_endpoints_response_dto_from_dict = ListWebhookEndpointsResponseDto.from_dict(list_webhook_endpoints_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


