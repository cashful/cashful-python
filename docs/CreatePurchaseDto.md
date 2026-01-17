# CreatePurchaseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant whose balance is being requested. If omitted, defaults to the authenticated merchant. | [optional] 
**customer_id** | **str** | The unique identifier of the customer | 
**product_id** | **str** | The unique identifier of the product | 
**amount** | **float** | The amount in the smallest currency unit | 
**currency** | **str** | The three-letter ISO 4217 currency code | 
**quantity** | **float** | The quantity of items in the purchase | [optional] 

## Example

```python
from cashful.models.create_purchase_dto import CreatePurchaseDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePurchaseDto from a JSON string
create_purchase_dto_instance = CreatePurchaseDto.from_json(json)
# print the JSON string representation of the object
print(CreatePurchaseDto.to_json())

# convert the object into a dict
create_purchase_dto_dict = create_purchase_dto_instance.to_dict()
# create an instance of CreatePurchaseDto from a dict
create_purchase_dto_from_dict = CreatePurchaseDto.from_dict(create_purchase_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


