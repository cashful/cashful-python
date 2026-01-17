# cashful.AnalyticsApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_analytics**](AnalyticsApi.md#get_analytics) | **GET** /api/canary/analytics | Get Analytics
[**get_analytics_summary**](AnalyticsApi.md#get_analytics_summary) | **GET** /api/canary/analytics/summary | Get Analytics Summary


# **get_analytics**
> AnalyticsResponseDto get_analytics(merchant_id)

Get Analytics

Retrieves transaction volume and customer growth metrics for the merchant.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.analytics_response_dto import AnalyticsResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.cashful.africa
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "https://api.cashful.africa"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AnalyticsApi(api_client)
    merchant_id = 'merchant_123' # str | The unique identifier of the merchant

    try:
        # Get Analytics
        api_response = api_instance.get_analytics(merchant_id)
        print("The response of AnalyticsApi->get_analytics:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AnalyticsApi->get_analytics: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The unique identifier of the merchant | 

### Return type

[**AnalyticsResponseDto**](AnalyticsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved analytics |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_analytics_summary**
> AnalyticsSummaryDto get_analytics_summary(merchant_id)

Get Analytics Summary

Retrieves a quick summary of key metrics for the merchant.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.analytics_summary_dto import AnalyticsSummaryDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.cashful.africa
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "https://api.cashful.africa"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AnalyticsApi(api_client)
    merchant_id = 'merchant_123' # str | The unique identifier of the merchant

    try:
        # Get Analytics Summary
        api_response = api_instance.get_analytics_summary(merchant_id)
        print("The response of AnalyticsApi->get_analytics_summary:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AnalyticsApi->get_analytics_summary: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The unique identifier of the merchant | 

### Return type

[**AnalyticsSummaryDto**](AnalyticsSummaryDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved analytics summary |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

