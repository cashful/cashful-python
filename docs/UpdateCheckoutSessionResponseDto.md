# UpdateCheckoutSessionResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**status** | **str** |  | 
**metadata** | **Dict[str, object]** |  | 

## Example

```python
from cashful.models.update_checkout_session_response_dto import UpdateCheckoutSessionResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCheckoutSessionResponseDto from a JSON string
update_checkout_session_response_dto_instance = UpdateCheckoutSessionResponseDto.from_json(json)
# print the JSON string representation of the object
print(UpdateCheckoutSessionResponseDto.to_json())

# convert the object into a dict
update_checkout_session_response_dto_dict = update_checkout_session_response_dto_instance.to_dict()
# create an instance of UpdateCheckoutSessionResponseDto from a dict
update_checkout_session_response_dto_from_dict = UpdateCheckoutSessionResponseDto.from_dict(update_checkout_session_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


