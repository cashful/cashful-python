# JwkDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**kid** | **str** | Key ID uniquely identifying the key | 
**kty** | **str** | Key type (e.g., &#39;RSA&#39;, &#39;EC&#39;, &#39;OKP&#39;) | 
**alg** | **str** | Algorithm intended for use with the key | 
**use** | **str** | Intended use of the public key | [optional] 
**n** | **str** | Modulus for RSA keys | [optional] 
**e** | **str** | Exponent for RSA keys | [optional] 
**crv** | **str** | Curve name for elliptic curve keys | [optional] 
**x** | **str** | X coordinate for elliptic curve keys | [optional] 
**y** | **str** | Y coordinate for elliptic curve keys | [optional] 

## Example

```python
from cashful.models.jwk_dto import JwkDto

# TODO update the JSON string below
json = "{}"
# create an instance of JwkDto from a JSON string
jwk_dto_instance = JwkDto.from_json(json)
# print the JSON string representation of the object
print(JwkDto.to_json())

# convert the object into a dict
jwk_dto_dict = jwk_dto_instance.to_dict()
# create an instance of JwkDto from a dict
jwk_dto_from_dict = JwkDto.from_dict(jwk_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


