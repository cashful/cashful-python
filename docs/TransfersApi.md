# cashful.TransfersApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_transfer**](TransfersApi.md#create_transfer) | **POST** /api/canary/transfers | Create P2P Transfer


# **create_transfer**
> TransferResponseDto create_transfer(create_transfer_dto)

Create P2P Transfer

(Wallet-Enabling) Moves funds from one CustomerBalance to another CustomerBalance. This is the P2P feature.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_transfer_dto import CreateTransferDto
from cashful.models.transfer_response_dto import TransferResponseDto
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
    api_instance = cashful.TransfersApi(api_client)
    create_transfer_dto = cashful.CreateTransferDto() # CreateTransferDto | Transfer details

    try:
        # Create P2P Transfer
        api_response = api_instance.create_transfer(create_transfer_dto)
        print("The response of TransfersApi->create_transfer:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling TransfersApi->create_transfer: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_transfer_dto** | [**CreateTransferDto**](CreateTransferDto.md)| Transfer details | 

### Return type

[**TransferResponseDto**](TransferResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Transfer created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**402** | Insufficient sender balance |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

