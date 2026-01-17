# ConfirmUploadDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **str** | File ID returned from upload URL request | 
**checksum** | **str** | File checksum for integrity verification | [optional] 
**size** | **float** | Actual file size in bytes | [optional] 

## Example

```python
from cashful.models.confirm_upload_dto import ConfirmUploadDto

# TODO update the JSON string below
json = "{}"
# create an instance of ConfirmUploadDto from a JSON string
confirm_upload_dto_instance = ConfirmUploadDto.from_json(json)
# print the JSON string representation of the object
print(ConfirmUploadDto.to_json())

# convert the object into a dict
confirm_upload_dto_dict = confirm_upload_dto_instance.to_dict()
# create an instance of ConfirmUploadDto from a dict
confirm_upload_dto_from_dict = ConfirmUploadDto.from_dict(confirm_upload_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


