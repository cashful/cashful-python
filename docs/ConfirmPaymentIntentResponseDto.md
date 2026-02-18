# ConfirmPaymentIntentResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**payment_intent** | [**PaymentIntentResponseDto**](PaymentIntentResponseDto.md) |  | 
**iveri_params** | **object** |  | 
**i_veri3ds_endpoint** | **str** |  | 

## Example

```python
from cashful.models.confirm_payment_intent_response_dto import ConfirmPaymentIntentResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ConfirmPaymentIntentResponseDto from a JSON string
confirm_payment_intent_response_dto_instance = ConfirmPaymentIntentResponseDto.from_json(json)
# print the JSON string representation of the object
print(ConfirmPaymentIntentResponseDto.to_json())

# convert the object into a dict
confirm_payment_intent_response_dto_dict = confirm_payment_intent_response_dto_instance.to_dict()
# create an instance of ConfirmPaymentIntentResponseDto from a dict
confirm_payment_intent_response_dto_from_dict = ConfirmPaymentIntentResponseDto.from_dict(confirm_payment_intent_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


