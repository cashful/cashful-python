# TransferResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**merchant_id** | **str** |  | 
**from_customer_id** | **str** |  | 
**to_customer_id** | **str** |  | 
**amount** | **float** |  | 
**currency** | **str** |  | 
**description** | **str** |  | [optional] 
**status** | **str** |  | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 

## Example

```python
from cashful.models.transfer_response_dto import TransferResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of TransferResponseDto from a JSON string
transfer_response_dto_instance = TransferResponseDto.from_json(json)
# print the JSON string representation of the object
print(TransferResponseDto.to_json())

# convert the object into a dict
transfer_response_dto_dict = transfer_response_dto_instance.to_dict()
# create an instance of TransferResponseDto from a dict
transfer_response_dto_from_dict = TransferResponseDto.from_dict(transfer_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


