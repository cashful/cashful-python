# ListMerchantBalancesResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[MerchantBalanceResponseDto]**](MerchantBalanceResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_merchant_balances_response_dto import ListMerchantBalancesResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListMerchantBalancesResponseDto from a JSON string
list_merchant_balances_response_dto_instance = ListMerchantBalancesResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListMerchantBalancesResponseDto.to_json())

# convert the object into a dict
list_merchant_balances_response_dto_dict = list_merchant_balances_response_dto_instance.to_dict()
# create an instance of ListMerchantBalancesResponseDto from a dict
list_merchant_balances_response_dto_from_dict = ListMerchantBalancesResponseDto.from_dict(list_merchant_balances_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


