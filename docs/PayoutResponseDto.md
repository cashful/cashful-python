# PayoutResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**merchant_id** | **str** |  | 
**amount** | **float** |  | 
**currency** | **str** |  | 
**status** | **str** |  | 
**bank_account** | **str** |  | [optional] 
**description** | **str** |  | [optional] 
**metadata** | **Dict[str, object]** |  | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 

## Example

```python
from cashful.models.payout_response_dto import PayoutResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of PayoutResponseDto from a JSON string
payout_response_dto_instance = PayoutResponseDto.from_json(json)
# print the JSON string representation of the object
print(PayoutResponseDto.to_json())

# convert the object into a dict
payout_response_dto_dict = payout_response_dto_instance.to_dict()
# create an instance of PayoutResponseDto from a dict
payout_response_dto_from_dict = PayoutResponseDto.from_dict(payout_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


