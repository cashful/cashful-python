# SessionDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**user_id** | **str** |  | 
**expires_at** | **datetime** |  | 
**ip_address** | **str** |  | [optional] 
**user_agent** | **str** |  | [optional] 

## Example

```python
from cashful.models.session_dto import SessionDto

# TODO update the JSON string below
json = "{}"
# create an instance of SessionDto from a JSON string
session_dto_instance = SessionDto.from_json(json)
# print the JSON string representation of the object
print(SessionDto.to_json())

# convert the object into a dict
session_dto_dict = session_dto_instance.to_dict()
# create an instance of SessionDto from a dict
session_dto_from_dict = SessionDto.from_dict(session_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


