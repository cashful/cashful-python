# RequestUploadUrlDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**filename** | **str** | Original filename | 
**mime_type** | **str** | MIME type of the file | 
**tags** | **List[str]** | Tags for classification | [optional] 
**related_entity_id** | **str** | Related entity ID (e.g., compliance info ID) | [optional] 
**related_entity_type** | **str** | Related entity type | [optional] 
**is_public** | **bool** | Whether the file should be publicly accessible | [optional] [default to False]

## Example

```python
from cashful.models.request_upload_url_dto import RequestUploadUrlDto

# TODO update the JSON string below
json = "{}"
# create an instance of RequestUploadUrlDto from a JSON string
request_upload_url_dto_instance = RequestUploadUrlDto.from_json(json)
# print the JSON string representation of the object
print(RequestUploadUrlDto.to_json())

# convert the object into a dict
request_upload_url_dto_dict = request_upload_url_dto_instance.to_dict()
# create an instance of RequestUploadUrlDto from a dict
request_upload_url_dto_from_dict = RequestUploadUrlDto.from_dict(request_upload_url_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


