# SendSmsDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**to** | **object** | Recipient phone number(s) in international format | 
**message** | **str** | SMS message content | 
**var_from** | **str** | Sender name or number | [optional] 

## Example

```python
from cashful.models.send_sms_dto import SendSmsDto

# TODO update the JSON string below
json = "{}"
# create an instance of SendSmsDto from a JSON string
send_sms_dto_instance = SendSmsDto.from_json(json)
# print the JSON string representation of the object
print(SendSmsDto.to_json())

# convert the object into a dict
send_sms_dto_dict = send_sms_dto_instance.to_dict()
# create an instance of SendSmsDto from a dict
send_sms_dto_from_dict = SendSmsDto.from_dict(send_sms_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


