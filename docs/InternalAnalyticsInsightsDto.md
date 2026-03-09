# InternalAnalyticsInsightsDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organizations** | **float** | Total number of organizations on the platform | 
**customers** | **float** | Total number of active customers across all organizations | 
**saved_payment_methods** | **float** | Total number of saved payment methods across all customers (non-deleted) | 
**transactions** | **float** | Total number of transactions across all organizations | 
**total_available_balance** | **float** | Sum of available merchant balances across all organizations (in cents/smallest unit) | 
**total_pending_balance** | **float** | Sum of pending merchant balances across all organizations (in cents/smallest unit) | 

## Example

```python
from cashful.models.internal_analytics_insights_dto import InternalAnalyticsInsightsDto

# TODO update the JSON string below
json = "{}"
# create an instance of InternalAnalyticsInsightsDto from a JSON string
internal_analytics_insights_dto_instance = InternalAnalyticsInsightsDto.from_json(json)
# print the JSON string representation of the object
print(InternalAnalyticsInsightsDto.to_json())

# convert the object into a dict
internal_analytics_insights_dto_dict = internal_analytics_insights_dto_instance.to_dict()
# create an instance of InternalAnalyticsInsightsDto from a dict
internal_analytics_insights_dto_from_dict = InternalAnalyticsInsightsDto.from_dict(internal_analytics_insights_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


