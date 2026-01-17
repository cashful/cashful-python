# BalanceHistoryResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[BalanceTransactionDto]**](BalanceTransactionDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.balance_history_response_dto import BalanceHistoryResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of BalanceHistoryResponseDto from a JSON string
balance_history_response_dto_instance = BalanceHistoryResponseDto.from_json(json)
# print the JSON string representation of the object
print(BalanceHistoryResponseDto.to_json())

# convert the object into a dict
balance_history_response_dto_dict = balance_history_response_dto_instance.to_dict()
# create an instance of BalanceHistoryResponseDto from a dict
balance_history_response_dto_from_dict = BalanceHistoryResponseDto.from_dict(balance_history_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


