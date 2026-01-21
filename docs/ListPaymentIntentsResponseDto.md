# ListPaymentIntentsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PaymentIntentResponseDto]**](PaymentIntentResponseDto.md) | List of payment intents | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) | Pagination metadata | 

## Example

```python
from cashful.models.list_payment_intents_response_dto import ListPaymentIntentsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListPaymentIntentsResponseDto from a JSON string
list_payment_intents_response_dto_instance = ListPaymentIntentsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListPaymentIntentsResponseDto.to_json())

# convert the object into a dict
list_payment_intents_response_dto_dict = list_payment_intents_response_dto_instance.to_dict()
# create an instance of ListPaymentIntentsResponseDto from a dict
list_payment_intents_response_dto_from_dict = ListPaymentIntentsResponseDto.from_dict(list_payment_intents_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


