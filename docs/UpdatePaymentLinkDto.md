# UpdatePaymentLinkDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the payment link | [optional] 
**description** | **str** | A description of the payment link | [optional] 
**active** | **bool** | Whether the payment link is active | [optional] 
**total_amount** | **float** |  | [optional] 
**success_url** | **str** | The URL to redirect to on successful payment | [optional] 
**cancel_url** | **str** | The URL to redirect to if customer cancels | [optional] 
**metadata** | **Dict[str, object]** | Optional custom metadata | 
**hosted_checkout_config** | [**HostedCheckoutConfigDto**](HostedCheckoutConfigDto.md) | Configuration for the hosted checkout page | [optional] 

## Example

```python
from cashful.models.update_payment_link_dto import UpdatePaymentLinkDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePaymentLinkDto from a JSON string
update_payment_link_dto_instance = UpdatePaymentLinkDto.from_json(json)
# print the JSON string representation of the object
print(UpdatePaymentLinkDto.to_json())

# convert the object into a dict
update_payment_link_dto_dict = update_payment_link_dto_instance.to_dict()
# create an instance of UpdatePaymentLinkDto from a dict
update_payment_link_dto_from_dict = UpdatePaymentLinkDto.from_dict(update_payment_link_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


