# ListCustomersResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CustomerResponseDto]**](CustomerResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_customers_response_dto import ListCustomersResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListCustomersResponseDto from a JSON string
list_customers_response_dto_instance = ListCustomersResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListCustomersResponseDto.to_json())

# convert the object into a dict
list_customers_response_dto_dict = list_customers_response_dto_instance.to_dict()
# create an instance of ListCustomersResponseDto from a dict
list_customers_response_dto_from_dict = ListCustomersResponseDto.from_dict(list_customers_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


