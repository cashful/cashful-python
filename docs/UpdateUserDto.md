# UpdateUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of user | [optional] 
**image** | **str** | The image of user | [optional] 

## Example

```python
from cashful.models.update_user_dto import UpdateUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateUserDto from a JSON string
update_user_dto_instance = UpdateUserDto.from_json(json)
# print the JSON string representation of the object
print(UpdateUserDto.to_json())

# convert the object into a dict
update_user_dto_dict = update_user_dto_instance.to_dict()
# create an instance of UpdateUserDto from a dict
update_user_dto_from_dict = UpdateUserDto.from_dict(update_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


