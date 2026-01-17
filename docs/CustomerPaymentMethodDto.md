# CustomerPaymentMethodDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**customer_id** | **str** |  | 
**type** | **str** |  | 
**brand** | **str** |  | [optional] 
**last4** | **str** |  | [optional] 
**expiry_month** | **float** |  | [optional] 
**expiry_year** | **float** |  | [optional] 
**is_default** | **bool** |  | [optional] 

## Example

```python
from cashful.models.customer_payment_method_dto import CustomerPaymentMethodDto

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerPaymentMethodDto from a JSON string
customer_payment_method_dto_instance = CustomerPaymentMethodDto.from_json(json)
# print the JSON string representation of the object
print(CustomerPaymentMethodDto.to_json())

# convert the object into a dict
customer_payment_method_dto_dict = customer_payment_method_dto_instance.to_dict()
# create an instance of CustomerPaymentMethodDto from a dict
customer_payment_method_dto_from_dict = CustomerPaymentMethodDto.from_dict(customer_payment_method_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


