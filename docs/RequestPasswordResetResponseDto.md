# RequestPasswordResetResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **bool** | Request status | 
**message** | **str** | Response message | [optional] 

## Example

```python
from cashful.models.request_password_reset_response_dto import RequestPasswordResetResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of RequestPasswordResetResponseDto from a JSON string
request_password_reset_response_dto_instance = RequestPasswordResetResponseDto.from_json(json)
# print the JSON string representation of the object
print(RequestPasswordResetResponseDto.to_json())

# convert the object into a dict
request_password_reset_response_dto_dict = request_password_reset_response_dto_instance.to_dict()
# create an instance of RequestPasswordResetResponseDto from a dict
request_password_reset_response_dto_from_dict = RequestPasswordResetResponseDto.from_dict(request_password_reset_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


