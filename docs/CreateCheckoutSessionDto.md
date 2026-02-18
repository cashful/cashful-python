# CreateCheckoutSessionDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant for the checkout session. | 
**customer_id** | **str** | The unique identifier of the customer | [optional] 
**product_id** | **str** | The unique identifier of the product | [optional] 
**success_url** | **str** | The URL to redirect to on successful payment | [optional] 
**cancel_url** | **str** | The URL to redirect to on cancel | [optional] 
**line_items** | [**List[LineItemDto]**](LineItemDto.md) | Array of line items for the checkout | [optional] 
**total_amount** | **float** | The total amount in the smallest currency unit | [optional] 
**currency** | **str** | The three-letter ISO 4217 currency code | 
**mode** | **str** | The checkout mode (e.g., &#39;payment&#39;) | [optional] 
**metadata** | **Dict[str, object]** | Optional custom metadata | 
**hosted_checkout_config** | [**HostedCheckoutConfigDto**](HostedCheckoutConfigDto.md) | Configuration for the hosted checkout page | [optional] 

## Example

```python
from cashful.models.create_checkout_session_dto import CreateCheckoutSessionDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateCheckoutSessionDto from a JSON string
create_checkout_session_dto_instance = CreateCheckoutSessionDto.from_json(json)
# print the JSON string representation of the object
print(CreateCheckoutSessionDto.to_json())

# convert the object into a dict
create_checkout_session_dto_dict = create_checkout_session_dto_instance.to_dict()
# create an instance of CreateCheckoutSessionDto from a dict
create_checkout_session_dto_from_dict = CreateCheckoutSessionDto.from_dict(create_checkout_session_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


