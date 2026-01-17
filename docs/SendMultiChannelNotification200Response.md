# SendMultiChannelNotification200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** | Email message ID | [optional] 
**sms** | **str** | SMS message ID | [optional] 

## Example

```python
from cashful.models.send_multi_channel_notification200_response import SendMultiChannelNotification200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SendMultiChannelNotification200Response from a JSON string
send_multi_channel_notification200_response_instance = SendMultiChannelNotification200Response.from_json(json)
# print the JSON string representation of the object
print(SendMultiChannelNotification200Response.to_json())

# convert the object into a dict
send_multi_channel_notification200_response_dict = send_multi_channel_notification200_response_instance.to_dict()
# create an instance of SendMultiChannelNotification200Response from a dict
send_multi_channel_notification200_response_from_dict = SendMultiChannelNotification200Response.from_dict(send_multi_channel_notification200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


