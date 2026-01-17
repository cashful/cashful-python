# MetricStatsDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**count** | **float** | Count of items | 
**sum** | **float** | Sum of amounts in cents/smallest unit | 

## Example

```python
from cashful.models.metric_stats_dto import MetricStatsDto

# TODO update the JSON string below
json = "{}"
# create an instance of MetricStatsDto from a JSON string
metric_stats_dto_instance = MetricStatsDto.from_json(json)
# print the JSON string representation of the object
print(MetricStatsDto.to_json())

# convert the object into a dict
metric_stats_dto_dict = metric_stats_dto_instance.to_dict()
# create an instance of MetricStatsDto from a dict
metric_stats_dto_from_dict = MetricStatsDto.from_dict(metric_stats_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


