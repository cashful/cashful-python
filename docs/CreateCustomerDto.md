# CreateCustomerDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant whose balance is being requested. If omitted, defaults to the authenticated merchant. | [optional] 
**phone_number** | **str** | The phone number of the customer | 
**email** | **str** | The email address of the customer | [optional] 
**name** | **str** | The full name of the customer | [optional] 
**metadata** | **Dict[str, object]** | Optional custom metadata | 

## Example

```python
from cashful.models.create_customer_dto import CreateCustomerDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateCustomerDto from a JSON string
create_customer_dto_instance = CreateCustomerDto.from_json(json)
# print the JSON string representation of the object
print(CreateCustomerDto.to_json())

# convert the object into a dict
create_customer_dto_dict = create_customer_dto_instance.to_dict()
# create an instance of CreateCustomerDto from a dict
create_customer_dto_from_dict = CreateCustomerDto.from_dict(create_customer_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


