# SignOutResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Sign out successful | 

## Example

```python
from cashful.models.sign_out_response_dto import SignOutResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of SignOutResponseDto from a JSON string
sign_out_response_dto_instance = SignOutResponseDto.from_json(json)
# print the JSON string representation of the object
print(SignOutResponseDto.to_json())

# convert the object into a dict
sign_out_response_dto_dict = sign_out_response_dto_instance.to_dict()
# create an instance of SignOutResponseDto from a dict
sign_out_response_dto_from_dict = SignOutResponseDto.from_dict(sign_out_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


