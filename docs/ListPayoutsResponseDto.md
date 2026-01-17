# ListPayoutsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PayoutResponseDto]**](PayoutResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_payouts_response_dto import ListPayoutsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListPayoutsResponseDto from a JSON string
list_payouts_response_dto_instance = ListPayoutsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListPayoutsResponseDto.to_json())

# convert the object into a dict
list_payouts_response_dto_dict = list_payouts_response_dto_instance.to_dict()
# create an instance of ListPayoutsResponseDto from a dict
list_payouts_response_dto_from_dict = ListPayoutsResponseDto.from_dict(list_payouts_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


