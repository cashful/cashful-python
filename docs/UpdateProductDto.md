# UpdateProductDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the product | [optional] 
**description** | **str** | A description of the product | [optional] 
**amount** | **float** | The price of the product in the smallest currency unit | [optional] 
**active** | **bool** | Whether the product is active | [optional] 
**metadata** | **Dict[str, object]** | Optional custom metadata | 

## Example

```python
from cashful.models.update_product_dto import UpdateProductDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateProductDto from a JSON string
update_product_dto_instance = UpdateProductDto.from_json(json)
# print the JSON string representation of the object
print(UpdateProductDto.to_json())

# convert the object into a dict
update_product_dto_dict = update_product_dto_instance.to_dict()
# create an instance of UpdateProductDto from a dict
update_product_dto_from_dict = UpdateProductDto.from_dict(update_product_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


