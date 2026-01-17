# ListPaymentMethodsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PaymentMethodResponseDto]**](PaymentMethodResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_payment_methods_response_dto import ListPaymentMethodsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListPaymentMethodsResponseDto from a JSON string
list_payment_methods_response_dto_instance = ListPaymentMethodsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListPaymentMethodsResponseDto.to_json())

# convert the object into a dict
list_payment_methods_response_dto_dict = list_payment_methods_response_dto_instance.to_dict()
# create an instance of ListPaymentMethodsResponseDto from a dict
list_payment_methods_response_dto_from_dict = ListPaymentMethodsResponseDto.from_dict(list_payment_methods_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


