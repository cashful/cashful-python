# CustomerStatsDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**daily** | **float** | New customers in the last 24 hours | 
**weekly** | **float** | New customers in the last 7 days | 
**monthly** | **float** | New customers in the last 30 days | 

## Example

```python
from cashful.models.customer_stats_dto import CustomerStatsDto

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerStatsDto from a JSON string
customer_stats_dto_instance = CustomerStatsDto.from_json(json)
# print the JSON string representation of the object
print(CustomerStatsDto.to_json())

# convert the object into a dict
customer_stats_dto_dict = customer_stats_dto_instance.to_dict()
# create an instance of CustomerStatsDto from a dict
customer_stats_dto_from_dict = CustomerStatsDto.from_dict(customer_stats_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


