# IveriParamsDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application_id** | **str** | iVeri Application ID | 
**return_url** | **str** | URL to return to after 3DS authentication | 
**merchant_reference** | **str** | Unique merchant reference for this payment | 
**amount** | **str** | Payment amount in cents (as string) | 
**currency** | **str** | Three-letter ISO 4217 currency code | 

## Example

```python
from cashful.models.iveri_params_dto import IveriParamsDto

# TODO update the JSON string below
json = "{}"
# create an instance of IveriParamsDto from a JSON string
iveri_params_dto_instance = IveriParamsDto.from_json(json)
# print the JSON string representation of the object
print(IveriParamsDto.to_json())

# convert the object into a dict
iveri_params_dto_dict = iveri_params_dto_instance.to_dict()
# create an instance of IveriParamsDto from a dict
iveri_params_dto_from_dict = IveriParamsDto.from_dict(iveri_params_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


