# CheckoutSessionResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**merchant_id** | **str** |  | 
**payment_intent_id** | **str** |  | [optional] 
**customer_id** | **str** |  | [optional] 
**session_url** | **str** |  | 
**success_url** | **str** |  | 
**cancel_url** | **str** |  | 
**line_items** | [**List[LineItemDto]**](LineItemDto.md) |  | [optional] 
**total_amount** | **float** |  | [optional] 
**currency** | **str** |  | 
**mode** | **str** |  | [optional] 
**status** | **str** |  | 
**expires_at** | **datetime** |  | [optional] 
**metadata** | **Dict[str, object]** |  | 
**hosted_checkout_config** | [**HostedCheckoutConfigDto**](HostedCheckoutConfigDto.md) | Configuration for the hosted checkout page | [optional] 

## Example

```python
from cashful.models.checkout_session_response_dto import CheckoutSessionResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of CheckoutSessionResponseDto from a JSON string
checkout_session_response_dto_instance = CheckoutSessionResponseDto.from_json(json)
# print the JSON string representation of the object
print(CheckoutSessionResponseDto.to_json())

# convert the object into a dict
checkout_session_response_dto_dict = checkout_session_response_dto_instance.to_dict()
# create an instance of CheckoutSessionResponseDto from a dict
checkout_session_response_dto_from_dict = CheckoutSessionResponseDto.from_dict(checkout_session_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


