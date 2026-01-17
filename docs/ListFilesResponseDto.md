# ListFilesResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[FileDto]**](FileDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_files_response_dto import ListFilesResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListFilesResponseDto from a JSON string
list_files_response_dto_instance = ListFilesResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListFilesResponseDto.to_json())

# convert the object into a dict
list_files_response_dto_dict = list_files_response_dto_instance.to_dict()
# create an instance of ListFilesResponseDto from a dict
list_files_response_dto_from_dict = ListFilesResponseDto.from_dict(list_files_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


