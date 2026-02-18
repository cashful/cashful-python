# CheckoutSessionConfirmResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**session_id** | **str** |  | 
**payment_intent_id** | **str** |  | 
**iveri_params** | **object** |  | 
**i_veri3ds_endpoint** | **str** |  | 

## Example

```python
from cashful.models.checkout_session_confirm_response_dto import CheckoutSessionConfirmResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of CheckoutSessionConfirmResponseDto from a JSON string
checkout_session_confirm_response_dto_instance = CheckoutSessionConfirmResponseDto.from_json(json)
# print the JSON string representation of the object
print(CheckoutSessionConfirmResponseDto.to_json())

# convert the object into a dict
checkout_session_confirm_response_dto_dict = checkout_session_confirm_response_dto_instance.to_dict()
# create an instance of CheckoutSessionConfirmResponseDto from a dict
checkout_session_confirm_response_dto_from_dict = CheckoutSessionConfirmResponseDto.from_dict(checkout_session_confirm_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


