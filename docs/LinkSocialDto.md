# LinkSocialDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The social provider to link | 
**access_token** | **str** | Access token from provider | [optional] 
**refresh_token** | **str** | Refresh token from provider | [optional] 
**id_token** | **str** | ID token from provider | [optional] 
**expires_at** | **float** | Token expiration time | [optional] 

## Example

```python
from cashful.models.link_social_dto import LinkSocialDto

# TODO update the JSON string below
json = "{}"
# create an instance of LinkSocialDto from a JSON string
link_social_dto_instance = LinkSocialDto.from_json(json)
# print the JSON string representation of the object
print(LinkSocialDto.to_json())

# convert the object into a dict
link_social_dto_dict = link_social_dto_instance.to_dict()
# create an instance of LinkSocialDto from a dict
link_social_dto_from_dict = LinkSocialDto.from_dict(link_social_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


