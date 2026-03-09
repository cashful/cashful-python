# BulkUpdateCustomersInputDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ids** | **List[str]** | List of IDs to target | 
**data** | **object** | Raw Prisma update payload | 

## Example

```python
from cashful.models.bulk_update_customers_input_dto import BulkUpdateCustomersInputDto

# TODO update the JSON string below
json = "{}"
# create an instance of BulkUpdateCustomersInputDto from a JSON string
bulk_update_customers_input_dto_instance = BulkUpdateCustomersInputDto.from_json(json)
# print the JSON string representation of the object
print(BulkUpdateCustomersInputDto.to_json())

# convert the object into a dict
bulk_update_customers_input_dto_dict = bulk_update_customers_input_dto_instance.to_dict()
# create an instance of BulkUpdateCustomersInputDto from a dict
bulk_update_customers_input_dto_from_dict = BulkUpdateCustomersInputDto.from_dict(bulk_update_customers_input_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


