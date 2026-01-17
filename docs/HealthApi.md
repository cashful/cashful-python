# cashful.HealthApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**check_health**](HealthApi.md#check_health) | **GET** /api/canary/health | Health check endpoint


# **check_health**
> object check_health()

Health check endpoint

Performs a health check on the application and external dependencies

### Example


```python
import cashful
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
    api_instance = cashful.HealthApi(api_client)

    try:
        # Health check endpoint
        api_response = api_instance.check_health()
        print("The response of HealthApi->check_health:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling HealthApi->check_health: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Application and all dependencies are healthy |  -  |
**503** | One or more health checks failed |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

