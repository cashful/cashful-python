# cashful.BalanceApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_balance_history**](BalanceApi.md#get_balance_history) | **GET** /api/canary/balance/history | List Merchant Balance History
[**get_merchant_balance**](BalanceApi.md#get_merchant_balance) | **GET** /api/canary/balance | Get Merchant Balance


# **get_balance_history**
> BalanceHistoryResponseDto get_balance_history(merchant_id, limit=limit, offset=offset, start_date=start_date, end_date=end_date, transaction_type=transaction_type)

List Merchant Balance History

A full ledger of all transactions, fees, and payouts for the merchant's master account.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.balance_history_response_dto import BalanceHistoryResponseDto
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
    api_instance = cashful.BalanceApi(api_client)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant. This parameter is required.
    limit = 3.4 # float | Maximum number of records to return (optional)
    offset = 3.4 # float | Number of records to skip (optional)
    start_date = 'start_date_example' # str | Filter transactions from this date (ISO 8601 format) (optional)
    end_date = 'end_date_example' # str | Filter transactions until this date (ISO 8601 format) (optional)
    transaction_type = 'transaction_type_example' # str | Filter by transaction type (e.g., \"credit\", \"debit\", \"fee\", \"payout\") (optional)

    try:
        # List Merchant Balance History
        api_response = api_instance.get_balance_history(merchant_id, limit=limit, offset=offset, start_date=start_date, end_date=end_date, transaction_type=transaction_type)
        print("The response of BalanceApi->get_balance_history:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling BalanceApi->get_balance_history: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The ID of the merchant. This parameter is required. | 
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 
 **start_date** | **str**| Filter transactions from this date (ISO 8601 format) | [optional] 
 **end_date** | **str**| Filter transactions until this date (ISO 8601 format) | [optional] 
 **transaction_type** | **str**| Filter by transaction type (e.g., \&quot;credit\&quot;, \&quot;debit\&quot;, \&quot;fee\&quot;, \&quot;payout\&quot;) | [optional] 

### Return type

[**BalanceHistoryResponseDto**](BalanceHistoryResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved balance history |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_merchant_balance**
> MerchantBalanceResponseDto get_merchant_balance(merchant_id)

Get Merchant Balance

Retrieves the merchant's own master balance (their earnings) available for payouts.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.merchant_balance_response_dto import MerchantBalanceResponseDto
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
    api_instance = cashful.BalanceApi(api_client)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant whose balance is being requested.

    try:
        # Get Merchant Balance
        api_response = api_instance.get_merchant_balance(merchant_id)
        print("The response of BalanceApi->get_merchant_balance:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling BalanceApi->get_merchant_balance: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The ID of the merchant whose balance is being requested. | 

### Return type

[**MerchantBalanceResponseDto**](MerchantBalanceResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved merchant balance |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

