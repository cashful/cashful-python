# CustomerResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**merchant_id** | **str** |  | 
**phone_number** | **str** | The phone number of the customer | 
**email** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**metadata** | **Dict[str, object]** |  | 

## Example

```python
from cashful.models.customer_response_dto import CustomerResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerResponseDto from a JSON string
customer_response_dto_instance = CustomerResponseDto.from_json(json)
# print the JSON string representation of the object
print(CustomerResponseDto.to_json())

# convert the object into a dict
customer_response_dto_dict = customer_response_dto_instance.to_dict()
# create an instance of CustomerResponseDto from a dict
customer_response_dto_from_dict = CustomerResponseDto.from_dict(customer_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


