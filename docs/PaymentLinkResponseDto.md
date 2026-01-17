# PaymentLinkResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**merchant_id** | **str** |  | 
**url** | **str** |  | 
**product_id** | **str** |  | [optional] 
**customer_id** | **str** |  | [optional] 
**amount** | **float** |  | [optional] 
**currency** | **str** |  | 
**mode** | **str** |  | 
**active** | **bool** |  | 
**success_url** | **str** |  | 
**cancel_url** | **str** |  | 
**metadata** | **Dict[str, object]** |  | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 

## Example

```python
from cashful.models.payment_link_response_dto import PaymentLinkResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of PaymentLinkResponseDto from a JSON string
payment_link_response_dto_instance = PaymentLinkResponseDto.from_json(json)
# print the JSON string representation of the object
print(PaymentLinkResponseDto.to_json())

# convert the object into a dict
payment_link_response_dto_dict = payment_link_response_dto_instance.to_dict()
# create an instance of PaymentLinkResponseDto from a dict
payment_link_response_dto_from_dict = PaymentLinkResponseDto.from_dict(payment_link_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


