# ListAccountsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**accounts** | **List[object]** | List of linked social accounts | 

## Example

```python
from cashful.models.list_accounts_response_dto import ListAccountsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListAccountsResponseDto from a JSON string
list_accounts_response_dto_instance = ListAccountsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListAccountsResponseDto.to_json())

# convert the object into a dict
list_accounts_response_dto_dict = list_accounts_response_dto_instance.to_dict()
# create an instance of ListAccountsResponseDto from a dict
list_accounts_response_dto_from_dict = ListAccountsResponseDto.from_dict(list_accounts_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


