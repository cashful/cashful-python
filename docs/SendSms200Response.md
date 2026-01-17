# SendSms200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_id** | **str** | SMS message ID | [optional] 

## Example

```python
from cashful.models.send_sms200_response import SendSms200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SendSms200Response from a JSON string
send_sms200_response_instance = SendSms200Response.from_json(json)
# print the JSON string representation of the object
print(SendSms200Response.to_json())

# convert the object into a dict
send_sms200_response_dict = send_sms200_response_instance.to_dict()
# create an instance of SendSms200Response from a dict
send_sms200_response_from_dict = SendSms200Response.from_dict(send_sms200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


