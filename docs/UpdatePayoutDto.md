# UpdatePayoutDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**metadata** | **Dict[str, object]** |  | 

## Example

```python
from cashful.models.update_payout_dto import UpdatePayoutDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePayoutDto from a JSON string
update_payout_dto_instance = UpdatePayoutDto.from_json(json)
# print the JSON string representation of the object
print(UpdatePayoutDto.to_json())

# convert the object into a dict
update_payout_dto_dict = update_payout_dto_instance.to_dict()
# create an instance of UpdatePayoutDto from a dict
update_payout_dto_from_dict = UpdatePayoutDto.from_dict(update_payout_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


