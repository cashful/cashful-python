# cashful.EventsApi

All URIs are relative to *https://api.cashful.africa*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_event**](EventsApi.md#create_event) | **POST** /api/canary/events | Create Event
[**list_event_types**](EventsApi.md#list_event_types) | **GET** /api/canary/events/types | List Event Types
[**list_events**](EventsApi.md#list_events) | **GET** /api/canary/events | List Events


# **create_event**
> create_event(create_event_dto)

Create Event

Records a new event and triggers associated webhooks.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_event_dto import CreateEventDto
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
    api_instance = cashful.EventsApi(api_client)
    create_event_dto = cashful.CreateEventDto() # CreateEventDto | 

    try:
        # Create Event
        api_instance.create_event(create_event_dto)
    except Exception as e:
        print("Exception when calling EventsApi->create_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_event_dto** | [**CreateEventDto**](CreateEventDto.md)|  | 

### Return type

void (empty response body)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Event successfully created |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_event_types**
> ListEventTypesResponseDto list_event_types()

List Event Types

Retrieves all available event types that can be sent or subscribed to.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_event_types_response_dto import ListEventTypesResponseDto
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
    api_instance = cashful.EventsApi(api_client)

    try:
        # List Event Types
        api_response = api_instance.list_event_types()
        print("The response of EventsApi->list_event_types:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EventsApi->list_event_types: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**ListEventTypesResponseDto**](ListEventTypesResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved event types |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_events**
> ListEventsResponseDto list_events(merchant_id, limit=limit, offset=offset, filter=filter, sort=sort, order=order, type=type, status=status, start_date=start_date, end_date=end_date)

List Events

Retrieves a log of all API events for debugging and logging.

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_events_response_dto import ListEventsResponseDto
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
    api_instance = cashful.EventsApi(api_client)
    merchant_id = 'merchant_id_example' # str | The ID of the merchant whose events are being requested. This parameter is required.
    limit = 50 # float | Maximum number of records to return (optional)
    offset = 0 # float | Number of records to skip (optional)
    filter = '{\"ids\":[\"prod_123\",\"prod_456\"]}' # str | JSON string used for dynamic filtering (optional)
    sort = 'createdAt' # str | Field name to sort by (optional)
    order = 'DESC' # str | Sort direction (ASC or DESC) (optional)
    type = 'type_example' # str | Filter by event type (optional)
    status = 'status_example' # str | Filter by event status (optional)
    start_date = 'start_date_example' # str | Filter by start date (optional)
    end_date = 'end_date_example' # str | Filter by end date (optional)

    try:
        # List Events
        api_response = api_instance.list_events(merchant_id, limit=limit, offset=offset, filter=filter, sort=sort, order=order, type=type, status=status, start_date=start_date, end_date=end_date)
        print("The response of EventsApi->list_events:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling EventsApi->list_events: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **merchant_id** | **str**| The ID of the merchant whose events are being requested. This parameter is required. | 
 **limit** | **float**| Maximum number of records to return | [optional] 
 **offset** | **float**| Number of records to skip | [optional] 
 **filter** | **str**| JSON string used for dynamic filtering | [optional] 
 **sort** | **str**| Field name to sort by | [optional] 
 **order** | **str**| Sort direction (ASC or DESC) | [optional] 
 **type** | **str**| Filter by event type | [optional] 
 **status** | **str**| Filter by event status | [optional] 
 **start_date** | **str**| Filter by start date | [optional] 
 **end_date** | **str**| Filter by end date | [optional] 

### Return type

[**ListEventsResponseDto**](ListEventsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved events |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

