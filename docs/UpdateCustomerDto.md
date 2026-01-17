# UpdateCustomerDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** | The email address of the customer | [optional] 
**name** | **str** | The full name of the customer | [optional] 
**metadata** | **Dict[str, object]** | Optional custom metadata | 

## Example

```python
from cashful.models.update_customer_dto import UpdateCustomerDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomerDto from a JSON string
update_customer_dto_instance = UpdateCustomerDto.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomerDto.to_json())

# convert the object into a dict
update_customer_dto_dict = update_customer_dto_instance.to_dict()
# create an instance of UpdateCustomerDto from a dict
update_customer_dto_from_dict = UpdateCustomerDto.from_dict(update_customer_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


