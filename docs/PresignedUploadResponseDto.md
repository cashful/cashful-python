# PresignedUploadResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**upload_url** | **str** | Presigned upload URL | 
**file_id** | **str** | File ID for tracking | 
**key** | **str** | S3 object key | 
**expires_at** | **datetime** | URL expiration time | 

## Example

```python
from cashful.models.presigned_upload_response_dto import PresignedUploadResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of PresignedUploadResponseDto from a JSON string
presigned_upload_response_dto_instance = PresignedUploadResponseDto.from_json(json)
# print the JSON string representation of the object
print(PresignedUploadResponseDto.to_json())

# convert the object into a dict
presigned_upload_response_dto_dict = presigned_upload_response_dto_instance.to_dict()
# create an instance of PresignedUploadResponseDto from a dict
presigned_upload_response_dto_from_dict = PresignedUploadResponseDto.from_dict(presigned_upload_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


