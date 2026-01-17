# AnalyticsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transactions** | [**TimeframeMetricsDto**](TimeframeMetricsDto.md) |  | 
**new_customers** | [**CustomerStatsDto**](CustomerStatsDto.md) |  | 
**recent_transactions** | [**List[CustomerTransactionDto]**](CustomerTransactionDto.md) | The 5 most recent transactions | 

## Example

```python
from cashful.models.analytics_response_dto import AnalyticsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of AnalyticsResponseDto from a JSON string
analytics_response_dto_instance = AnalyticsResponseDto.from_json(json)
# print the JSON string representation of the object
print(AnalyticsResponseDto.to_json())

# convert the object into a dict
analytics_response_dto_dict = analytics_response_dto_instance.to_dict()
# create an instance of AnalyticsResponseDto from a dict
analytics_response_dto_from_dict = AnalyticsResponseDto.from_dict(analytics_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


