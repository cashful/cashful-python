# ProductResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**merchant_id** | **str** |  | 
**name** | **str** |  | 
**description** | **str** |  | [optional] 
**amount** | **float** |  | [optional] 
**currency** | **str** |  | 
**active** | **bool** |  | 
**image_id** | **str** | The ID of the product image file | [optional] 
**image_url** | **str** | The public URL of the product image | [optional] 
**metadata** | **Dict[str, object]** |  | 

## Example

```python
from cashful.models.product_response_dto import ProductResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ProductResponseDto from a JSON string
product_response_dto_instance = ProductResponseDto.from_json(json)
# print the JSON string representation of the object
print(ProductResponseDto.to_json())

# convert the object into a dict
product_response_dto_dict = product_response_dto_instance.to_dict()
# create an instance of ProductResponseDto from a dict
product_response_dto_from_dict = ProductResponseDto.from_dict(product_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


