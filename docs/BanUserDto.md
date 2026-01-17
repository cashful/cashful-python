# BanUserDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user to ban | 
**ban_reason** | **str** | The reason for the ban | [optional] 
**ban_expires_in** | **float** | Ban duration in seconds | [optional] 

## Example

```python
from cashful.models.ban_user_dto import BanUserDto

# TODO update the JSON string below
json = "{}"
# create an instance of BanUserDto from a JSON string
ban_user_dto_instance = BanUserDto.from_json(json)
# print the JSON string representation of the object
print(BanUserDto.to_json())

# convert the object into a dict
ban_user_dto_dict = ban_user_dto_instance.to_dict()
# create an instance of BanUserDto from a dict
ban_user_dto_from_dict = BanUserDto.from_dict(ban_user_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


