# CreateWebhookEndpointDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant whose balance is being requested. If omitted, defaults to the authenticated merchant. | [optional] 
**url** | **str** | The URL where webhook events will be sent | 
**events** | **List[str]** | Array of event types to listen for | 
**metadata** | **Dict[str, object]** | Optional custom metadata | [optional] 

## Example

```python
from cashful.models.create_webhook_endpoint_dto import CreateWebhookEndpointDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateWebhookEndpointDto from a JSON string
create_webhook_endpoint_dto_instance = CreateWebhookEndpointDto.from_json(json)
# print the JSON string representation of the object
print(CreateWebhookEndpointDto.to_json())

# convert the object into a dict
create_webhook_endpoint_dto_dict = create_webhook_endpoint_dto_instance.to_dict()
# create an instance of CreateWebhookEndpointDto from a dict
create_webhook_endpoint_dto_from_dict = CreateWebhookEndpointDto.from_dict(create_webhook_endpoint_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


