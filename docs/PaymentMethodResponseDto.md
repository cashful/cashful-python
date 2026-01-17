# PaymentMethodResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique payment method identifier | 
**customer_id** | **str** | Customer ID this payment method belongs to | 
**type** | **str** | Payment method type (e.g., card, mobile_money) | 
**provider** | **str** | Payment provider name (e.g., iveri, mpesa) | 
**brand** | **str** | Card brand (e.g., Visa, Mastercard) | [optional] 
**last4** | **str** | Last 4 digits of card number | [optional] 
**expiry_month** | **float** | Card expiry month (1-12) | [optional] 
**expiry_year** | **float** | Card expiry year | [optional] 
**phone_number** | **str** | Phone number for mobile money | [optional] 
**is_default** | **bool** | Whether this is the default payment method | 
**created_at** | **datetime** | When the payment method was created | 
**updated_at** | **datetime** | When the payment method was last updated | 

## Example

```python
from cashful.models.payment_method_response_dto import PaymentMethodResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of PaymentMethodResponseDto from a JSON string
payment_method_response_dto_instance = PaymentMethodResponseDto.from_json(json)
# print the JSON string representation of the object
print(PaymentMethodResponseDto.to_json())

# convert the object into a dict
payment_method_response_dto_dict = payment_method_response_dto_instance.to_dict()
# create an instance of PaymentMethodResponseDto from a dict
payment_method_response_dto_from_dict = PaymentMethodResponseDto.from_dict(payment_method_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


