# cashful.ProductsApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_product**](ProductsApi.md#create_product) | **POST** /api/canary/products | Create Product
[**delete_product**](ProductsApi.md#delete_product) | **DELETE** /api/canary/products/{id} | Delete Product
[**delete_products_bulk**](ProductsApi.md#delete_products_bulk) | **DELETE** /api/canary/products/bulk | Bulk Delete Products
[**list_products**](ProductsApi.md#list_products) | **GET** /api/canary/products | List Products
[**retrieve_product**](ProductsApi.md#retrieve_product) | **GET** /api/canary/products/{id} | Retrieve Product
[**update_product**](ProductsApi.md#update_product) | **PATCH** /api/canary/products/{id} | Update Product
[**update_products_bulk**](ProductsApi.md#update_products_bulk) | **PATCH** /api/canary/products/bulk | Bulk Update Products


# **create_product**
> ProductResponseDto create_product(create_product_dto)

Create Product

Defines a product in the merchant's catalog (e.g., "Airtime," "Data").

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_product_dto import CreateProductDto
from cashful.models.product_response_dto import ProductResponseDto
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
    api_instance = cashful.ProductsApi(api_client)
    create_product_dto = cashful.CreateProductDto() # CreateProductDto | Product details

    try:
        # Create Product
        api_response = api_instance.create_product(create_product_dto)
        print("The response of ProductsApi->create_product:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ProductsApi->create_product: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_product_dto** | [**CreateProductDto**](CreateProductDto.md)| Product details | 

### Return type

[**ProductResponseDto**](ProductResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Product created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_product**
> ProductResponseDto delete_product(id)

Delete Product

Deletes a product by ID.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.product_response_dto import ProductResponseDto
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
    api_instance = cashful.ProductsApi(api_client)
    id = 'id_example' # str | The unique identifier of the product

    try:
        # Delete Product
        api_response = api_instance.delete_product(id)
        print("The response of ProductsApi->delete_product:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ProductsApi->delete_product: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the product | 

### Return type

[**ProductResponseDto**](ProductResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Product deleted successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_products_bulk**
> object delete_products_bulk(bulk_ids_dto)

Bulk Delete Products

Deletes multiple products by ID.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.bulk_ids_dto import BulkIdsDto
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
    api_instance = cashful.ProductsApi(api_client)
    bulk_ids_dto = cashful.BulkIdsDto() # BulkIdsDto | 

    try:
        # Bulk Delete Products
        api_response = api_instance.delete_products_bulk(bulk_ids_dto)
        print("The response of ProductsApi->delete_products_bulk:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ProductsApi->delete_products_bulk: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulk_ids_dto** | [**BulkIdsDto**](BulkIdsDto.md)|  | 

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
**200** | Products deleted successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_products**
> ListProductsResponseDto list_products(limit=limit, offset=offset, filter=filter, sort=sort, order=order, merchant_id=merchant_id, active=active)

List Products

Retrieves all products in the merchant's catalog.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_products_response_dto import ListProductsResponseDto
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
    api_instance = cashful.ProductsApi(api_client)
    limit = 50 # float | Maximum number of items to return (optional)
    offset = 0 # float | Number of items to skip (optional)
    filter = '{\"ids\":[\"prod_123\",\"prod_456\"]}' # str | JSON string used for dynamic filtering (optional)
    sort = 'createdAt' # str | Field name to sort by (optional)
    order = 'DESC' # str | Sort direction (optional)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant whose products are being requested. If not provided, the products of the authenticated merchant will be returned. (optional)
    active = True # bool | Filter by active status (optional)

    try:
        # List Products
        api_response = api_instance.list_products(limit=limit, offset=offset, filter=filter, sort=sort, order=order, merchant_id=merchant_id, active=active)
        print("The response of ProductsApi->list_products:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ProductsApi->list_products: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float**| Maximum number of items to return | [optional] 
 **offset** | **float**| Number of items to skip | [optional] 
 **filter** | **str**| JSON string used for dynamic filtering | [optional] 
 **sort** | **str**| Field name to sort by | [optional] 
 **order** | **str**| Sort direction | [optional] 
 **merchant_id** | **str**| The ID of the merchant whose products are being requested. If not provided, the products of the authenticated merchant will be returned. | [optional] 
 **active** | **bool**| Filter by active status | [optional] 

### Return type

[**ListProductsResponseDto**](ListProductsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved products |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **retrieve_product**
> ProductResponseDto retrieve_product(id)

Retrieve Product

Retrieves a single product by ID.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.product_response_dto import ProductResponseDto
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
    api_instance = cashful.ProductsApi(api_client)
    id = 'id_example' # str | The unique identifier of the product

    try:
        # Retrieve Product
        api_response = api_instance.retrieve_product(id)
        print("The response of ProductsApi->retrieve_product:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ProductsApi->retrieve_product: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the product | 

### Return type

[**ProductResponseDto**](ProductResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved product |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_product**
> ProductResponseDto update_product(id, update_product_dto)

Update Product

Updates a product's name, description, or metadata.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.product_response_dto import ProductResponseDto
from cashful.models.update_product_dto import UpdateProductDto
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
    api_instance = cashful.ProductsApi(api_client)
    id = 'id_example' # str | The unique identifier of the product
    update_product_dto = cashful.UpdateProductDto() # UpdateProductDto | Product update details

    try:
        # Update Product
        api_response = api_instance.update_product(id, update_product_dto)
        print("The response of ProductsApi->update_product:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ProductsApi->update_product: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The unique identifier of the product | 
 **update_product_dto** | [**UpdateProductDto**](UpdateProductDto.md)| Product update details | 

### Return type

[**ProductResponseDto**](ProductResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Product updated successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_products_bulk**
> object update_products_bulk(bulk_update_products_input_dto)

Bulk Update Products

Updates multiple products using a shared patch.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.bulk_update_products_input_dto import BulkUpdateProductsInputDto
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
    api_instance = cashful.ProductsApi(api_client)
    bulk_update_products_input_dto = cashful.BulkUpdateProductsInputDto() # BulkUpdateProductsInputDto | 

    try:
        # Bulk Update Products
        api_response = api_instance.update_products_bulk(bulk_update_products_input_dto)
        print("The response of ProductsApi->update_products_bulk:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ProductsApi->update_products_bulk: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulk_update_products_input_dto** | [**BulkUpdateProductsInputDto**](BulkUpdateProductsInputDto.md)|  | 

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
**200** | Products updated successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

