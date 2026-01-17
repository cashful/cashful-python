# CreatePaymentMethodDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **str** |  | 
**type** | **str** |  | 
**is_default** | **bool** |  | [optional] 
**card_number** | **str** |  | [optional] 
**brand** | **str** |  | [optional] 
**last4** | **str** |  | [optional] 
**expiry_month** | **float** |  | [optional] 
**expiry_year** | **float** |  | [optional] 

## Example

```python
from cashful.models.create_payment_method_dto import CreatePaymentMethodDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePaymentMethodDto from a JSON string
create_payment_method_dto_instance = CreatePaymentMethodDto.from_json(json)
# print the JSON string representation of the object
print(CreatePaymentMethodDto.to_json())

# convert the object into a dict
create_payment_method_dto_dict = create_payment_method_dto_instance.to_dict()
# create an instance of CreatePaymentMethodDto from a dict
create_payment_method_dto_from_dict = CreatePaymentMethodDto.from_dict(create_payment_method_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


