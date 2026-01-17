# cashful.PaymentLinksApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_payment_link**](PaymentLinksApi.md#create_payment_link) | **POST** /api/canary/payment-links | Create Payment Link
[**list_payment_links**](PaymentLinksApi.md#list_payment_links) | **GET** /api/canary/payment-links | List Payment Links
[**retrieve_payment_link**](PaymentLinksApi.md#retrieve_payment_link) | **GET** /api/canary/payment-links/{id} | Retrieve Payment Link
[**update_payment_link**](PaymentLinksApi.md#update_payment_link) | **PATCH** /api/canary/payment-links/{id} | Update Payment Link


# **create_payment_link**
> PaymentLinkResponseDto create_payment_link(create_payment_link_dto)

Create Payment Link

Creates a re-usable hosted link. Can be used for: (1) Selling a product, or (2) as a "Pay-In" link for a customer.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_payment_link_dto import CreatePaymentLinkDto
from cashful.models.payment_link_response_dto import PaymentLinkResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
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
    api_instance = cashful.PaymentLinksApi(api_client)
    create_payment_link_dto = cashful.CreatePaymentLinkDto() # CreatePaymentLinkDto | Payment link details

    try:
        # Create Payment Link
        api_response = api_instance.create_payment_link(create_payment_link_dto)
        print("The response of PaymentLinksApi->create_payment_link:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentLinksApi->create_payment_link: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_payment_link_dto** | [**CreatePaymentLinkDto**](CreatePaymentLinkDto.md)| Payment link details | 

### Return type

[**PaymentLinkResponseDto**](PaymentLinkResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Payment link created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_payment_links**
> ListPaymentLinksResponseDto list_payment_links(merchant_id, limit=limit, offset=offset, active=active)

List Payment Links

Retrieves all payment links created by the merchant.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_payment_links_response_dto import ListPaymentLinksResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
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
    api_instance = cashful.PaymentLinksApi(api_client)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant. This parameter is required.
    limit = 3.4 # float | Maximum number of records to return (optional)
    offset = 3.4 # float | Number of records to skip (optional)
    active = True # bool | Filter by active status (optional)

    try:
        # List Payment Links
        api_response = api_instance.list_payment_links(merchant_id, limit=limit, offset=offset, active=active)
        print("The response of PaymentLinksApi->list_payment_links:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentLinksApi->list_payment_links: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The ID of the merchant. This parameter is required. | 
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 
 **active** | **bool**| Filter by active status | [optional] 

### Return type

[**ListPaymentLinksResponseDto**](ListPaymentLinksResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved payment links |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **retrieve_payment_link**
> PaymentLinkResponseDto retrieve_payment_link(id)

Retrieve Payment Link

Retrieves a single payment link by ID.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.payment_link_response_dto import PaymentLinkResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
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
    api_instance = cashful.PaymentLinksApi(api_client)
    id = 'id_example' # str | The unique identifier of the payment link

    try:
        # Retrieve Payment Link
        api_response = api_instance.retrieve_payment_link(id)
        print("The response of PaymentLinksApi->retrieve_payment_link:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentLinksApi->retrieve_payment_link: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the payment link | 

### Return type

[**PaymentLinkResponseDto**](PaymentLinkResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Payment link retrieved successfully |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_payment_link**
> object update_payment_link(id, update_payment_link_dto)

Update Payment Link

Updates a link's details, most commonly to set active: false.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.update_payment_link_dto import UpdatePaymentLinkDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
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
    api_instance = cashful.PaymentLinksApi(api_client)
    id = 'id_example' # str | The unique identifier of the payment link
    update_payment_link_dto = cashful.UpdatePaymentLinkDto() # UpdatePaymentLinkDto | Payment link update details

    try:
        # Update Payment Link
        api_response = api_instance.update_payment_link(id, update_payment_link_dto)
        print("The response of PaymentLinksApi->update_payment_link:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PaymentLinksApi->update_payment_link: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the payment link | 
 **update_payment_link_dto** | [**UpdatePaymentLinkDto**](UpdatePaymentLinkDto.md)| Payment link update details | 

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
**200** | Payment link updated successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

