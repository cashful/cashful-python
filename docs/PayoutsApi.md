# cashful.PayoutsApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_payout**](PayoutsApi.md#create_payout) | **POST** /api/canary/payouts | Create Payout
[**list_payouts**](PayoutsApi.md#list_payouts) | **GET** /api/canary/payouts | List Payouts


# **create_payout**
> PayoutResponseDto create_payout(create_payout_dto)

Create Payout

Allows the merchant to move funds from their MerchantBalance (their earnings) to their external bank account.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_payout_dto import CreatePayoutDto
from cashful.models.payout_response_dto import PayoutResponseDto
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
    api_instance = cashful.PayoutsApi(api_client)
    create_payout_dto = cashful.CreatePayoutDto() # CreatePayoutDto | Payout details

    try:
        # Create Payout
        api_response = api_instance.create_payout(create_payout_dto)
        print("The response of PayoutsApi->create_payout:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PayoutsApi->create_payout: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_payout_dto** | [**CreatePayoutDto**](CreatePayoutDto.md)| Payout details | 

### Return type

[**PayoutResponseDto**](PayoutResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Payout created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**402** | Insufficient merchant balance |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_payouts**
> ListPayoutsResponseDto list_payouts(merchant_id=merchant_id, limit=limit, offset=offset, status=status)

List Payouts

Retrieves a list of all historical and pending payouts for the merchant.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_payouts_response_dto import ListPayoutsResponseDto
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
    api_instance = cashful.PayoutsApi(api_client)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant whose payouts are being requested. If omitted, defaults to the authenticated merchant. (optional)
    limit = 3.4 # float | Maximum number of records to return (optional)
    offset = 3.4 # float | Number of records to skip (optional)
    status = 'status_example' # str | Filter by status (optional)

    try:
        # List Payouts
        api_response = api_instance.list_payouts(merchant_id=merchant_id, limit=limit, offset=offset, status=status)
        print("The response of PayoutsApi->list_payouts:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PayoutsApi->list_payouts: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The ID of the merchant whose payouts are being requested. If omitted, defaults to the authenticated merchant. | [optional] 
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 
 **status** | **str**| Filter by status | [optional] 

### Return type

[**ListPayoutsResponseDto**](ListPayoutsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved payouts |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

