# PaymentLinkResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**name** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**merchant_id** | **str** |  | 
**url** | **str** |  | 
**line_items** | [**List[LineItemDto]**](LineItemDto.md) |  | [optional] 
**customer_id** | **str** |  | [optional] 
**total_amount** | **float** |  | 
**currency** | **str** |  | 
**mode** | **str** |  | 
**active** | **bool** |  | 
**success_url** | **str** |  | 
**cancel_url** | **str** |  | 
**metadata** | **Dict[str, object]** |  | 
**hosted_checkout_config** | [**HostedCheckoutConfigDto**](HostedCheckoutConfigDto.md) | Configuration for the hosted checkout page | [optional] 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 

## Example

```python
from cashful.models.payment_link_response_dto import PaymentLinkResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of PaymentLinkResponseDto from a JSON string
payment_link_response_dto_instance = PaymentLinkResponseDto.from_json(json)
# print the JSON string representation of the object
print(PaymentLinkResponseDto.to_json())

# convert the object into a dict
payment_link_response_dto_dict = payment_link_response_dto_instance.to_dict()
# create an instance of PaymentLinkResponseDto from a dict
payment_link_response_dto_from_dict = PaymentLinkResponseDto.from_dict(payment_link_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


