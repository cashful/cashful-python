# HostedCheckoutConfigDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | Merchant ID | [optional] 
**merchant_alias** | **str** | Merchant alias | [optional] 
**merchant_legal_name** | **str** | Merchant legal name | [optional] 
**merchant_avatar_text_placeholder** | **str** | Merchant avatar text placeholder | [optional] 
**merchant_avatar_url** | **str** | Merchant avatar URL | [optional] 
**require_contact** | **bool** | Require contact | [optional] 
**require_address** | **bool** | Require address | [optional] 
**tax_rate** | **float** | Tax rate | [optional] 
**embed_mode** | **bool** | Embed mode | [optional] 
**embed_origin** | **str** | Embed origin | [optional] 

## Example

```python
from cashful.models.hosted_checkout_config_dto import HostedCheckoutConfigDto

# TODO update the JSON string below
json = "{}"
# create an instance of HostedCheckoutConfigDto from a JSON string
hosted_checkout_config_dto_instance = HostedCheckoutConfigDto.from_json(json)
# print the JSON string representation of the object
print(HostedCheckoutConfigDto.to_json())

# convert the object into a dict
hosted_checkout_config_dto_dict = hosted_checkout_config_dto_instance.to_dict()
# create an instance of HostedCheckoutConfigDto from a dict
hosted_checkout_config_dto_from_dict = HostedCheckoutConfigDto.from_dict(hosted_checkout_config_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


