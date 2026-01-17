# RevokeSessionDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**session_id** | **str** | The session ID to revoke | 

## Example

```python
from cashful.models.revoke_session_dto import RevokeSessionDto

# TODO update the JSON string below
json = "{}"
# create an instance of RevokeSessionDto from a JSON string
revoke_session_dto_instance = RevokeSessionDto.from_json(json)
# print the JSON string representation of the object
print(RevokeSessionDto.to_json())

# convert the object into a dict
revoke_session_dto_dict = revoke_session_dto_instance.to_dict()
# create an instance of RevokeSessionDto from a dict
revoke_session_dto_from_dict = RevokeSessionDto.from_dict(revoke_session_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


