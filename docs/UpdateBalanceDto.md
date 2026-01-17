# UpdateBalanceDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount** | **float** | The amount to adjust the balance by | 
**currency** | **str** | The currency for the balance | [optional] 

## Example

```python
from cashful.models.update_balance_dto import UpdateBalanceDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateBalanceDto from a JSON string
update_balance_dto_instance = UpdateBalanceDto.from_json(json)
# print the JSON string representation of the object
print(UpdateBalanceDto.to_json())

# convert the object into a dict
update_balance_dto_dict = update_balance_dto_instance.to_dict()
# create an instance of UpdateBalanceDto from a dict
update_balance_dto_from_dict = UpdateBalanceDto.from_dict(update_balance_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


