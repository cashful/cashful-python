# PaymentIntentResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique payment intent ID | 
**merchant_id** | **str** | Merchant ID | 
**customer_id** | **str** | Customer ID (if associated) | 
**payment_method_id** | **str** | Payment method ID (if attached) | 
**amount** | **float** | Amount in smallest currency unit | 
**currency** | **str** | Three-letter currency code | 
**status** | **str** | Current status of the payment intent | 
**mode** | **str** | Mode of the payment intent | 
**description** | **str** | Description | [optional] 
**metadata** | **Dict[str, object]** | Custom metadata | [optional] 
**idempotency_key** | **str** | Unique idempotency key for this payment intent | 
**expires_at** | **datetime** | When the payment intent expires | 
**created_at** | **datetime** | Creation timestamp | 
**updated_at** | **datetime** | Last update timestamp | 
**deleted_at** | **datetime** | Deletion timestamp (for soft deletes) | [optional] 

## Example

```python
from cashful.models.payment_intent_response_dto import PaymentIntentResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of PaymentIntentResponseDto from a JSON string
payment_intent_response_dto_instance = PaymentIntentResponseDto.from_json(json)
# print the JSON string representation of the object
print(PaymentIntentResponseDto.to_json())

# convert the object into a dict
payment_intent_response_dto_dict = payment_intent_response_dto_instance.to_dict()
# create an instance of PaymentIntentResponseDto from a dict
payment_intent_response_dto_from_dict = PaymentIntentResponseDto.from_dict(payment_intent_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


