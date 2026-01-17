# CustomerTransactionDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**customer_id** | **str** |  | [optional] 
**merchant_id** | **str** |  | [optional] 
**type** | **str** |  | 
**amount** | **float** |  | 
**currency** | **str** |  | 
**description** | **str** |  | [optional] 
**related_entity_id** | **str** |  | [optional] 
**related_entity_type** | **str** |  | [optional] 
**balance_after** | **float** |  | [optional] 

## Example

```python
from cashful.models.customer_transaction_dto import CustomerTransactionDto

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerTransactionDto from a JSON string
customer_transaction_dto_instance = CustomerTransactionDto.from_json(json)
# print the JSON string representation of the object
print(CustomerTransactionDto.to_json())

# convert the object into a dict
customer_transaction_dto_dict = customer_transaction_dto_instance.to_dict()
# create an instance of CustomerTransactionDto from a dict
customer_transaction_dto_from_dict = CustomerTransactionDto.from_dict(customer_transaction_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


