# SendEmailDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**to** | **object** | Recipient email address(es) | 
**subject** | **str** | Email subject | 
**template** | **str** | Template name to use (if using templates) | [optional] 
**context** | **object** | Context variables for template rendering | [optional] 
**html** | **str** | HTML content (if not using templates) | [optional] 
**text** | **str** | Plain text content | [optional] 
**var_from** | **str** | Sender email address | [optional] 
**cc** | **object** | CC email address(es) | [optional] 
**bcc** | **object** | BCC email address(es) | [optional] 

## Example

```python
from cashful.models.send_email_dto import SendEmailDto

# TODO update the JSON string below
json = "{}"
# create an instance of SendEmailDto from a JSON string
send_email_dto_instance = SendEmailDto.from_json(json)
# print the JSON string representation of the object
print(SendEmailDto.to_json())

# convert the object into a dict
send_email_dto_dict = send_email_dto_instance.to_dict()
# create an instance of SendEmailDto from a dict
send_email_dto_from_dict = SendEmailDto.from_dict(send_email_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


