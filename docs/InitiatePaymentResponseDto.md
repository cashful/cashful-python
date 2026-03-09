# InitiatePaymentResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**iveri_params** | [**IveriParamsDto**](IveriParamsDto.md) | Parameters to POST to iVeri 3DS endpoint (only in live mode) | [optional] 
**i_veri3ds_endpoint** | **str** | iVeri 3DS endpoint URL to POST the parameters to (only in live mode) | [optional] 
**sandbox_mode** | **bool** | Whether sandbox mode is active | [optional] 
**status** | **str** | Payment status (only in sandbox mode) | [optional] 
**payment_intent_id** | **str** | Payment intent ID | [optional] 
**transaction_id** | **str** | Transaction ID (only in sandbox mode on success) | [optional] 
**auth_code** | **str** | Authorization code (only in sandbox mode on success) | [optional] 
**amount** | **float** | Payment amount in smallest currency unit | [optional] 
**currency** | **str** | Currency code | [optional] 
**reason** | **str** | Reason for failure (only in sandbox mode on failure) | [optional] 

## Example

```python
from cashful.models.initiate_payment_response_dto import InitiatePaymentResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of InitiatePaymentResponseDto from a JSON string
initiate_payment_response_dto_instance = InitiatePaymentResponseDto.from_json(json)
# print the JSON string representation of the object
print(InitiatePaymentResponseDto.to_json())

# convert the object into a dict
initiate_payment_response_dto_dict = initiate_payment_response_dto_instance.to_dict()
# create an instance of InitiatePaymentResponseDto from a dict
initiate_payment_response_dto_from_dict = InitiatePaymentResponseDto.from_dict(initiate_payment_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


