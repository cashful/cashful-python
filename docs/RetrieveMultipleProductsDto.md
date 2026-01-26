# RetrieveMultipleProductsDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ids** | **List[str]** | Max 50 IDs of the products to retrieve | 

## Example

```python
from cashful.models.retrieve_multiple_products_dto import RetrieveMultipleProductsDto

# TODO update the JSON string below
json = "{}"
# create an instance of RetrieveMultipleProductsDto from a JSON string
retrieve_multiple_products_dto_instance = RetrieveMultipleProductsDto.from_json(json)
# print the JSON string representation of the object
print(RetrieveMultipleProductsDto.to_json())

# convert the object into a dict
retrieve_multiple_products_dto_dict = retrieve_multiple_products_dto_instance.to_dict()
# create an instance of RetrieveMultipleProductsDto from a dict
retrieve_multiple_products_dto_from_dict = RetrieveMultipleProductsDto.from_dict(retrieve_multiple_products_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


