# LinkedAccountDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**account_id** | **str** | Account ID | 
**provider_id** | **str** | Provider ID (e.g., google, github) | 
**user_id** | **str** | User ID | 
**access_token** | **str** | Access token | [optional] 
**refresh_token** | **str** | Refresh token | [optional] 
**id_token** | **str** | ID token | [optional] 
**access_token_expires_at** | **datetime** | Access token expires at | [optional] 
**refresh_token_expires_at** | **datetime** | Refresh token expires at | [optional] 
**scope** | **str** | Scope | [optional] 
**password** | **str** | Password | [optional] 
**created_at** | **datetime** | Creation timestamp | 
**updated_at** | **datetime** | Last update timestamp | 

## Example

```python
from cashful.models.linked_account_dto import LinkedAccountDto

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedAccountDto from a JSON string
linked_account_dto_instance = LinkedAccountDto.from_json(json)
# print the JSON string representation of the object
print(LinkedAccountDto.to_json())

# convert the object into a dict
linked_account_dto_dict = linked_account_dto_instance.to_dict()
# create an instance of LinkedAccountDto from a dict
linked_account_dto_from_dict = LinkedAccountDto.from_dict(linked_account_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


