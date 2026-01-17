# ListProductsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[ProductResponseDto]**](ProductResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_products_response_dto import ListProductsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListProductsResponseDto from a JSON string
list_products_response_dto_instance = ListProductsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListProductsResponseDto.to_json())

# convert the object into a dict
list_products_response_dto_dict = list_products_response_dto_instance.to_dict()
# create an instance of ListProductsResponseDto from a dict
list_products_response_dto_from_dict = ListProductsResponseDto.from_dict(list_products_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


