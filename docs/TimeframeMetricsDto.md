# TimeframeMetricsDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**daily** | [**MetricStatsDto**](MetricStatsDto.md) |  | 
**weekly** | [**MetricStatsDto**](MetricStatsDto.md) |  | 
**monthly** | [**MetricStatsDto**](MetricStatsDto.md) |  | 
**breakdown** | [**List[DailyBreakdownDto]**](DailyBreakdownDto.md) | Day-by-day breakdown for the last 30 days | 

## Example

```python
from cashful.models.timeframe_metrics_dto import TimeframeMetricsDto

# TODO update the JSON string below
json = "{}"
# create an instance of TimeframeMetricsDto from a JSON string
timeframe_metrics_dto_instance = TimeframeMetricsDto.from_json(json)
# print the JSON string representation of the object
print(TimeframeMetricsDto.to_json())

# convert the object into a dict
timeframe_metrics_dto_dict = timeframe_metrics_dto_instance.to_dict()
# create an instance of TimeframeMetricsDto from a dict
timeframe_metrics_dto_from_dict = TimeframeMetricsDto.from_dict(timeframe_metrics_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


