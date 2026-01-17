# BanUserResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | User banned successfully | 

## Example

```python
from cashful.models.ban_user_response_dto import BanUserResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of BanUserResponseDto from a JSON string
ban_user_response_dto_instance = BanUserResponseDto.from_json(json)
# print the JSON string representation of the object
print(BanUserResponseDto.to_json())

# convert the object into a dict
ban_user_response_dto_dict = ban_user_response_dto_instance.to_dict()
# create an instance of BanUserResponseDto from a dict
ban_user_response_dto_from_dict = BanUserResponseDto.from_dict(ban_user_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


