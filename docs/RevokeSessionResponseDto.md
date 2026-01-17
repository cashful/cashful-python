# RevokeSessionResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**success** | **bool** | Revocation status | 

## Example

```python
from cashful.models.revoke_session_response_dto import RevokeSessionResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of RevokeSessionResponseDto from a JSON string
revoke_session_response_dto_instance = RevokeSessionResponseDto.from_json(json)
# print the JSON string representation of the object
print(RevokeSessionResponseDto.to_json())

# convert the object into a dict
revoke_session_response_dto_dict = revoke_session_response_dto_instance.to_dict()
# create an instance of RevokeSessionResponseDto from a dict
revoke_session_response_dto_from_dict = RevokeSessionResponseDto.from_dict(revoke_session_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


