# cashful.PurchasesApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_purchase**](PurchasesApi.md#create_purchase) | **POST** /api/canary/purchases | Buy with Cash Balance


# **create_purchase**
> PurchaseResponseDto create_purchase(create_purchase_dto)

Buy with Cash Balance

(Wallet-Enabling) Spends a product using the CustomerBalance as the source. Atomically debits the CustomerBalance and credits the MerchantBalance.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_purchase_dto import CreatePurchaseDto
from cashful.models.purchase_response_dto import PurchaseResponseDto
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
    api_instance = cashful.PurchasesApi(api_client)
    create_purchase_dto = cashful.CreatePurchaseDto() # CreatePurchaseDto | Purchase details

    try:
        # Buy with Cash Balance
        api_response = api_instance.create_purchase(create_purchase_dto)
        print("The response of PurchasesApi->create_purchase:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PurchasesApi->create_purchase: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_purchase_dto** | [**CreatePurchaseDto**](CreatePurchaseDto.md)| Purchase details | 

### Return type

[**PurchaseResponseDto**](PurchaseResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Purchase created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**402** | Insufficient customer balance |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

