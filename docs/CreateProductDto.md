# CreateProductDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant whose balance is being requested. If omitted, defaults to the authenticated merchant. | [optional] 
**name** | **str** | The name of the product | 
**description** | **str** | A description of the product | [optional] 
**amount** | **float** | The price of the product in the smallest currency unit | [optional] 
**currency** | **str** | The three-letter ISO 4217 currency code | 
**active** | **bool** | Whether the product is active | [optional] 
**image_id** | **str** | The ID of the product image file | [optional] 
**metadata** | **Dict[str, object]** | Optional custom metadata | 

## Example

```python
from cashful.models.create_product_dto import CreateProductDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateProductDto from a JSON string
create_product_dto_instance = CreateProductDto.from_json(json)
# print the JSON string representation of the object
print(CreateProductDto.to_json())

# convert the object into a dict
create_product_dto_dict = create_product_dto_instance.to_dict()
# create an instance of CreateProductDto from a dict
create_product_dto_from_dict = CreateProductDto.from_dict(create_product_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


