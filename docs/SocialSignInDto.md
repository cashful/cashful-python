# SocialSignInDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The social provider to sign in with | 
**callback_url** | **str** | Callback URL to redirect to after the user has signed in | [optional] 
**new_user_callback_url** | **str** | Callback URL for new users | [optional] 
**error_callback_url** | **str** | Callback URL for errors | [optional] 
**disable_redirect** | **bool** | Disable automatic redirection to the provider | [optional] 
**id_token** | **object** | ID token from provider | [optional] 
**scopes** | **List[str]** | Array of scopes to request from the provider | [optional] 
**request_sign_up** | **bool** | Explicitly request sign-up | [optional] 
**login_hint** | **str** | Login hint for the authorization code request | [optional] 
**additional_data** | **str** | Additional data for the request | [optional] 

## Example

```python
from cashful.models.social_sign_in_dto import SocialSignInDto

# TODO update the JSON string below
json = "{}"
# create an instance of SocialSignInDto from a JSON string
social_sign_in_dto_instance = SocialSignInDto.from_json(json)
# print the JSON string representation of the object
print(SocialSignInDto.to_json())

# convert the object into a dict
social_sign_in_dto_dict = social_sign_in_dto_instance.to_dict()
# create an instance of SocialSignInDto from a dict
social_sign_in_dto_from_dict = SocialSignInDto.from_dict(social_sign_in_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


