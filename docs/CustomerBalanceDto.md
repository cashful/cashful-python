# CustomerBalanceDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**customer_id** | **str** |  | 
**merchant_id** | **str** |  | [optional] 
**amount** | **float** |  | 
**currency** | **str** |  | 
**available** | **float** |  | 
**pending** | **float** |  | 

## Example

```python
from cashful.models.customer_balance_dto import CustomerBalanceDto

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerBalanceDto from a JSON string
customer_balance_dto_instance = CustomerBalanceDto.from_json(json)
# print the JSON string representation of the object
print(CustomerBalanceDto.to_json())

# convert the object into a dict
customer_balance_dto_dict = customer_balance_dto_instance.to_dict()
# create an instance of CustomerBalanceDto from a dict
customer_balance_dto_from_dict = CustomerBalanceDto.from_dict(customer_balance_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


