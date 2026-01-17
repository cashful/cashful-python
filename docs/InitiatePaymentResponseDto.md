# InitiatePaymentResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**iveri_params** | [**IveriParamsDto**](IveriParamsDto.md) | Parameters to POST to iVeri 3DS endpoint | 
**i_veri3ds_endpoint** | **str** | iVeri 3DS endpoint URL to POST the parameters to | 

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


