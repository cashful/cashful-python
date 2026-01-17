# cashful.ProductsApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_product**](ProductsApi.md#create_product) | **POST** /api/canary/products | Create Product
[**list_products**](ProductsApi.md#list_products) | **GET** /api/canary/products | List Products
[**retrieve_product**](ProductsApi.md#retrieve_product) | **GET** /api/canary/products/{id} | Retrieve Product
[**update_product**](ProductsApi.md#update_product) | **PATCH** /api/canary/products/{id} | Update Product


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

# **list_products**
> ListProductsResponseDto list_products(merchant_id, limit=limit, offset=offset, active=active)

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
    merchant_id = 'merchant_id_example' # str | The ID of the merchant. This parameter is required.
    limit = 50 # float | Maximum number of records to return (optional)
    offset = 0 # float | Number of records to skip (optional)
    active = True # bool | Filter by active status (optional)

    try:
        # List Products
        api_response = api_instance.list_products(merchant_id, limit=limit, offset=offset, active=active)
        print("The response of ProductsApi->list_products:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ProductsApi->list_products: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The ID of the merchant. This parameter is required. | 
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 
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

