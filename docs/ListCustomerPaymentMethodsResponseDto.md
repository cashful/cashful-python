# ListCustomerPaymentMethodsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CustomerPaymentMethodDto]**](CustomerPaymentMethodDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_customer_payment_methods_response_dto import ListCustomerPaymentMethodsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListCustomerPaymentMethodsResponseDto from a JSON string
list_customer_payment_methods_response_dto_instance = ListCustomerPaymentMethodsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListCustomerPaymentMethodsResponseDto.to_json())

# convert the object into a dict
list_customer_payment_methods_response_dto_dict = list_customer_payment_methods_response_dto_instance.to_dict()
# create an instance of ListCustomerPaymentMethodsResponseDto from a dict
list_customer_payment_methods_response_dto_from_dict = ListCustomerPaymentMethodsResponseDto.from_dict(list_customer_payment_methods_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


