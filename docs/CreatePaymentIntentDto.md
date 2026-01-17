# CreatePaymentIntentDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant whose balance is being requested. If omitted, defaults to the authenticated merchant. | [optional] 
**customer_id** | **str** | The unique identifier of the customer. Optional for payment intents that don&#39;t require a customer. | [optional] 
**payment_method_id** | **str** | The unique identifier of the payment method. Optional if payment method will be collected later. | [optional] 
**amount** | **float** | The amount to charge in the smallest currency unit (cents) | 
**currency** | **str** | The three-letter ISO 4217 currency code | 
**mode** | **str** | The mode of the payment intent | [optional] [default to 'payment']
**description** | **str** | Optional description for the payment | [optional] 
**metadata** | **Dict[str, object]** | Optional custom metadata | [optional] 
**idempotency_key** | **str** | A unique key to prevent duplicate charges. If not provided, one will be generated. | [optional] 
**expires_at** | **datetime** | When the payment intent expires. Defaults to 24 hours from creation. | [optional] 

## Example

```python
from cashful.models.create_payment_intent_dto import CreatePaymentIntentDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePaymentIntentDto from a JSON string
create_payment_intent_dto_instance = CreatePaymentIntentDto.from_json(json)
# print the JSON string representation of the object
print(CreatePaymentIntentDto.to_json())

# convert the object into a dict
create_payment_intent_dto_dict = create_payment_intent_dto_instance.to_dict()
# create an instance of CreatePaymentIntentDto from a dict
create_payment_intent_dto_from_dict = CreatePaymentIntentDto.from_dict(create_payment_intent_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


