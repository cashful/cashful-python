# cashful.CheckoutsApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_checkout_session**](CheckoutsApi.md#create_checkout_session) | **POST** /api/canary/checkout/sessions | Create Hosted Checkout
[**list_checkout_sessions**](CheckoutsApi.md#list_checkout_sessions) | **GET** /api/canary/checkout/sessions | List Checkout Sessions
[**retrieve_checkout_session**](CheckoutsApi.md#retrieve_checkout_session) | **GET** /api/canary/checkout/sessions/{id} | Retrieve Checkout Session


# **create_checkout_session**
> CheckoutSessionResponseDto create_checkout_session(create_checkout_session_dto)

Create Hosted Checkout

Creates a hosted payment page. Used for: (1) A standard e-commerce purchase, or (2) a "Pay-In" to fund a CustomerBalance.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.checkout_session_response_dto import CheckoutSessionResponseDto
from cashful.models.create_checkout_session_dto import CreateCheckoutSessionDto
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
    api_instance = cashful.CheckoutsApi(api_client)
    create_checkout_session_dto = cashful.CreateCheckoutSessionDto() # CreateCheckoutSessionDto | Checkout session details

    try:
        # Create Hosted Checkout
        api_response = api_instance.create_checkout_session(create_checkout_session_dto)
        print("The response of CheckoutsApi->create_checkout_session:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CheckoutsApi->create_checkout_session: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_checkout_session_dto** | [**CreateCheckoutSessionDto**](CreateCheckoutSessionDto.md)| Checkout session details | 

### Return type

[**CheckoutSessionResponseDto**](CheckoutSessionResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Checkout session created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_checkout_sessions**
> ListCheckoutSessionsResponseDto list_checkout_sessions(merchant_id, limit=limit, offset=offset, status=status)

List Checkout Sessions

Lists checkout sessions

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_checkout_sessions_response_dto import ListCheckoutSessionsResponseDto
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
    api_instance = cashful.CheckoutsApi(api_client)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant. This parameter is required.
    limit = 50 # float | Maximum number of records to return (optional)
    offset = 0 # float | Number of records to skip (optional)
    status = 'status_example' # str | The status to filter checkout sessions (optional)

    try:
        # List Checkout Sessions
        api_response = api_instance.list_checkout_sessions(merchant_id, limit=limit, offset=offset, status=status)
        print("The response of CheckoutsApi->list_checkout_sessions:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CheckoutsApi->list_checkout_sessions: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The ID of the merchant. This parameter is required. | 
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 
 **status** | **str**| The status to filter checkout sessions | [optional] 

### Return type

[**ListCheckoutSessionsResponseDto**](ListCheckoutSessionsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved checkout sessions |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **retrieve_checkout_session**
> CheckoutSessionResponseDto retrieve_checkout_session(id)

Retrieve Checkout Session

Retrieves details of a specific checkout session

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.checkout_session_response_dto import CheckoutSessionResponseDto
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
    api_instance = cashful.CheckoutsApi(api_client)
    id = 'id_example' # str | The unique identifier of the checkout session

    try:
        # Retrieve Checkout Session
        api_response = api_instance.retrieve_checkout_session(id)
        print("The response of CheckoutsApi->retrieve_checkout_session:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CheckoutsApi->retrieve_checkout_session: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the checkout session | 

### Return type

[**CheckoutSessionResponseDto**](CheckoutSessionResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved checkout session |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

