# RequestPasswordResetDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** | The email address of user to send a password reset email to | 
**redirect_to** | **str** | The URL to redirect user to reset their password. If token isn&#39;t valid or expired, it&#39;ll be redirected with a query parameter &#x60;?error&#x3D;INVALID_TOKEN&#x60;. If token is valid, it&#39;ll be redirected with a query parameter &#x60;?token&#x3D;VALID_TOKEN&#x60; | [optional] 

## Example

```python
from cashful.models.request_password_reset_dto import RequestPasswordResetDto

# TODO update the JSON string below
json = "{}"
# create an instance of RequestPasswordResetDto from a JSON string
request_password_reset_dto_instance = RequestPasswordResetDto.from_json(json)
# print the JSON string representation of the object
print(RequestPasswordResetDto.to_json())

# convert the object into a dict
request_password_reset_dto_dict = request_password_reset_dto_instance.to_dict()
# create an instance of RequestPasswordResetDto from a dict
request_password_reset_dto_from_dict = RequestPasswordResetDto.from_dict(request_password_reset_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


