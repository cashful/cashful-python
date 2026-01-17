# PurchaseResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**merchant_id** | **str** |  | 
**customer_id** | **str** |  | 
**product_id** | **str** |  | [optional] 
**amount** | **float** |  | 
**currency** | **str** |  | 
**status** | **str** |  | 
**customer_balance_before** | **float** |  | [optional] 
**customer_balance_after** | **float** |  | [optional] 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 

## Example

```python
from cashful.models.purchase_response_dto import PurchaseResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of PurchaseResponseDto from a JSON string
purchase_response_dto_instance = PurchaseResponseDto.from_json(json)
# print the JSON string representation of the object
print(PurchaseResponseDto.to_json())

# convert the object into a dict
purchase_response_dto_dict = purchase_response_dto_instance.to_dict()
# create an instance of PurchaseResponseDto from a dict
purchase_response_dto_from_dict = PurchaseResponseDto.from_dict(purchase_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


