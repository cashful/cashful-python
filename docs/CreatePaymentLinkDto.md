# CreatePaymentLinkDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant whose balance is being requested. If omitted, defaults to the authenticated merchant. | [optional] 
**product_id** | **str** | The unique identifier of the product | [optional] 
**customer_id** | **str** | The unique identifier of the customer | [optional] 
**amount** | **float** | The amount in the smallest currency unit | [optional] 
**currency** | **str** | The three-letter ISO 4217 currency code | 
**mode** | **str** | The payment mode (e.g., &#39;payment&#39; or &#39;subscription&#39;) | 
**success_url** | **str** | The URL to redirect to on successful payment | 
**cancel_url** | **str** | The URL to redirect to if customer cancels | 
**metadata** | **Dict[str, object]** | Optional custom metadata | 

## Example

```python
from cashful.models.create_payment_link_dto import CreatePaymentLinkDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePaymentLinkDto from a JSON string
create_payment_link_dto_instance = CreatePaymentLinkDto.from_json(json)
# print the JSON string representation of the object
print(CreatePaymentLinkDto.to_json())

# convert the object into a dict
create_payment_link_dto_dict = create_payment_link_dto_instance.to_dict()
# create an instance of CreatePaymentLinkDto from a dict
create_payment_link_dto_from_dict = CreatePaymentLinkDto.from_dict(create_payment_link_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


