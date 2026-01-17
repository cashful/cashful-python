# AnalyticsSummaryDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**balance** | **float** | Current merchant balance in cents/smallest unit | 
**customers** | **float** | Total number of customers | 
**transactions** | **float** | Total number of transactions | 
**members** | **float** | Total number of organization members | 

## Example

```python
from cashful.models.analytics_summary_dto import AnalyticsSummaryDto

# TODO update the JSON string below
json = "{}"
# create an instance of AnalyticsSummaryDto from a JSON string
analytics_summary_dto_instance = AnalyticsSummaryDto.from_json(json)
# print the JSON string representation of the object
print(AnalyticsSummaryDto.to_json())

# convert the object into a dict
analytics_summary_dto_dict = analytics_summary_dto_instance.to_dict()
# create an instance of AnalyticsSummaryDto from a dict
analytics_summary_dto_from_dict = AnalyticsSummaryDto.from_dict(analytics_summary_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


