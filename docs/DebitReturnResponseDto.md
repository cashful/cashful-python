# DebitReturnResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Payment status after 3DS authentication | 
**merchant_reference** | **str** | Merchant reference for the payment | 
**payment_intent_id** | **str** | Payment intent ID | [optional] 
**transaction_id** | **str** | Transaction ID if payment succeeded | [optional] 
**auth_code** | **str** | Authorization code from payment gateway | [optional] 
**reason** | **str** | Reason for failure if payment failed | [optional] 
**amount** | **float** | Payment amount in smallest currency unit | [optional] 
**currency** | **str** | Currency code | [optional] 

## Example

```python
from cashful.models.debit_return_response_dto import DebitReturnResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of DebitReturnResponseDto from a JSON string
debit_return_response_dto_instance = DebitReturnResponseDto.from_json(json)
# print the JSON string representation of the object
print(DebitReturnResponseDto.to_json())

# convert the object into a dict
debit_return_response_dto_dict = debit_return_response_dto_instance.to_dict()
# create an instance of DebitReturnResponseDto from a dict
debit_return_response_dto_from_dict = DebitReturnResponseDto.from_dict(debit_return_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


