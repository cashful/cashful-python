# IsUsernameAvailableResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**available** | **bool** | Whether username is available | 

## Example

```python
from cashful.models.is_username_available_response_dto import IsUsernameAvailableResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of IsUsernameAvailableResponseDto from a JSON string
is_username_available_response_dto_instance = IsUsernameAvailableResponseDto.from_json(json)
# print the JSON string representation of the object
print(IsUsernameAvailableResponseDto.to_json())

# convert the object into a dict
is_username_available_response_dto_dict = is_username_available_response_dto_instance.to_dict()
# create an instance of IsUsernameAvailableResponseDto from a dict
is_username_available_response_dto_from_dict = IsUsernameAvailableResponseDto.from_dict(is_username_available_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


