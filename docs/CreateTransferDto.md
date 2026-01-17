# CreateTransferDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merchant_id** | **str** | The ID of the merchant whose balance is being requested. If omitted, defaults to the authenticated merchant. | [optional] 
**from_customer_id** | **str** | The unique identifier of the customer sending the transfer | 
**to_customer_id** | **str** | The unique identifier of the customer receiving the transfer | 
**amount** | **float** | The amount to transfer in the smallest currency unit | 
**currency** | **str** | The three-letter ISO 4217 currency code | 
**description** | **str** | Optional description for the transfer | [optional] 

## Example

```python
from cashful.models.create_transfer_dto import CreateTransferDto

# TODO update the JSON string below
json = "{}"
# create an instance of CreateTransferDto from a JSON string
create_transfer_dto_instance = CreateTransferDto.from_json(json)
# print the JSON string representation of the object
print(CreateTransferDto.to_json())

# convert the object into a dict
create_transfer_dto_dict = create_transfer_dto_instance.to_dict()
# create an instance of CreateTransferDto from a dict
create_transfer_dto_from_dict = CreateTransferDto.from_dict(create_transfer_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


