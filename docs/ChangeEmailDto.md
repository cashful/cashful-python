# ChangeEmailDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**new_email** | **str** | The new email address to set must be a valid email address | 
**callback_url** | **str** | The URL to redirect to after email verification | [optional] 

## Example

```python
from cashful.models.change_email_dto import ChangeEmailDto

# TODO update the JSON string below
json = "{}"
# create an instance of ChangeEmailDto from a JSON string
change_email_dto_instance = ChangeEmailDto.from_json(json)
# print the JSON string representation of the object
print(ChangeEmailDto.to_json())

# convert the object into a dict
change_email_dto_dict = change_email_dto_instance.to_dict()
# create an instance of ChangeEmailDto from a dict
change_email_dto_from_dict = ChangeEmailDto.from_dict(change_email_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


