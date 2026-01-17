# PresignedDownloadResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**download_url** | **str** | Presigned download URL | 
**expires_at** | **datetime** | URL expiration time | 

## Example

```python
from cashful.models.presigned_download_response_dto import PresignedDownloadResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of PresignedDownloadResponseDto from a JSON string
presigned_download_response_dto_instance = PresignedDownloadResponseDto.from_json(json)
# print the JSON string representation of the object
print(PresignedDownloadResponseDto.to_json())

# convert the object into a dict
presigned_download_response_dto_dict = presigned_download_response_dto_instance.to_dict()
# create an instance of PresignedDownloadResponseDto from a dict
presigned_download_response_dto_from_dict = PresignedDownloadResponseDto.from_dict(presigned_download_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


