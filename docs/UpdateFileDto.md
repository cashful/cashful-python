# UpdateFileDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tags** | **List[str]** |  | [optional] 
**status** | **str** |  | [optional] 
**is_public** | **bool** |  | [optional] 
**related_entity_id** | **str** |  | [optional] 
**related_entity_type** | **str** |  | [optional] 

## Example

```python
from cashful.models.update_file_dto import UpdateFileDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateFileDto from a JSON string
update_file_dto_instance = UpdateFileDto.from_json(json)
# print the JSON string representation of the object
print(UpdateFileDto.to_json())

# convert the object into a dict
update_file_dto_dict = update_file_dto_instance.to_dict()
# create an instance of UpdateFileDto from a dict
update_file_dto_from_dict = UpdateFileDto.from_dict(update_file_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


