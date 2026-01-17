# UnbanUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user to unban | 

## Example

```python
from cashful.models.unban_user_dto import UnbanUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of UnbanUserDto from a JSON string
unban_user_dto_instance = UnbanUserDto.from_json(json)
# print the JSON string representation of the object
print(UnbanUserDto.to_json())

# convert the object into a dict
unban_user_dto_dict = unban_user_dto_instance.to_dict()
# create an instance of UnbanUserDto from a dict
unban_user_dto_from_dict = UnbanUserDto.from_dict(unban_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


