# SessionUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**email** | **str** |  | 
**email_verified** | **bool** |  | 
**name** | **str** |  | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 

## Example

```python
from cashful.models.session_user_dto import SessionUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of SessionUserDto from a JSON string
session_user_dto_instance = SessionUserDto.from_json(json)
# print the JSON string representation of the object
print(SessionUserDto.to_json())

# convert the object into a dict
session_user_dto_dict = session_user_dto_instance.to_dict()
# create an instance of SessionUserDto from a dict
session_user_dto_from_dict = SessionUserDto.from_dict(session_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


