# ListPaymentLinksResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PaymentLinkResponseDto]**](PaymentLinkResponseDto.md) |  | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) |  | 

## Example

```python
from cashful.models.list_payment_links_response_dto import ListPaymentLinksResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListPaymentLinksResponseDto from a JSON string
list_payment_links_response_dto_instance = ListPaymentLinksResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListPaymentLinksResponseDto.to_json())

# convert the object into a dict
list_payment_links_response_dto_dict = list_payment_links_response_dto_instance.to_dict()
# create an instance of ListPaymentLinksResponseDto from a dict
list_payment_links_response_dto_from_dict = ListPaymentLinksResponseDto.from_dict(list_payment_links_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


