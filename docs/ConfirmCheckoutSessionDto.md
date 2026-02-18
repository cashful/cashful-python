# ConfirmCheckoutSessionDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**evervault_encrypted_card** | [**EvervaultEncryptedCardDto**](EvervaultEncryptedCardDto.md) | Evervault encrypted card details | 
**masked_pan** | **str** | Masked PAN for display purposes | [optional] 
**tokenize_card** | **bool** | Whether to tokenize the card for future use | [optional] [default to False]
**first_name** | **str** | Cardholder first name | [optional] 
**last_name** | **str** | Cardholder last name | [optional] 
**phone_number** | **str** | Cardholder phone number | [optional] 
**payment_description** | **str** | Payment description | [optional] 
**merchant_name** | **str** | Merchant name for display | [optional] 
**metadata** | **Dict[str, object]** | Additional metadata | [optional] 

## Example

```python
from cashful.models.confirm_checkout_session_dto import ConfirmCheckoutSessionDto

# TODO update the JSON string below
json = "{}"
# create an instance of ConfirmCheckoutSessionDto from a JSON string
confirm_checkout_session_dto_instance = ConfirmCheckoutSessionDto.from_json(json)
# print the JSON string representation of the object
print(ConfirmCheckoutSessionDto.to_json())

# convert the object into a dict
confirm_checkout_session_dto_dict = confirm_checkout_session_dto_instance.to_dict()
# create an instance of ConfirmCheckoutSessionDto from a dict
confirm_checkout_session_dto_from_dict = ConfirmCheckoutSessionDto.from_dict(confirm_checkout_session_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


