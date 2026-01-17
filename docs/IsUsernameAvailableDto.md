# IsUsernameAvailableDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | The username to check availability for | 

## Example

```python
from cashful.models.is_username_available_dto import IsUsernameAvailableDto

# TODO update the JSON string below
json = "{}"
# create an instance of IsUsernameAvailableDto from a JSON string
is_username_available_dto_instance = IsUsernameAvailableDto.from_json(json)
# print the JSON string representation of the object
print(IsUsernameAvailableDto.to_json())

# convert the object into a dict
is_username_available_dto_dict = is_username_available_dto_instance.to_dict()
# create an instance of IsUsernameAvailableDto from a dict
is_username_available_dto_from_dict = IsUsernameAvailableDto.from_dict(is_username_available_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


