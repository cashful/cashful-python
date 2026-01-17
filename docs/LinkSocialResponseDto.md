# LinkSocialResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Social account linked successfully | 
**account** | **object** | Linked account details | [optional] 

## Example

```python
from cashful.models.link_social_response_dto import LinkSocialResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of LinkSocialResponseDto from a JSON string
link_social_response_dto_instance = LinkSocialResponseDto.from_json(json)
# print the JSON string representation of the object
print(LinkSocialResponseDto.to_json())

# convert the object into a dict
link_social_response_dto_dict = link_social_response_dto_instance.to_dict()
# create an instance of LinkSocialResponseDto from a dict
link_social_response_dto_from_dict = LinkSocialResponseDto.from_dict(link_social_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


