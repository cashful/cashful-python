# cashful.NotificationsApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**send_email**](NotificationsApi.md#send_email) | **POST** /api/canary/notifications/email | Send an email notification
[**send_multi_channel_notification**](NotificationsApi.md#send_multi_channel_notification) | **POST** /api/canary/notifications/multi-channel | Send notifications via multiple channels
[**send_notification**](NotificationsApi.md#send_notification) | **POST** /api/canary/notifications/send | Send a notification via specified channel
[**send_sms**](NotificationsApi.md#send_sms) | **POST** /api/canary/notifications/sms | Send an SMS notification


# **send_email**
> SendEmail200Response send_email(send_email_dto)

Send an email notification

### Example


```python
import cashful
from cashful.models.send_email200_response import SendEmail200Response
from cashful.models.send_email_dto import SendEmailDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.cashful.africa
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "https://api.cashful.africa"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.NotificationsApi(api_client)
    send_email_dto = cashful.SendEmailDto() # SendEmailDto | 

    try:
        # Send an email notification
        api_response = api_instance.send_email(send_email_dto)
        print("The response of NotificationsApi->send_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling NotificationsApi->send_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **send_email_dto** | [**SendEmailDto**](SendEmailDto.md)|  | 

### Return type

[**SendEmail200Response**](SendEmail200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Email sent successfully |  -  |
**400** | Bad request |  -  |
**500** | Failed to send email |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **send_multi_channel_notification**
> SendMultiChannelNotification200Response send_multi_channel_notification()

Send notifications via multiple channels

### Example


```python
import cashful
from cashful.models.send_multi_channel_notification200_response import SendMultiChannelNotification200Response
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.cashful.africa
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "https://api.cashful.africa"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.NotificationsApi(api_client)

    try:
        # Send notifications via multiple channels
        api_response = api_instance.send_multi_channel_notification()
        print("The response of NotificationsApi->send_multi_channel_notification:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling NotificationsApi->send_multi_channel_notification: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**SendMultiChannelNotification200Response**](SendMultiChannelNotification200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Notifications sent |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **send_notification**
> send_notification(notification_dto)

Send a notification via specified channel

### Example


```python
import cashful
from cashful.models.notification_dto import NotificationDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.cashful.africa
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "https://api.cashful.africa"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.NotificationsApi(api_client)
    notification_dto = cashful.NotificationDto() # NotificationDto | 

    try:
        # Send a notification via specified channel
        api_instance.send_notification(notification_dto)
    except Exception as e:
        print("Exception when calling NotificationsApi->send_notification: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **notification_dto** | [**NotificationDto**](NotificationDto.md)|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Notification sent successfully |  -  |
**400** | Bad request |  -  |
**500** | Failed to send notification |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **send_sms**
> SendSms200Response send_sms(send_sms_dto)

Send an SMS notification

### Example


```python
import cashful
from cashful.models.send_sms200_response import SendSms200Response
from cashful.models.send_sms_dto import SendSmsDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.cashful.africa
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "https://api.cashful.africa"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.NotificationsApi(api_client)
    send_sms_dto = cashful.SendSmsDto() # SendSmsDto | 

    try:
        # Send an SMS notification
        api_response = api_instance.send_sms(send_sms_dto)
        print("The response of NotificationsApi->send_sms:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling NotificationsApi->send_sms: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **send_sms_dto** | [**SendSmsDto**](SendSmsDto.md)|  | 

### Return type

[**SendSms200Response**](SendSms200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | SMS sent successfully |  -  |
**400** | Bad request |  -  |
**500** | Failed to send SMS |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

