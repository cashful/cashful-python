# cashful.CustomersApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_customer**](CustomersApi.md#create_customer) | **POST** /api/canary/customers | Create Customer
[**get_customer_balance**](CustomersApi.md#get_customer_balance) | **GET** /api/canary/customers/{id}/balance | Get Customer&#39;s Cash Balance
[**list_customer_payment_methods**](CustomersApi.md#list_customer_payment_methods) | **GET** /api/canary/customers/{id}/payment-methods | List Customer&#39;s Payment Methods
[**list_customer_transactions**](CustomersApi.md#list_customer_transactions) | **GET** /api/canary/customers/{id}/transactions | List Customer&#39;s Cash Transactions
[**list_customers**](CustomersApi.md#list_customers) | **GET** /api/canary/customers | List Customers
[**retrieve_customer**](CustomersApi.md#retrieve_customer) | **GET** /api/canary/customers/{id} | Retrieve Customer
[**update_customer**](CustomersApi.md#update_customer) | **PATCH** /api/canary/customers/{id} | Update Customer


# **create_customer**
> CustomerResponseDto create_customer(create_customer_dto)

Create Customer

Creates a new customer object. This also provisions their "cash balance" feature (starting at 0).

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_customer_dto import CreateCustomerDto
from cashful.models.customer_response_dto import CustomerResponseDto
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
    api_instance = cashful.CustomersApi(api_client)
    create_customer_dto = cashful.CreateCustomerDto() # CreateCustomerDto | Customer details

    try:
        # Create Customer
        api_response = api_instance.create_customer(create_customer_dto)
        print("The response of CustomersApi->create_customer:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomersApi->create_customer: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_customer_dto** | [**CreateCustomerDto**](CreateCustomerDto.md)| Customer details | 

### Return type

[**CustomerResponseDto**](CustomerResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Customer created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**409** | Customer with this email already exists |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_customer_balance**
> object get_customer_balance(id)

Get Customer's Cash Balance

Retrieves the real-time balance for a single customer's "cash balance" (the "wallet-enabling" feature).

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
    api_instance = cashful.CustomersApi(api_client)
    id = 'id_example' # str | The unique identifier of the customer

    try:
        # Get Customer's Cash Balance
        api_response = api_instance.get_customer_balance(id)
        print("The response of CustomersApi->get_customer_balance:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomersApi->get_customer_balance: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the customer | 

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
**200** | Successfully retrieved customer&#39;s cash balance |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_customer_payment_methods**
> object list_customer_payment_methods(id, limit=limit, offset=offset)

List Customer's Payment Methods

Shows all saved payment methods (cards, etc.) for a single customer.

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
    api_instance = cashful.CustomersApi(api_client)
    id = 'id_example' # str | The unique identifier of the customer
    limit = 3.4 # float | Maximum number of records to return (optional)
    offset = 3.4 # float | Number of records to skip (optional)

    try:
        # List Customer's Payment Methods
        api_response = api_instance.list_customer_payment_methods(id, limit=limit, offset=offset)
        print("The response of CustomersApi->list_customer_payment_methods:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomersApi->list_customer_payment_methods: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the customer | 
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 

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
**200** | Successfully retrieved customer&#39;s payment methods |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_customer_transactions**
> ListCustomerTransactionsResponseDto list_customer_transactions(id, limit=limit, offset=offset)

List Customer's Cash Transactions

Provides the full transaction history for a single customer's "cash balance" (Pay-Ins, Purchases, Transfers).

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_customer_transactions_response_dto import ListCustomerTransactionsResponseDto
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
    api_instance = cashful.CustomersApi(api_client)
    id = 'id_example' # str | The unique identifier of the customer
    limit = 3.4 # float | Maximum number of records to return (optional)
    offset = 3.4 # float | Number of records to skip (optional)

    try:
        # List Customer's Cash Transactions
        api_response = api_instance.list_customer_transactions(id, limit=limit, offset=offset)
        print("The response of CustomersApi->list_customer_transactions:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomersApi->list_customer_transactions: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the customer | 
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 

### Return type

[**ListCustomerTransactionsResponseDto**](ListCustomerTransactionsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved customer transactions |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_customers**
> ListCustomersResponseDto list_customers(merchant_id, limit=limit, offset=offset, email=email, search=search)

List Customers

Retrieves a paginated list of all customers for the merchant.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_customers_response_dto import ListCustomersResponseDto
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
    api_instance = cashful.CustomersApi(api_client)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant. This parameter is required.
    limit = 3.4 # float | Maximum number of records to return (optional)
    offset = 3.4 # float | Number of records to skip (optional)
    email = 'email_example' # str | Filter by email address (optional)
    search = 'search_example' # str | Search across customer fields (optional)

    try:
        # List Customers
        api_response = api_instance.list_customers(merchant_id, limit=limit, offset=offset, email=email, search=search)
        print("The response of CustomersApi->list_customers:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomersApi->list_customers: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The ID of the merchant. This parameter is required. | 
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 
 **email** | **str**| Filter by email address | [optional] 
 **search** | **str**| Search across customer fields | [optional] 

### Return type

[**ListCustomersResponseDto**](ListCustomersResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved customers list |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **retrieve_customer**
> object retrieve_customer(id)

Retrieve Customer

Gets the details for a single customer.

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
    api_instance = cashful.CustomersApi(api_client)
    id = 'id_example' # str | The unique identifier of the customer

    try:
        # Retrieve Customer
        api_response = api_instance.retrieve_customer(id)
        print("The response of CustomersApi->retrieve_customer:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomersApi->retrieve_customer: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the customer | 

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
**200** | Successfully retrieved customer details |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_customer**
> object update_customer(id, update_customer_dto)

Update Customer

Updates a customer's details (e.g., email, metadata).

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.update_customer_dto import UpdateCustomerDto
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
    api_instance = cashful.CustomersApi(api_client)
    id = 'id_example' # str | The unique identifier of the customer
    update_customer_dto = cashful.UpdateCustomerDto() # UpdateCustomerDto | Customer update details

    try:
        # Update Customer
        api_response = api_instance.update_customer(id, update_customer_dto)
        print("The response of CustomersApi->update_customer:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomersApi->update_customer: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the customer | 
 **update_customer_dto** | [**UpdateCustomerDto**](UpdateCustomerDto.md)| Customer update details | 

### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Customer updated successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**409** | Email already in use by another customer |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

