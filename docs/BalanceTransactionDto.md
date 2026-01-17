# BalanceTransactionDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**merchant_id** | **str** |  | [optional] 
**type** | **str** |  | 
**amount** | **float** |  | 
**currency** | **str** |  | 
**description** | **str** |  | 
**related_entity_id** | **str** |  | [optional] 
**related_entity_type** | **str** |  | [optional] 
**balance_after** | **float** |  | [optional] 

## Example

```python
from cashful.models.balance_transaction_dto import BalanceTransactionDto

# TODO update the JSON string below
json = "{}"
# create an instance of BalanceTransactionDto from a JSON string
balance_transaction_dto_instance = BalanceTransactionDto.from_json(json)
# print the JSON string representation of the object
print(BalanceTransactionDto.to_json())

# convert the object into a dict
balance_transaction_dto_dict = balance_transaction_dto_instance.to_dict()
# create an instance of BalanceTransactionDto from a dict
balance_transaction_dto_from_dict = BalanceTransactionDto.from_dict(balance_transaction_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


