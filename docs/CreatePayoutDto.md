# CreatePayoutDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant whose balance is being requested. If omitted, defaults to the authenticated merchant. | [optional] 
**amount** | **float** |  | 
**currency** | **str** |  | 
**bank_account** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**metadata** | **Dict[str, object]** |  | 

## Example

```python
from cashful.models.create_payout_dto import CreatePayoutDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePayoutDto from a JSON string
create_payout_dto_instance = CreatePayoutDto.from_json(json)
# print the JSON string representation of the object
print(CreatePayoutDto.to_json())

# convert the object into a dict
create_payout_dto_dict = create_payout_dto_instance.to_dict()
# create an instance of CreatePayoutDto from a dict
create_payout_dto_from_dict = CreatePayoutDto.from_dict(create_payout_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


