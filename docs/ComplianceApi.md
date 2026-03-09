# cashful.ComplianceApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_compliance**](ComplianceApi.md#create_compliance) | **POST** /api/canary/compliance | Create Compliance info
[**list_compliance**](ComplianceApi.md#list_compliance) | **GET** /api/canary/compliance | List Compliance info for organization
[**update_compliance**](ComplianceApi.md#update_compliance) | **PATCH** /api/canary/compliance/{id} | Update Compliance info


# **create_compliance**
> OrganizationComplianceResponseDto create_compliance(create_organization_compliance_dto)

Create Compliance info

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_organization_compliance_dto import CreateOrganizationComplianceDto
from cashful.models.organization_compliance_response_dto import OrganizationComplianceResponseDto
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
    api_instance = cashful.ComplianceApi(api_client)
    create_organization_compliance_dto = cashful.CreateOrganizationComplianceDto() # CreateOrganizationComplianceDto | 

    try:
        # Create Compliance info
        api_response = api_instance.create_compliance(create_organization_compliance_dto)
        print("The response of ComplianceApi->create_compliance:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ComplianceApi->create_compliance: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_organization_compliance_dto** | [**CreateOrganizationComplianceDto**](CreateOrganizationComplianceDto.md)|  | 

### Return type

[**OrganizationComplianceResponseDto**](OrganizationComplianceResponseDto.md)

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
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_compliance**
> ListOrganizationComplianceResponseDto list_compliance(limit=limit, offset=offset, filter=filter, sort=sort, order=order)

List Compliance info for organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_organization_compliance_response_dto import ListOrganizationComplianceResponseDto
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
    api_instance = cashful.ComplianceApi(api_client)
    limit = 50 # float | Maximum number of items to return (optional)
    offset = 0 # float | Number of items to skip (optional)
    filter = '{\"ids\":[\"prod_123\",\"prod_456\"]}' # str | JSON string used for dynamic filtering (optional)
    sort = 'createdAt' # str | Field name to sort by (optional)
    order = 'DESC' # str | Sort direction (optional)

    try:
        # List Compliance info for organization
        api_response = api_instance.list_compliance(limit=limit, offset=offset, filter=filter, sort=sort, order=order)
        print("The response of ComplianceApi->list_compliance:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ComplianceApi->list_compliance: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float**| Maximum number of items to return | [optional] 
 **offset** | **float**| Number of items to skip | [optional] 
 **filter** | **str**| JSON string used for dynamic filtering | [optional] 
 **sort** | **str**| Field name to sort by | [optional] 
 **order** | **str**| Sort direction | [optional] 

### Return type

[**ListOrganizationComplianceResponseDto**](ListOrganizationComplianceResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** |  |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_compliance**
> update_compliance(id, update_organization_compliance_dto)

Update Compliance info

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.update_organization_compliance_dto import UpdateOrganizationComplianceDto
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
    api_instance = cashful.ComplianceApi(api_client)
    id = 'id_example' # str | 
    update_organization_compliance_dto = cashful.UpdateOrganizationComplianceDto() # UpdateOrganizationComplianceDto | 

    try:
        # Update Compliance info
        api_instance.update_compliance(id, update_organization_compliance_dto)
    except Exception as e:
        print("Exception when calling ComplianceApi->update_compliance: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**|  | 
 **update_organization_compliance_dto** | [**UpdateOrganizationComplianceDto**](UpdateOrganizationComplianceDto.md)|  | 

### Return type

void (empty response body)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Compliance updated |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

