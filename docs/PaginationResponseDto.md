# PaginationResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**limit** | **float** | Maximum number of items returned in this response | 
**offset** | **float** | Number of items skipped before this response | 
**total** | **float** | Total number of items available | 
**has_more** | **bool** | Whether there are more items available beyond this response | 

## Example

```python
from cashful.models.pagination_response_dto import PaginationResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of PaginationResponseDto from a JSON string
pagination_response_dto_instance = PaginationResponseDto.from_json(json)
# print the JSON string representation of the object
print(PaginationResponseDto.to_json())

# convert the object into a dict
pagination_response_dto_dict = pagination_response_dto_instance.to_dict()
# create an instance of PaginationResponseDto from a dict
pagination_response_dto_from_dict = PaginationResponseDto.from_dict(pagination_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


