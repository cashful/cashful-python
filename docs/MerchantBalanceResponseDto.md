# MerchantBalanceResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**merchant_id** | **str** |  | 
**amount** | **float** |  | 
**currency** | **str** |  | 
**available** | **float** |  | 
**pending** | **float** |  | 

## Example

```python
from cashful.models.merchant_balance_response_dto import MerchantBalanceResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of MerchantBalanceResponseDto from a JSON string
merchant_balance_response_dto_instance = MerchantBalanceResponseDto.from_json(json)
# print the JSON string representation of the object
print(MerchantBalanceResponseDto.to_json())

# convert the object into a dict
merchant_balance_response_dto_dict = merchant_balance_response_dto_instance.to_dict()
# create an instance of MerchantBalanceResponseDto from a dict
merchant_balance_response_dto_from_dict = MerchantBalanceResponseDto.from_dict(merchant_balance_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


