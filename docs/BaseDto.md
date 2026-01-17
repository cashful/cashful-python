# BaseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 

## Example

```python
from cashful.models.base_dto import BaseDto

# TODO update the JSON string below
json = "{}"
# create an instance of BaseDto from a JSON string
base_dto_instance = BaseDto.from_json(json)
# print the JSON string representation of the object
print(BaseDto.to_json())

# convert the object into a dict
base_dto_dict = base_dto_instance.to_dict()
# create an instance of BaseDto from a dict
base_dto_from_dict = BaseDto.from_dict(base_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


