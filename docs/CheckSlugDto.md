# CheckSlugDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**slug** | **str** | The organization slug to check | 

## Example

```python
from cashful.models.check_slug_dto import CheckSlugDto

# TODO update the JSON string below
json = "{}"
# create an instance of CheckSlugDto from a JSON string
check_slug_dto_instance = CheckSlugDto.from_json(json)
# print the JSON string representation of the object
print(CheckSlugDto.to_json())

# convert the object into a dict
check_slug_dto_dict = check_slug_dto_instance.to_dict()
# create an instance of CheckSlugDto from a dict
check_slug_dto_from_dict = CheckSlugDto.from_dict(check_slug_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


