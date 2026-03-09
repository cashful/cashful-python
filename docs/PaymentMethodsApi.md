# cashful.PaymentMethodsApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**delete_payment_method**](PaymentMethodsApi.md#delete_payment_method) | **DELETE** /api/canary/payment-methods/{id} | Delete Payment Method
[**list_payment_methods**](PaymentMethodsApi.md#list_payment_methods) | **GET** /api/canary/payment-methods | List Payment Methods
[**retrieve_payment_method**](PaymentMethodsApi.md#retrieve_payment_method) | **GET** /api/canary/payment-methods/{id} | Retrieve Payment Method


# **delete_payment_method**
> object delete_payment_method(id)

Delete Payment Method

Detaches and deletes a saved payment method from a customer.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
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
    api_instance = cashful.PaymentMethodsApi(api_client)
    id = 'id_example' # str | The unique identifier of the payment method

    try:
        # Delete Payment Method
        api_response = api_instance.delete_payment_method(id)
        print("The response of PaymentMethodsApi->delete_payment_method:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentMethodsApi->delete_payment_method: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the payment method | 

### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Payment method successfully deleted |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_payment_methods**
> ListPaymentMethodsResponseDto list_payment_methods(limit=limit, offset=offset, filter=filter, sort=sort, order=order, merchant_id=merchant_id, customer_id=customer_id)

List Payment Methods

Lists saved payment methods for a specific customer.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_payment_methods_response_dto import ListPaymentMethodsResponseDto
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
    api_instance = cashful.PaymentMethodsApi(api_client)
    limit = 50 # float | Maximum number of items to return (optional)
    offset = 0 # float | Number of items to skip (optional)
    filter = '{\"ids\":[\"prod_123\",\"prod_456\"]}' # str | JSON string used for dynamic filtering (optional)
    sort = 'createdAt' # str | Field name to sort by (optional)
    order = 'DESC' # str | Sort direction (optional)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant. If omitted, defaults to the authenticated merchant. (optional)
    customer_id = 'customer_id_example' # str | Customer ID to filter by (optional)

    try:
        # List Payment Methods
        api_response = api_instance.list_payment_methods(limit=limit, offset=offset, filter=filter, sort=sort, order=order, merchant_id=merchant_id, customer_id=customer_id)
        print("The response of PaymentMethodsApi->list_payment_methods:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentMethodsApi->list_payment_methods: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float**| Maximum number of items to return | [optional] 
 **offset** | **float**| Number of items to skip | [optional] 
 **filter** | **str**| JSON string used for dynamic filtering | [optional] 
 **sort** | **str**| Field name to sort by | [optional] 
 **order** | **str**| Sort direction | [optional] 
 **merchant_id** | **str**| The ID of the merchant. If omitted, defaults to the authenticated merchant. | [optional] 
 **customer_id** | **str**| Customer ID to filter by | [optional] 

### Return type

[**ListPaymentMethodsResponseDto**](ListPaymentMethodsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved payment methods list |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **retrieve_payment_method**
> PaymentMethodResponseDto retrieve_payment_method(id)

Retrieve Payment Method

Gets the non-sensitive details of a saved card (e.g., brand, last 4).

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.payment_method_response_dto import PaymentMethodResponseDto
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
    api_instance = cashful.PaymentMethodsApi(api_client)
    id = 'id_example' # str | The unique identifier of the payment method

    try:
        # Retrieve Payment Method
        api_response = api_instance.retrieve_payment_method(id)
        print("The response of PaymentMethodsApi->retrieve_payment_method:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentMethodsApi->retrieve_payment_method: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the payment method | 

### Return type

[**PaymentMethodResponseDto**](PaymentMethodResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved payment method details |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

