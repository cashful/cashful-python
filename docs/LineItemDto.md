# LineItemDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**product_id** | **str** | The unique identifier of the product | [optional] 
**quantity** | **float** | The quantity of the product | [optional] 
**amount** | **float** | The amount for this line item in the smallest currency unit | 
**currency** | **str** | The three-letter ISO 4217 currency code | 

## Example

```python
from cashful.models.line_item_dto import LineItemDto

# TODO update the JSON string below
json = "{}"
# create an instance of LineItemDto from a JSON string
line_item_dto_instance = LineItemDto.from_json(json)
# print the JSON string representation of the object
print(LineItemDto.to_json())

# convert the object into a dict
line_item_dto_dict = line_item_dto_instance.to_dict()
# create an instance of LineItemDto from a dict
line_item_dto_from_dict = LineItemDto.from_dict(line_item_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


