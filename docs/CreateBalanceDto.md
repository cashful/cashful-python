# CreateBalanceDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant | 
**amount** | **float** | The initial balance amount | 
**currency** | **str** | The currency for the balance | 

## Example

```python
from cashful.models.create_balance_dto import CreateBalanceDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateBalanceDto from a JSON string
create_balance_dto_instance = CreateBalanceDto.from_json(json)
# print the JSON string representation of the object
print(CreateBalanceDto.to_json())

# convert the object into a dict
create_balance_dto_dict = create_balance_dto_instance.to_dict()
# create an instance of CreateBalanceDto from a dict
create_balance_dto_from_dict = CreateBalanceDto.from_dict(create_balance_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


