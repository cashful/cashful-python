# ListTransfersResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[TransferResponseDto]**](TransferResponseDto.md) | List of transfers | 
**pagination** | [**PaginationResponseDto**](PaginationResponseDto.md) | Pagination metadata | 

## Example

```python
from cashful.models.list_transfers_response_dto import ListTransfersResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of ListTransfersResponseDto from a JSON string
list_transfers_response_dto_instance = ListTransfersResponseDto.from_json(json)
# print the JSON string representation of the object
print(ListTransfersResponseDto.to_json())

# convert the object into a dict
list_transfers_response_dto_dict = list_transfers_response_dto_instance.to_dict()
# create an instance of ListTransfersResponseDto from a dict
list_transfers_response_dto_from_dict = ListTransfersResponseDto.from_dict(list_transfers_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


