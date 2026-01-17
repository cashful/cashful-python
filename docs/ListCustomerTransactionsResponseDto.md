# ListCustomerTransactionsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CustomerTransactionDto]**](CustomerTransactionDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_customer_transactions_response_dto import ListCustomerTransactionsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListCustomerTransactionsResponseDto from a JSON string
list_customer_transactions_response_dto_instance = ListCustomerTransactionsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListCustomerTransactionsResponseDto.to_json())

# convert the object into a dict
list_customer_transactions_response_dto_dict = list_customer_transactions_response_dto_instance.to_dict()
# create an instance of ListCustomerTransactionsResponseDto from a dict
list_customer_transactions_response_dto_from_dict = ListCustomerTransactionsResponseDto.from_dict(list_customer_transactions_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


