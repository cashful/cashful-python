# cashful.PaymentIntentsApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cancel_payment_intent**](PaymentIntentsApi.md#cancel_payment_intent) | **POST** /api/canary/payment-intents/{id}/cancel | Cancel Payment Intent
[**confirm_payment_intent**](PaymentIntentsApi.md#confirm_payment_intent) | **POST** /api/canary/payment-intents/{id}/confirm | Confirm Payment Intent
[**create_payment_intent**](PaymentIntentsApi.md#create_payment_intent) | **POST** /api/canary/payment-intents | Create Payment Intent
[**list_payment_intents**](PaymentIntentsApi.md#list_payment_intents) | **GET** /api/canary/payment-intents | List Payment Intents
[**retrieve_payment_intent**](PaymentIntentsApi.md#retrieve_payment_intent) | **GET** /api/canary/payment-intents/{id} | Retrieve Payment Intent


# **cancel_payment_intent**
> PaymentIntentResponseDto cancel_payment_intent(id)

Cancel Payment Intent

Cancels a payment intent that has not yet succeeded or failed.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.payment_intent_response_dto import PaymentIntentResponseDto
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
    api_instance = cashful.PaymentIntentsApi(api_client)
    id = 'id_example' # str | The unique identifier of the payment intent

    try:
        # Cancel Payment Intent
        api_response = api_instance.cancel_payment_intent(id)
        print("The response of PaymentIntentsApi->cancel_payment_intent:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentIntentsApi->cancel_payment_intent: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the payment intent | 

### Return type

[**PaymentIntentResponseDto**](PaymentIntentResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Payment intent canceled |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **confirm_payment_intent**
> PaymentIntentResponseDto confirm_payment_intent(id)

Confirm Payment Intent

Confirms a payment intent that requires confirmation. This initiates the actual payment processing.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.payment_intent_response_dto import PaymentIntentResponseDto
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
    api_instance = cashful.PaymentIntentsApi(api_client)
    id = 'id_example' # str | The unique identifier of the payment intent

    try:
        # Confirm Payment Intent
        api_response = api_instance.confirm_payment_intent(id)
        print("The response of PaymentIntentsApi->confirm_payment_intent:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentIntentsApi->confirm_payment_intent: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the payment intent | 

### Return type

[**PaymentIntentResponseDto**](PaymentIntentResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Payment intent confirmed and processing |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_payment_intent**
> PaymentIntentResponseDto create_payment_intent(create_payment_intent_dto)

Create Payment Intent

Creates a payment intent for off-session charges. Used for subscriptions, recurring billing, or server-to-server payments with saved cards.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_payment_intent_dto import CreatePaymentIntentDto
from cashful.models.payment_intent_response_dto import PaymentIntentResponseDto
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
    api_instance = cashful.PaymentIntentsApi(api_client)
    create_payment_intent_dto = cashful.CreatePaymentIntentDto() # CreatePaymentIntentDto | Payment intent details

    try:
        # Create Payment Intent
        api_response = api_instance.create_payment_intent(create_payment_intent_dto)
        print("The response of PaymentIntentsApi->create_payment_intent:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentIntentsApi->create_payment_intent: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_payment_intent_dto** | [**CreatePaymentIntentDto**](CreatePaymentIntentDto.md)| Payment intent details | 

### Return type

[**PaymentIntentResponseDto**](PaymentIntentResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Payment intent created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**402** | Payment declined |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_payment_intents**
> ListPaymentIntentsResponseDto list_payment_intents(merchant_id=merchant_id, limit=limit, offset=offset, status=status)

List Payment Intents

Lists payment intents for a specific merchant with pagination and filtering.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_payment_intents_response_dto import ListPaymentIntentsResponseDto
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
    api_instance = cashful.PaymentIntentsApi(api_client)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant. If omitted, defaults to the authenticated merchant. (optional)
    limit = 50 # float | Maximum number of records to return (optional) (default to 50)
    offset = 0 # float | Number of records to skip (optional) (default to 0)
    status = 'status_example' # str | Filter by status (optional)

    try:
        # List Payment Intents
        api_response = api_instance.list_payment_intents(merchant_id=merchant_id, limit=limit, offset=offset, status=status)
        print("The response of PaymentIntentsApi->list_payment_intents:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentIntentsApi->list_payment_intents: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The ID of the merchant. If omitted, defaults to the authenticated merchant. | [optional] 
 **limit** | **float**| Maximum number of records to return | [optional] [default to 50]
 **offset** | **float**| Number of records to skip | [optional] [default to 0]
 **status** | **str**| Filter by status | [optional] 

### Return type

[**ListPaymentIntentsResponseDto**](ListPaymentIntentsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved payment intents |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **retrieve_payment_intent**
> PaymentIntentResponseDto retrieve_payment_intent(id)

Retrieve Payment Intent

Retrieves the current state of a specific payment intent.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.payment_intent_response_dto import PaymentIntentResponseDto
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
    api_instance = cashful.PaymentIntentsApi(api_client)
    id = 'id_example' # str | The unique identifier of the payment intent

    try:
        # Retrieve Payment Intent
        api_response = api_instance.retrieve_payment_intent(id)
        print("The response of PaymentIntentsApi->retrieve_payment_intent:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentIntentsApi->retrieve_payment_intent: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the payment intent | 

### Return type

[**PaymentIntentResponseDto**](PaymentIntentResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved payment intent |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

