# EvervaultEncryptedCardDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pan** | **str** | Encrypted Primary Account Number (PAN) | 
**expiry_date** | **str** | Encrypted card expiry date | 
**card_security_code** | **str** | Encrypted card security code (CVV) | 
**cardholder_name** | **str** | Encrypted cardholder name | [optional] 

## Example

```python
from cashful.models.evervault_encrypted_card_dto import EvervaultEncryptedCardDto

# TODO update the JSON string below
json = "{}"
# create an instance of EvervaultEncryptedCardDto from a JSON string
evervault_encrypted_card_dto_instance = EvervaultEncryptedCardDto.from_json(json)
# print the JSON string representation of the object
print(EvervaultEncryptedCardDto.to_json())

# convert the object into a dict
evervault_encrypted_card_dto_dict = evervault_encrypted_card_dto_instance.to_dict()
# create an instance of EvervaultEncryptedCardDto from a dict
evervault_encrypted_card_dto_from_dict = EvervaultEncryptedCardDto.from_dict(evervault_encrypted_card_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


