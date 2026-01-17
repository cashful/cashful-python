# ListCheckoutSessionsResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CheckoutSessionResponseDto]**](CheckoutSessionResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_checkout_sessions_response_dto import ListCheckoutSessionsResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListCheckoutSessionsResponseDto from a JSON string
list_checkout_sessions_response_dto_instance = ListCheckoutSessionsResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListCheckoutSessionsResponseDto.to_json())

# convert the object into a dict
list_checkout_sessions_response_dto_dict = list_checkout_sessions_response_dto_instance.to_dict()
# create an instance of ListCheckoutSessionsResponseDto from a dict
list_checkout_sessions_response_dto_from_dict = ListCheckoutSessionsResponseDto.from_dict(list_checkout_sessions_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


