# FileDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**key** | **str** |  | 
**bucket** | **str** |  | 
**filename** | **str** |  | 
**mime_type** | **str** |  | 
**size** | **float** |  | 
**tags** | **List[str]** |  | 
**status** | **str** |  | 
**checksum** | **str** |  | [optional] 
**is_public** | **bool** |  | 
**related_entity_id** | **str** |  | [optional] 
**related_entity_type** | **str** |  | [optional] 
**uploaded_by_id** | **str** |  | [optional] 

## Example

```python
from cashful.models.file_dto import FileDto

# TODO update the JSON string below
json = "{}"
# create an instance of FileDto from a JSON string
file_dto_instance = FileDto.from_json(json)
# print the JSON string representation of the object
print(FileDto.to_json())

# convert the object into a dict
file_dto_dict = file_dto_instance.to_dict()
# create an instance of FileDto from a dict
file_dto_from_dict = FileDto.from_dict(file_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


