# UpdateCheckoutSessionDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** |  | 
**success_url** | **str** | The URL to redirect to on successful payment | [optional] 
**failure_url** | **str** | The URL to redirect to on failure | [optional] 
**cancel_url** | **str** | The URL to redirect to on cancel | [optional] 
**metadata** | **Dict[str, object]** | Optional custom metadata | 
**hosted_checkout_config** | [**HostedCheckoutConfigDto**](HostedCheckoutConfigDto.md) | Configuration for the hosted checkout page | [optional] 

## Example

```python
from cashful.models.update_checkout_session_dto import UpdateCheckoutSessionDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCheckoutSessionDto from a JSON string
update_checkout_session_dto_instance = UpdateCheckoutSessionDto.from_json(json)
# print the JSON string representation of the object
print(UpdateCheckoutSessionDto.to_json())

# convert the object into a dict
update_checkout_session_dto_dict = update_checkout_session_dto_instance.to_dict()
# create an instance of UpdateCheckoutSessionDto from a dict
update_checkout_session_dto_from_dict = UpdateCheckoutSessionDto.from_dict(update_checkout_session_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


