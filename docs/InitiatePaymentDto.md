# InitiatePaymentDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount** | **float** | Payment amount in the smallest currency unit (e.g., cents) | 
**currency** | **str** | Three-letter ISO 4217 currency code | 
**merchant_id** | **str** | The unique identifier of the merchant | 
**evervault_encrypted_card** | [**EvervaultEncryptedCardDto**](EvervaultEncryptedCardDto.md) | Evervault encrypted card details | 
**payment_intent_id** | **str** | Payment intent ID linked to the checkout/payment flow | 
**masked_pan** | **str** | Masked PAN for display purposes | [optional] 
**tokenize_card** | **bool** | Whether to tokenize the card for future use | [optional] [default to False]
**first_name** | **str** | Cardholder first name | [optional] 
**last_name** | **str** | Cardholder last name | [optional] 
**phone_number** | **str** | Cardholder phone number | [optional] 
**payment_description** | **str** | Payment description | [optional] 
**merchant_name** | **str** | Merchant name for display | [optional] 
**metadata** | **object** | Additional metadata | [optional] 

## Example

```python
from cashful.models.initiate_payment_dto import InitiatePaymentDto

# TODO update the JSON string below
json = "{}"
# create an instance of InitiatePaymentDto from a JSON string
initiate_payment_dto_instance = InitiatePaymentDto.from_json(json)
# print the JSON string representation of the object
print(InitiatePaymentDto.to_json())

# convert the object into a dict
initiate_payment_dto_dict = initiate_payment_dto_instance.to_dict()
# create an instance of InitiatePaymentDto from a dict
initiate_payment_dto_from_dict = InitiatePaymentDto.from_dict(initiate_payment_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


