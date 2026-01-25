# cashful.StorageApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**storage_controller_confirm_upload_canary**](StorageApi.md#storage_controller_confirm_upload_canary) | **POST** /api/canary/storage/confirm-upload | Confirm that a file upload was completed
[**storage_controller_delete_canary**](StorageApi.md#storage_controller_delete_canary) | **DELETE** /api/canary/storage/{id} | Delete a file
[**storage_controller_get_download_url_canary**](StorageApi.md#storage_controller_get_download_url_canary) | **GET** /api/canary/storage/{id}/download-url | Get a presigned download URL for a file
[**storage_controller_list_canary**](StorageApi.md#storage_controller_list_canary) | **GET** /api/canary/storage | List files
[**storage_controller_request_upload_url_canary**](StorageApi.md#storage_controller_request_upload_url_canary) | **POST** /api/canary/storage/upload-url | Request a presigned URL for file upload
[**storage_controller_retrieve_canary**](StorageApi.md#storage_controller_retrieve_canary) | **GET** /api/canary/storage/{id} | Get file details


# **storage_controller_confirm_upload_canary**
> FileDto storage_controller_confirm_upload_canary(confirm_upload_dto)

Confirm that a file upload was completed

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.confirm_upload_dto import ConfirmUploadDto
from cashful.models.file_dto import FileDto
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
    api_instance = cashful.StorageApi(api_client)
    confirm_upload_dto = {"fileId":"file_abc123xyz","checksum":"sha256:a1b2c3d4e5f6...","size":245760} # ConfirmUploadDto | 

    try:
        # Confirm that a file upload was completed
        api_response = api_instance.storage_controller_confirm_upload_canary(confirm_upload_dto)
        print("The response of StorageApi->storage_controller_confirm_upload_canary:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling StorageApi->storage_controller_confirm_upload_canary: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **confirm_upload_dto** | [**ConfirmUploadDto**](ConfirmUploadDto.md)|  | 

### Return type

[**FileDto**](FileDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** |  |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_controller_delete_canary**
> storage_controller_delete_canary(id)

Delete a file

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
    api_instance = cashful.StorageApi(api_client)
    id = 'id_example' # str | File ID

    try:
        # Delete a file
        api_instance.storage_controller_delete_canary(id)
    except Exception as e:
        print("Exception when calling StorageApi->storage_controller_delete_canary: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| File ID | 

### Return type

void (empty response body)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** |  |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_controller_get_download_url_canary**
> PresignedDownloadResponseDto storage_controller_get_download_url_canary(id)

Get a presigned download URL for a file

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.presigned_download_response_dto import PresignedDownloadResponseDto
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
    api_instance = cashful.StorageApi(api_client)
    id = 'id_example' # str | File ID

    try:
        # Get a presigned download URL for a file
        api_response = api_instance.storage_controller_get_download_url_canary(id)
        print("The response of StorageApi->storage_controller_get_download_url_canary:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling StorageApi->storage_controller_get_download_url_canary: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| File ID | 

### Return type

[**PresignedDownloadResponseDto**](PresignedDownloadResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** |  |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_controller_list_canary**
> ListFilesResponseDto storage_controller_list_canary(limit=limit, offset=offset, tag=tag, status=status, related_entity_id=related_entity_id, related_entity_type=related_entity_type)

List files

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_files_response_dto import ListFilesResponseDto
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
    api_instance = cashful.StorageApi(api_client)
    limit = 50 # float | Maximum number of records to return (optional)
    offset = 0 # float | Number of records to skip (optional)
    tag = 'tag_example' # str | Filter by tag (optional)
    status = 'status_example' # str |  (optional)
    related_entity_id = 'related_entity_id_example' # str |  (optional)
    related_entity_type = 'related_entity_type_example' # str |  (optional)

    try:
        # List files
        api_response = api_instance.storage_controller_list_canary(limit=limit, offset=offset, tag=tag, status=status, related_entity_id=related_entity_id, related_entity_type=related_entity_type)
        print("The response of StorageApi->storage_controller_list_canary:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling StorageApi->storage_controller_list_canary: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 
 **tag** | **str**| Filter by tag | [optional] 
 **status** | **str**|  | [optional] 
 **related_entity_id** | **str**|  | [optional] 
 **related_entity_type** | **str**|  | [optional] 

### Return type

[**ListFilesResponseDto**](ListFilesResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** |  |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_controller_request_upload_url_canary**
> PresignedUploadResponseDto storage_controller_request_upload_url_canary(request_upload_url_dto)

Request a presigned URL for file upload

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.presigned_upload_response_dto import PresignedUploadResponseDto
from cashful.models.request_upload_url_dto import RequestUploadUrlDto
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
    api_instance = cashful.StorageApi(api_client)
    request_upload_url_dto = {"filename":"iphone-15.png","mimeType":"image/png","isPublic":true,"tags":["product","image"],"relatedEntityId":"product_123","relatedEntityType":"product"} # RequestUploadUrlDto | 

    try:
        # Request a presigned URL for file upload
        api_response = api_instance.storage_controller_request_upload_url_canary(request_upload_url_dto)
        print("The response of StorageApi->storage_controller_request_upload_url_canary:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling StorageApi->storage_controller_request_upload_url_canary: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request_upload_url_dto** | [**RequestUploadUrlDto**](RequestUploadUrlDto.md)|  | 

### Return type

[**PresignedUploadResponseDto**](PresignedUploadResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** |  |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_controller_retrieve_canary**
> FileDto storage_controller_retrieve_canary(id)

Get file details

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.file_dto import FileDto
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
    api_instance = cashful.StorageApi(api_client)
    id = 'id_example' # str | File ID

    try:
        # Get file details
        api_response = api_instance.storage_controller_retrieve_canary(id)
        print("The response of StorageApi->storage_controller_retrieve_canary:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling StorageApi->storage_controller_retrieve_canary: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| File ID | 

### Return type

[**FileDto**](FileDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** |  |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

