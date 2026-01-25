# GetJsonWebKeySetResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keys** | [**List[JwkDto]**](JwkDto.md) | Array of public JSON Web Keys | 

## Example

```python
from cashful.models.get_json_web_key_set_response_dto import GetJsonWebKeySetResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of GetJsonWebKeySetResponseDto from a JSON string
get_json_web_key_set_response_dto_instance = GetJsonWebKeySetResponseDto.from_json(json)
# print the JSON string representation of the object
print(GetJsonWebKeySetResponseDto.to_json())

# convert the object into a dict
get_json_web_key_set_response_dto_dict = get_json_web_key_set_response_dto_instance.to_dict()
# create an instance of GetJsonWebKeySetResponseDto from a dict
get_json_web_key_set_response_dto_from_dict = GetJsonWebKeySetResponseDto.from_dict(get_json_web_key_set_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


