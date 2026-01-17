# OrganizationComplianceResponseDto


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**deleted_at** | **datetime** |  | [optional] 
**organization_id** | **str** |  | 
**company_registration_name** | **str** |  | [optional] 
**company_registration_number** | **str** |  | [optional] 
**company_trading_name** | **str** |  | [optional] 
**vat_registration_number** | **str** |  | [optional] 
**industry** | **str** |  | [optional] 
**sub_industry** | **str** |  | [optional] 
**estimated_annual_turnover** | **str** |  | [optional] 
**business_description** | **str** |  | [optional] 
**company_mobile_money_settlement_number** | **str** |  | [optional] 
**company_email** | **str** |  | [optional] 
**company_contact_number** | **str** |  | [optional] 
**website** | **str** |  | [optional] 
**social_media** | **str** |  | [optional] 
**account_contact_number** | **str** |  | [optional] 
**customer_support_contact_number** | **str** |  | [optional] 
**customer_support_escalation_contact_number** | **str** |  | [optional] 
**emergency_contact_number** | **str** |  | [optional] 
**street_address** | **str** |  | [optional] 
**apartment** | **str** |  | [optional] 
**suburb** | **str** |  | [optional] 
**city** | **str** |  | [optional] 
**postal_code** | **str** |  | [optional] 
**country** | **str** |  | [optional] 
**bank** | **str** |  | [optional] 
**account_type** | **str** |  | [optional] 
**account_name** | **str** |  | [optional] 
**account_number** | **str** |  | [optional] 
**branch_code** | **str** |  | [optional] 
**swift_code** | **str** |  | [optional] 
**certificate_of_incorporation** | **str** |  | [optional] 
**identity_documents** | **str** |  | [optional] 
**bank_account_confirmation_letter** | **str** |  | [optional] 
**proof_of_business_address** | **str** |  | [optional] 
**terms_accepted** | **bool** |  | [optional] 
**accepted_at** | **datetime** |  | [optional] 
**current_step** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**is_completed** | **bool** |  | [optional] 
**completion_score** | **float** |  | [optional] 

## Example

```python
from cashful.models.organization_compliance_response_dto import OrganizationComplianceResponseDto

# TODO update the JSON string below
json = "{}"
# create an instance of OrganizationComplianceResponseDto from a JSON string
organization_compliance_response_dto_instance = OrganizationComplianceResponseDto.from_json(json)
# print the JSON string representation of the object
print(OrganizationComplianceResponseDto.to_json())

# convert the object into a dict
organization_compliance_response_dto_dict = organization_compliance_response_dto_instance.to_dict()
# create an instance of OrganizationComplianceResponseDto from a dict
organization_compliance_response_dto_from_dict = OrganizationComplianceResponseDto.from_dict(organization_compliance_response_dto_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


