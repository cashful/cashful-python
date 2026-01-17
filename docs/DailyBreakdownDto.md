# DailyBreakdownDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_date** | **str** | The date for this breakdown (ISO string) | 
**count** | **float** | Count of transactions on this day | 
**sum** | **float** | Sum of transaction amounts on this day | 

## Example

```python
from cashful.models.daily_breakdown_dto import DailyBreakdownDto

# TODO update the JSON string below
json = "{}"
# create an instance of DailyBreakdownDto from a JSON string
daily_breakdown_dto_instance = DailyBreakdownDto.from_json(json)
# print the JSON string representation of the object
print(DailyBreakdownDto.to_json())

# convert the object into a dict
daily_breakdown_dto_dict = daily_breakdown_dto_instance.to_dict()
# create an instance of DailyBreakdownDto from a dict
daily_breakdown_dto_from_dict = DailyBreakdownDto.from_dict(daily_breakdown_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


