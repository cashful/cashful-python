# cashful.AuthenticationApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**accept_invitation**](AuthenticationApi.md#accept_invitation) | **POST** /api/canary/authentication/organization/accept-invitation | Accept Invitation
[**cancel_invitation**](AuthenticationApi.md#cancel_invitation) | **POST** /api/canary/authentication/organization/cancel-invitation | Cancel Invitation
[**change_email**](AuthenticationApi.md#change_email) | **POST** /api/canary/authentication/change-email | Change Email
[**change_password**](AuthenticationApi.md#change_password) | **POST** /api/canary/authentication/change-password | Change Password
[**check_slug**](AuthenticationApi.md#check_slug) | **POST** /api/canary/authentication/organization/check-slug | Check Slug
[**create_api_key**](AuthenticationApi.md#create_api_key) | **POST** /api/canary/authentication/api-key/create | Create API Key
[**create_organization**](AuthenticationApi.md#create_organization) | **POST** /api/canary/authentication/organization/create | Create Organization
[**delete_api_key**](AuthenticationApi.md#delete_api_key) | **POST** /api/canary/authentication/api-key/delete | Delete API Key
[**delete_organization**](AuthenticationApi.md#delete_organization) | **POST** /api/canary/authentication/organization/delete | Delete Organization
[**delete_user**](AuthenticationApi.md#delete_user) | **POST** /api/canary/authentication/delete-user | Delete User
[**forget_password**](AuthenticationApi.md#forget_password) | **POST** /api/canary/authentication/forget-password | Forget Password
[**get_access_token**](AuthenticationApi.md#get_access_token) | **POST** /api/canary/authentication/get-access-token | Get Access Token
[**get_active_member**](AuthenticationApi.md#get_active_member) | **GET** /api/canary/authentication/organization/get-active-member | Get Active Member
[**get_active_member_role**](AuthenticationApi.md#get_active_member_role) | **GET** /api/canary/authentication/organization/get-active-member-role | Get Active Member Role
[**get_api_key**](AuthenticationApi.md#get_api_key) | **GET** /api/canary/authentication/api-key/get | Get API Key
[**get_invitation**](AuthenticationApi.md#get_invitation) | **GET** /api/canary/authentication/organization/get-invitation | Get Invitation
[**get_organization**](AuthenticationApi.md#get_organization) | **GET** /api/canary/authentication/organization/get-full-organization | Get Full Organization
[**get_session**](AuthenticationApi.md#get_session) | **GET** /api/canary/authentication/get-session | Get Session
[**has_permission**](AuthenticationApi.md#has_permission) | **POST** /api/canary/authentication/organization/has-permission | Has Permission
[**invite_member**](AuthenticationApi.md#invite_member) | **POST** /api/canary/authentication/organization/invite-member | Invite Member
[**is_username_available**](AuthenticationApi.md#is_username_available) | **POST** /api/canary/authentication/is-username-available | Check Username Availability
[**leave_organization**](AuthenticationApi.md#leave_organization) | **POST** /api/canary/authentication/organization/leave | Leave Organization
[**link_social**](AuthenticationApi.md#link_social) | **POST** /api/canary/authentication/link-social | Link Social Account
[**list_accounts**](AuthenticationApi.md#list_accounts) | **GET** /api/canary/authentication/list-accounts | List Linked Accounts
[**list_api_keys**](AuthenticationApi.md#list_api_keys) | **GET** /api/canary/authentication/api-key/list | List API Keys
[**list_members**](AuthenticationApi.md#list_members) | **GET** /api/canary/authentication/organization/list-members | List Members
[**list_organization_invitations**](AuthenticationApi.md#list_organization_invitations) | **GET** /api/canary/authentication/organization/list-invitations | List Invitations
[**list_organizations**](AuthenticationApi.md#list_organizations) | **GET** /api/canary/authentication/organization/list | List Organizations
[**list_user_invitations**](AuthenticationApi.md#list_user_invitations) | **GET** /api/canary/authentication/organization/list-user-invitations | List User Invitations
[**list_user_sessions**](AuthenticationApi.md#list_user_sessions) | **GET** /api/canary/authentication/list-sessions | List User Sessions
[**ok**](AuthenticationApi.md#ok) | **GET** /api/canary/authentication/ok | Health Check
[**refresh_token**](AuthenticationApi.md#refresh_token) | **POST** /api/canary/authentication/refresh-token | Refresh Token
[**reject_invitation**](AuthenticationApi.md#reject_invitation) | **POST** /api/canary/authentication/organization/reject-invitation | Reject Invitation
[**remove_member**](AuthenticationApi.md#remove_member) | **POST** /api/canary/authentication/organization/remove-member | Remove Member
[**request_password_reset**](AuthenticationApi.md#request_password_reset) | **POST** /api/canary/authentication/request-password-reset | Request Password Reset
[**request_phone_password_reset**](AuthenticationApi.md#request_phone_password_reset) | **POST** /api/canary/authentication/phone-number/request-password-reset | Request Password Reset via Phone
[**reset_password**](AuthenticationApi.md#reset_password) | **POST** /api/canary/authentication/reset-password | Reset Password
[**reset_password_callback**](AuthenticationApi.md#reset_password_callback) | **GET** /api/canary/authentication/reset-password/{token} | Reset Password Callback
[**reset_phone_password**](AuthenticationApi.md#reset_phone_password) | **POST** /api/canary/authentication/phone-number/reset-password | Reset Password with Phone
[**revoke_other_sessions**](AuthenticationApi.md#revoke_other_sessions) | **POST** /api/canary/authentication/revoke-other-sessions | Revoke Other Sessions
[**revoke_session**](AuthenticationApi.md#revoke_session) | **POST** /api/canary/authentication/revoke-session | Revoke Session
[**revoke_sessions**](AuthenticationApi.md#revoke_sessions) | **POST** /api/canary/authentication/revoke-sessions | Revoke All Sessions
[**send_phone_otp**](AuthenticationApi.md#send_phone_otp) | **POST** /api/canary/authentication/phone-number/send-otp | Send OTP to Phone
[**send_verification_email**](AuthenticationApi.md#send_verification_email) | **POST** /api/canary/authentication/send-verification-email | Send Verification Email
[**set_active_organization**](AuthenticationApi.md#set_active_organization) | **POST** /api/canary/authentication/organization/set-active | Set Active Organization
[**sign_in_email**](AuthenticationApi.md#sign_in_email) | **POST** /api/canary/authentication/sign-in/email | Sign in with email
[**sign_in_phone_number**](AuthenticationApi.md#sign_in_phone_number) | **POST** /api/canary/authentication/sign-in/phone-number | Sign in with Phone Number
[**sign_out**](AuthenticationApi.md#sign_out) | **POST** /api/canary/authentication/sign-out | Sign out
[**sign_up_email**](AuthenticationApi.md#sign_up_email) | **POST** /api/canary/authentication/sign-up/email | Sign up with email
[**social_sign_in**](AuthenticationApi.md#social_sign_in) | **POST** /api/canary/authentication/sign-in/social | Sign in with social provider
[**unlink_account**](AuthenticationApi.md#unlink_account) | **POST** /api/canary/authentication/unlink-account | Unlink Social Account
[**update_api_key**](AuthenticationApi.md#update_api_key) | **POST** /api/canary/authentication/api-key/update | Update API Key
[**update_member_role**](AuthenticationApi.md#update_member_role) | **POST** /api/canary/authentication/organization/update-member-role | Update Member Role
[**update_organization**](AuthenticationApi.md#update_organization) | **POST** /api/canary/authentication/organization/update | Update Organization
[**update_user**](AuthenticationApi.md#update_user) | **POST** /api/canary/authentication/update-user | Update User
[**verify_api_key**](AuthenticationApi.md#verify_api_key) | **POST** /api/canary/authentication/api-key/verify | Verify API Key
[**verify_email**](AuthenticationApi.md#verify_email) | **GET** /api/canary/authentication/verify-email | Verify Email
[**verify_phone_number**](AuthenticationApi.md#verify_phone_number) | **POST** /api/canary/authentication/phone-number/verify | Verify Phone Number


# **accept_invitation**
> AcceptInvitationResponseDto accept_invitation(accept_invitation_dto)

Accept Invitation

Accept an invitation to an organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.accept_invitation_dto import AcceptInvitationDto
from cashful.models.accept_invitation_response_dto import AcceptInvitationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    accept_invitation_dto = cashful.AcceptInvitationDto() # AcceptInvitationDto | 

    try:
        # Accept Invitation
        api_response = api_instance.accept_invitation(accept_invitation_dto)
        print("The response of AuthenticationApi->accept_invitation:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->accept_invitation: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept_invitation_dto** | [**AcceptInvitationDto**](AcceptInvitationDto.md)|  | 

### Return type

[**AcceptInvitationResponseDto**](AcceptInvitationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Invitation accepted successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **cancel_invitation**
> CancelInvitationResponseDto cancel_invitation(cancel_invitation_dto)

Cancel Invitation

Cancel an invitation to an organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.cancel_invitation_dto import CancelInvitationDto
from cashful.models.cancel_invitation_response_dto import CancelInvitationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    cancel_invitation_dto = cashful.CancelInvitationDto() # CancelInvitationDto | 

    try:
        # Cancel Invitation
        api_response = api_instance.cancel_invitation(cancel_invitation_dto)
        print("The response of AuthenticationApi->cancel_invitation:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->cancel_invitation: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cancel_invitation_dto** | [**CancelInvitationDto**](CancelInvitationDto.md)|  | 

### Return type

[**CancelInvitationResponseDto**](CancelInvitationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Invitation cancelled successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **change_email**
> ChangeEmailResponseDto change_email(change_email_dto)

Change Email

Change the email address of the current user

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.change_email_dto import ChangeEmailDto
from cashful.models.change_email_response_dto import ChangeEmailResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    change_email_dto = cashful.ChangeEmailDto() # ChangeEmailDto | 

    try:
        # Change Email
        api_response = api_instance.change_email(change_email_dto)
        print("The response of AuthenticationApi->change_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->change_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **change_email_dto** | [**ChangeEmailDto**](ChangeEmailDto.md)|  | 

### Return type

[**ChangeEmailResponseDto**](ChangeEmailResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Email change request processed successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **change_password**
> ChangePasswordResponseDto change_password(change_password_dto)

Change Password

Change the password of the current user

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.change_password_dto import ChangePasswordDto
from cashful.models.change_password_response_dto import ChangePasswordResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    change_password_dto = cashful.ChangePasswordDto() # ChangePasswordDto | 

    try:
        # Change Password
        api_response = api_instance.change_password(change_password_dto)
        print("The response of AuthenticationApi->change_password:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->change_password: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **change_password_dto** | [**ChangePasswordDto**](ChangePasswordDto.md)|  | 

### Return type

[**ChangePasswordResponseDto**](ChangePasswordResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Password changed successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **check_slug**
> CheckSlugResponseDto check_slug(check_slug_dto)

Check Slug

Check if organization slug is available

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.check_slug_dto import CheckSlugDto
from cashful.models.check_slug_response_dto import CheckSlugResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    check_slug_dto = cashful.CheckSlugDto() # CheckSlugDto | 

    try:
        # Check Slug
        api_response = api_instance.check_slug(check_slug_dto)
        print("The response of AuthenticationApi->check_slug:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->check_slug: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **check_slug_dto** | [**CheckSlugDto**](CheckSlugDto.md)|  | 

### Return type

[**CheckSlugResponseDto**](CheckSlugResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Slug check completed |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_api_key**
> CreateApiKeyResponseDto create_api_key(create_api_key_dto)

Create API Key

Create a new API key

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_api_key_dto import CreateApiKeyDto
from cashful.models.create_api_key_response_dto import CreateApiKeyResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    create_api_key_dto = cashful.CreateApiKeyDto() # CreateApiKeyDto | 

    try:
        # Create API Key
        api_response = api_instance.create_api_key(create_api_key_dto)
        print("The response of AuthenticationApi->create_api_key:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->create_api_key: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_api_key_dto** | [**CreateApiKeyDto**](CreateApiKeyDto.md)|  | 

### Return type

[**CreateApiKeyResponseDto**](CreateApiKeyResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | API key created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_organization**
> CreateOrganizationResponseDto create_organization(create_organization_dto)

Create Organization

Create a new organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.create_organization_dto import CreateOrganizationDto
from cashful.models.create_organization_response_dto import CreateOrganizationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    create_organization_dto = cashful.CreateOrganizationDto() # CreateOrganizationDto | 

    try:
        # Create Organization
        api_response = api_instance.create_organization(create_organization_dto)
        print("The response of AuthenticationApi->create_organization:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->create_organization: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_organization_dto** | [**CreateOrganizationDto**](CreateOrganizationDto.md)|  | 

### Return type

[**CreateOrganizationResponseDto**](CreateOrganizationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Organization created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_api_key**
> DeleteApiKeyResponseDto delete_api_key(delete_api_key_dto)

Delete API Key

Delete an API key

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.delete_api_key_dto import DeleteApiKeyDto
from cashful.models.delete_api_key_response_dto import DeleteApiKeyResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    delete_api_key_dto = cashful.DeleteApiKeyDto() # DeleteApiKeyDto | 

    try:
        # Delete API Key
        api_response = api_instance.delete_api_key(delete_api_key_dto)
        print("The response of AuthenticationApi->delete_api_key:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->delete_api_key: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **delete_api_key_dto** | [**DeleteApiKeyDto**](DeleteApiKeyDto.md)|  | 

### Return type

[**DeleteApiKeyResponseDto**](DeleteApiKeyResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | API key deleted successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_organization**
> DeleteOrganizationResponseDto delete_organization(delete_organization_dto)

Delete Organization

Delete an organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.delete_organization_dto import DeleteOrganizationDto
from cashful.models.delete_organization_response_dto import DeleteOrganizationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    delete_organization_dto = cashful.DeleteOrganizationDto() # DeleteOrganizationDto | 

    try:
        # Delete Organization
        api_response = api_instance.delete_organization(delete_organization_dto)
        print("The response of AuthenticationApi->delete_organization:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->delete_organization: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **delete_organization_dto** | [**DeleteOrganizationDto**](DeleteOrganizationDto.md)|  | 

### Return type

[**DeleteOrganizationResponseDto**](DeleteOrganizationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Organization deleted successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_user**
> DeleteUserResponseDto delete_user(delete_user_dto)

Delete User

Delete the current user's account

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.delete_user_dto import DeleteUserDto
from cashful.models.delete_user_response_dto import DeleteUserResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    delete_user_dto = cashful.DeleteUserDto() # DeleteUserDto | 

    try:
        # Delete User
        api_response = api_instance.delete_user(delete_user_dto)
        print("The response of AuthenticationApi->delete_user:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->delete_user: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **delete_user_dto** | [**DeleteUserDto**](DeleteUserDto.md)|  | 

### Return type

[**DeleteUserResponseDto**](DeleteUserResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | User deletion processed successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **forget_password**
> ForgotPasswordResponseDto forget_password(forgot_password_dto)

Forget Password

Send a password reset email to the user

### Example


```python
import cashful
from cashful.models.forgot_password_dto import ForgotPasswordDto
from cashful.models.forgot_password_response_dto import ForgotPasswordResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    forgot_password_dto = cashful.ForgotPasswordDto() # ForgotPasswordDto | 

    try:
        # Forget Password
        api_response = api_instance.forget_password(forgot_password_dto)
        print("The response of AuthenticationApi->forget_password:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->forget_password: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **forgot_password_dto** | [**ForgotPasswordDto**](ForgotPasswordDto.md)|  | 

### Return type

[**ForgotPasswordResponseDto**](ForgotPasswordResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Password reset email sent |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_access_token**
> GetAccessTokenResponseDto get_access_token(get_access_token_dto)

Get Access Token

Get current access token

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.get_access_token_dto import GetAccessTokenDto
from cashful.models.get_access_token_response_dto import GetAccessTokenResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    get_access_token_dto = cashful.GetAccessTokenDto() # GetAccessTokenDto | 

    try:
        # Get Access Token
        api_response = api_instance.get_access_token(get_access_token_dto)
        print("The response of AuthenticationApi->get_access_token:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->get_access_token: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **get_access_token_dto** | [**GetAccessTokenDto**](GetAccessTokenDto.md)|  | 

### Return type

[**GetAccessTokenResponseDto**](GetAccessTokenResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Access token retrieved successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_active_member**
> GetActiveMemberResponseDto get_active_member(organization_id=organization_id)

Get Active Member

Get the member details of the active organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.get_active_member_response_dto import GetActiveMemberResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    organization_id = 'org_12345' # str | Filter by organization ID (optional)

    try:
        # Get Active Member
        api_response = api_instance.get_active_member(organization_id=organization_id)
        print("The response of AuthenticationApi->get_active_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->get_active_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organization_id** | **str**| Filter by organization ID | [optional] 

### Return type

[**GetActiveMemberResponseDto**](GetActiveMemberResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Active member retrieved successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_active_member_role**
> GetActiveMemberRoleResponseDto get_active_member_role(organization_id=organization_id)

Get Active Member Role

Get the role of the current user in the active organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.get_active_member_role_response_dto import GetActiveMemberRoleResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    organization_id = 'org_12345' # str | Filter by organization ID (optional)

    try:
        # Get Active Member Role
        api_response = api_instance.get_active_member_role(organization_id=organization_id)
        print("The response of AuthenticationApi->get_active_member_role:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->get_active_member_role: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organization_id** | **str**| Filter by organization ID | [optional] 

### Return type

[**GetActiveMemberRoleResponseDto**](GetActiveMemberRoleResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Active member role retrieved successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_api_key**
> GetApiKeyResponseDto get_api_key(id)

Get API Key

Retrieve a specific API key by ID

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.get_api_key_response_dto import GetApiKeyResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    id = 'key_12345' # str | The ID of API key to retrieve

    try:
        # Get API Key
        api_response = api_instance.get_api_key(id)
        print("The response of AuthenticationApi->get_api_key:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->get_api_key: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The ID of API key to retrieve | 

### Return type

[**GetApiKeyResponseDto**](GetApiKeyResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | API key retrieved successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_invitation**
> GetInvitationResponseDto get_invitation(invitation_id)

Get Invitation

Get an invitation by ID

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.get_invitation_response_dto import GetInvitationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    invitation_id = 'inv_12345' # str | The ID of the invitation to get

    try:
        # Get Invitation
        api_response = api_instance.get_invitation(invitation_id)
        print("The response of AuthenticationApi->get_invitation:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->get_invitation: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **invitation_id** | **str**| The ID of the invitation to get | 

### Return type

[**GetInvitationResponseDto**](GetInvitationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Invitation retrieved successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_organization**
> GetFullOrganizationResponseDto get_organization(organization_id=organization_id)

Get Full Organization

Get the full organization details

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.get_full_organization_response_dto import GetFullOrganizationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    organization_id = 'org_12345' # str | The organization ID to get (optional)

    try:
        # Get Full Organization
        api_response = api_instance.get_organization(organization_id=organization_id)
        print("The response of AuthenticationApi->get_organization:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->get_organization: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organization_id** | **str**| The organization ID to get | [optional] 

### Return type

[**GetFullOrganizationResponseDto**](GetFullOrganizationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Organization retrieved successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_session**
> GetSessionResponseDto get_session()

Get Session

Retrieve the current user session

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.get_session_response_dto import GetSessionResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)

    try:
        # Get Session
        api_response = api_instance.get_session()
        print("The response of AuthenticationApi->get_session:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->get_session: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**GetSessionResponseDto**](GetSessionResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Session retrieved successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **has_permission**
> HasPermissionResponseDto has_permission(has_permission_dto)

Has Permission

Check if a user has permission

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.has_permission_dto import HasPermissionDto
from cashful.models.has_permission_response_dto import HasPermissionResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    has_permission_dto = cashful.HasPermissionDto() # HasPermissionDto | 

    try:
        # Has Permission
        api_response = api_instance.has_permission(has_permission_dto)
        print("The response of AuthenticationApi->has_permission:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->has_permission: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **has_permission_dto** | [**HasPermissionDto**](HasPermissionDto.md)|  | 

### Return type

[**HasPermissionResponseDto**](HasPermissionResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Permission check completed |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **invite_member**
> InviteMemberResponseDto invite_member(invite_member_dto)

Invite Member

Invite a user to an organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.invite_member_dto import InviteMemberDto
from cashful.models.invite_member_response_dto import InviteMemberResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    invite_member_dto = cashful.InviteMemberDto() # InviteMemberDto | 

    try:
        # Invite Member
        api_response = api_instance.invite_member(invite_member_dto)
        print("The response of AuthenticationApi->invite_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->invite_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **invite_member_dto** | [**InviteMemberDto**](InviteMemberDto.md)|  | 

### Return type

[**InviteMemberResponseDto**](InviteMemberResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Member invited successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **is_username_available**
> IsUsernameAvailableResponseDto is_username_available(is_username_available_dto)

Check Username Availability

Check if username is available for signup

### Example


```python
import cashful
from cashful.models.is_username_available_dto import IsUsernameAvailableDto
from cashful.models.is_username_available_response_dto import IsUsernameAvailableResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    is_username_available_dto = cashful.IsUsernameAvailableDto() # IsUsernameAvailableDto | 

    try:
        # Check Username Availability
        api_response = api_instance.is_username_available(is_username_available_dto)
        print("The response of AuthenticationApi->is_username_available:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->is_username_available: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **is_username_available_dto** | [**IsUsernameAvailableDto**](IsUsernameAvailableDto.md)|  | 

### Return type

[**IsUsernameAvailableResponseDto**](IsUsernameAvailableResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Username availability checked |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **leave_organization**
> LeaveOrganizationResponseDto leave_organization(leave_organization_dto)

Leave Organization

Leave an organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.leave_organization_dto import LeaveOrganizationDto
from cashful.models.leave_organization_response_dto import LeaveOrganizationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    leave_organization_dto = cashful.LeaveOrganizationDto() # LeaveOrganizationDto | 

    try:
        # Leave Organization
        api_response = api_instance.leave_organization(leave_organization_dto)
        print("The response of AuthenticationApi->leave_organization:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->leave_organization: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **leave_organization_dto** | [**LeaveOrganizationDto**](LeaveOrganizationDto.md)|  | 

### Return type

[**LeaveOrganizationResponseDto**](LeaveOrganizationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Left organization successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **link_social**
> LinkSocialResponseDto link_social(link_social_dto)

Link Social Account

Link a social account to existing user

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.link_social_dto import LinkSocialDto
from cashful.models.link_social_response_dto import LinkSocialResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    link_social_dto = cashful.LinkSocialDto() # LinkSocialDto | 

    try:
        # Link Social Account
        api_response = api_instance.link_social(link_social_dto)
        print("The response of AuthenticationApi->link_social:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->link_social: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **link_social_dto** | [**LinkSocialDto**](LinkSocialDto.md)|  | 

### Return type

[**LinkSocialResponseDto**](LinkSocialResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Social account linked successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_accounts**
> ListAccountsResponseDto list_accounts()

List Linked Accounts

List all linked social accounts

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_accounts_response_dto import ListAccountsResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)

    try:
        # List Linked Accounts
        api_response = api_instance.list_accounts()
        print("The response of AuthenticationApi->list_accounts:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->list_accounts: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**ListAccountsResponseDto**](ListAccountsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Linked accounts listed successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_api_keys**
> ListApiKeysResponseDto list_api_keys()

List API Keys

List all API keys for the current user

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_api_keys_response_dto import ListApiKeysResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)

    try:
        # List API Keys
        api_response = api_instance.list_api_keys()
        print("The response of AuthenticationApi->list_api_keys:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->list_api_keys: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**ListApiKeysResponseDto**](ListApiKeysResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | API keys listed successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_members**
> ListMembersResponseDto list_members(organization_id=organization_id)

List Members

List all members of an organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_members_response_dto import ListMembersResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    organization_id = 'org_12345' # str | Filter by organization ID (optional)

    try:
        # List Members
        api_response = api_instance.list_members(organization_id=organization_id)
        print("The response of AuthenticationApi->list_members:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->list_members: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organization_id** | **str**| Filter by organization ID | [optional] 

### Return type

[**ListMembersResponseDto**](ListMembersResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Members listed successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_organization_invitations**
> ListInvitationsResponseDto list_organization_invitations(organization_id=organization_id)

List Invitations

List all invitations a user has received

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_invitations_response_dto import ListInvitationsResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    organization_id = 'org_12345' # str | Filter by organization ID (optional)

    try:
        # List Invitations
        api_response = api_instance.list_organization_invitations(organization_id=organization_id)
        print("The response of AuthenticationApi->list_organization_invitations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->list_organization_invitations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organization_id** | **str**| Filter by organization ID | [optional] 

### Return type

[**ListInvitationsResponseDto**](ListInvitationsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Invitations listed successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_organizations**
> List[OrganizationDto] list_organizations(include=include)

List Organizations

List all organizations for the current user

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.organization_dto import OrganizationDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    include = true # bool | Include additional organization data (optional)

    try:
        # List Organizations
        api_response = api_instance.list_organizations(include=include)
        print("The response of AuthenticationApi->list_organizations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->list_organizations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **include** | **bool**| Include additional organization data | [optional] 

### Return type

[**List[OrganizationDto]**](OrganizationDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Organizations listed successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_user_invitations**
> ListUserInvitationsResponseDto list_user_invitations(status=status)

List User Invitations

List all invitations a user has received

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_user_invitations_response_dto import ListUserInvitationsResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    status = 'pending' # str | Filter by status (optional)

    try:
        # List User Invitations
        api_response = api_instance.list_user_invitations(status=status)
        print("The response of AuthenticationApi->list_user_invitations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->list_user_invitations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **str**| Filter by status | [optional] 

### Return type

[**ListUserInvitationsResponseDto**](ListUserInvitationsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | User invitations listed successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_user_sessions**
> ListSessionsResponseDto list_user_sessions()

List User Sessions

List all active sessions for the user

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.list_sessions_response_dto import ListSessionsResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)

    try:
        # List User Sessions
        api_response = api_instance.list_user_sessions()
        print("The response of AuthenticationApi->list_user_sessions:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->list_user_sessions: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**ListSessionsResponseDto**](ListSessionsResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Sessions listed successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ok**
> str ok()

Health Check

Check if the authentication API is working

### Example


```python
import cashful
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)

    try:
        # Health Check
        api_response = api_instance.ok()
        print("The response of AuthenticationApi->ok:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->ok: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

**str**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | API is working |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**404** | Resource not found |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **refresh_token**
> RefreshTokenResponseDto refresh_token(refresh_token_dto)

Refresh Token

Refresh authentication token

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.refresh_token_dto import RefreshTokenDto
from cashful.models.refresh_token_response_dto import RefreshTokenResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    refresh_token_dto = cashful.RefreshTokenDto() # RefreshTokenDto | 

    try:
        # Refresh Token
        api_response = api_instance.refresh_token(refresh_token_dto)
        print("The response of AuthenticationApi->refresh_token:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->refresh_token: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **refresh_token_dto** | [**RefreshTokenDto**](RefreshTokenDto.md)|  | 

### Return type

[**RefreshTokenResponseDto**](RefreshTokenResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Token refreshed successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **reject_invitation**
> RejectInvitationResponseDto reject_invitation(reject_invitation_dto)

Reject Invitation

Reject an invitation to an organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.reject_invitation_dto import RejectInvitationDto
from cashful.models.reject_invitation_response_dto import RejectInvitationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    reject_invitation_dto = cashful.RejectInvitationDto() # RejectInvitationDto | 

    try:
        # Reject Invitation
        api_response = api_instance.reject_invitation(reject_invitation_dto)
        print("The response of AuthenticationApi->reject_invitation:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->reject_invitation: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **reject_invitation_dto** | [**RejectInvitationDto**](RejectInvitationDto.md)|  | 

### Return type

[**RejectInvitationResponseDto**](RejectInvitationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Invitation rejected successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **remove_member**
> RemoveMemberResponseDto remove_member(remove_member_dto)

Remove Member

Remove a member from an organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.remove_member_dto import RemoveMemberDto
from cashful.models.remove_member_response_dto import RemoveMemberResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    remove_member_dto = cashful.RemoveMemberDto() # RemoveMemberDto | 

    try:
        # Remove Member
        api_response = api_instance.remove_member(remove_member_dto)
        print("The response of AuthenticationApi->remove_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->remove_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **remove_member_dto** | [**RemoveMemberDto**](RemoveMemberDto.md)|  | 

### Return type

[**RemoveMemberResponseDto**](RemoveMemberResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Member removed successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **request_password_reset**
> RequestPasswordResetResponseDto request_password_reset(request_password_reset_dto)

Request Password Reset

Send a password reset email to the user

### Example


```python
import cashful
from cashful.models.request_password_reset_dto import RequestPasswordResetDto
from cashful.models.request_password_reset_response_dto import RequestPasswordResetResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    request_password_reset_dto = cashful.RequestPasswordResetDto() # RequestPasswordResetDto | 

    try:
        # Request Password Reset
        api_response = api_instance.request_password_reset(request_password_reset_dto)
        print("The response of AuthenticationApi->request_password_reset:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->request_password_reset: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request_password_reset_dto** | [**RequestPasswordResetDto**](RequestPasswordResetDto.md)|  | 

### Return type

[**RequestPasswordResetResponseDto**](RequestPasswordResetResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Password reset email sent successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **request_phone_password_reset**
> RequestPhonePasswordResetResponseDto request_phone_password_reset(request_phone_password_reset_dto)

Request Password Reset via Phone

Request password reset via phone number

### Example


```python
import cashful
from cashful.models.request_phone_password_reset_dto import RequestPhonePasswordResetDto
from cashful.models.request_phone_password_reset_response_dto import RequestPhonePasswordResetResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    request_phone_password_reset_dto = cashful.RequestPhonePasswordResetDto() # RequestPhonePasswordResetDto | 

    try:
        # Request Password Reset via Phone
        api_response = api_instance.request_phone_password_reset(request_phone_password_reset_dto)
        print("The response of AuthenticationApi->request_phone_password_reset:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->request_phone_password_reset: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request_phone_password_reset_dto** | [**RequestPhonePasswordResetDto**](RequestPhonePasswordResetDto.md)|  | 

### Return type

[**RequestPhonePasswordResetResponseDto**](RequestPhonePasswordResetResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Password reset requested successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **reset_password**
> ResetPasswordResponseDto reset_password(reset_password_dto)

Reset Password

Reset the user's password using a token

### Example


```python
import cashful
from cashful.models.reset_password_dto import ResetPasswordDto
from cashful.models.reset_password_response_dto import ResetPasswordResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    reset_password_dto = cashful.ResetPasswordDto() # ResetPasswordDto | 

    try:
        # Reset Password
        api_response = api_instance.reset_password(reset_password_dto)
        print("The response of AuthenticationApi->reset_password:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->reset_password: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **reset_password_dto** | [**ResetPasswordDto**](ResetPasswordDto.md)|  | 

### Return type

[**ResetPasswordResponseDto**](ResetPasswordResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Password reset successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **reset_password_callback**
> ResetPasswordCallbackResponseDto reset_password_callback(token, callback_url)

Reset Password Callback

Redirects user to callback URL with token

### Example


```python
import cashful
from cashful.models.reset_password_callback_response_dto import ResetPasswordCallbackResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    token = 'token_example' # str | 
    callback_url = 'https://example.com/reset-password' # str | The URL to redirect user to reset their password

    try:
        # Reset Password Callback
        api_response = api_instance.reset_password_callback(token, callback_url)
        print("The response of AuthenticationApi->reset_password_callback:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->reset_password_callback: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **str**|  | 
 **callback_url** | **str**| The URL to redirect user to reset their password | 

### Return type

[**ResetPasswordCallbackResponseDto**](ResetPasswordCallbackResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Password reset token validated |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **reset_phone_password**
> ResetPhonePasswordResponseDto reset_phone_password(reset_phone_password_dto)

Reset Password with Phone

Reset password using phone verification

### Example


```python
import cashful
from cashful.models.reset_phone_password_dto import ResetPhonePasswordDto
from cashful.models.reset_phone_password_response_dto import ResetPhonePasswordResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    reset_phone_password_dto = cashful.ResetPhonePasswordDto() # ResetPhonePasswordDto | 

    try:
        # Reset Password with Phone
        api_response = api_instance.reset_phone_password(reset_phone_password_dto)
        print("The response of AuthenticationApi->reset_phone_password:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->reset_phone_password: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **reset_phone_password_dto** | [**ResetPhonePasswordDto**](ResetPhonePasswordDto.md)|  | 

### Return type

[**ResetPhonePasswordResponseDto**](ResetPhonePasswordResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Password reset successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **revoke_other_sessions**
> RevokeSessionResponseDto revoke_other_sessions()

Revoke Other Sessions

Revoke all sessions except the current one

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.revoke_session_response_dto import RevokeSessionResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)

    try:
        # Revoke Other Sessions
        api_response = api_instance.revoke_other_sessions()
        print("The response of AuthenticationApi->revoke_other_sessions:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->revoke_other_sessions: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**RevokeSessionResponseDto**](RevokeSessionResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Other sessions revoked successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **revoke_session**
> RevokeSessionResponseDto revoke_session(revoke_session_dto)

Revoke Session

Revoke a specific session

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.revoke_session_dto import RevokeSessionDto
from cashful.models.revoke_session_response_dto import RevokeSessionResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    revoke_session_dto = cashful.RevokeSessionDto() # RevokeSessionDto | 

    try:
        # Revoke Session
        api_response = api_instance.revoke_session(revoke_session_dto)
        print("The response of AuthenticationApi->revoke_session:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->revoke_session: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revoke_session_dto** | [**RevokeSessionDto**](RevokeSessionDto.md)|  | 

### Return type

[**RevokeSessionResponseDto**](RevokeSessionResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Session revoked successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **revoke_sessions**
> RevokeSessionResponseDto revoke_sessions()

Revoke All Sessions

Revoke all sessions for the current user

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.revoke_session_response_dto import RevokeSessionResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)

    try:
        # Revoke All Sessions
        api_response = api_instance.revoke_sessions()
        print("The response of AuthenticationApi->revoke_sessions:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->revoke_sessions: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**RevokeSessionResponseDto**](RevokeSessionResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | All sessions revoked successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **send_phone_otp**
> SendPhoneOTPResponseDto send_phone_otp(send_phone_otp_dto)

Send OTP to Phone

Send one-time password to phone number

### Example


```python
import cashful
from cashful.models.send_phone_otp_dto import SendPhoneOTPDto
from cashful.models.send_phone_otp_response_dto import SendPhoneOTPResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    send_phone_otp_dto = cashful.SendPhoneOTPDto() # SendPhoneOTPDto | 

    try:
        # Send OTP to Phone
        api_response = api_instance.send_phone_otp(send_phone_otp_dto)
        print("The response of AuthenticationApi->send_phone_otp:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->send_phone_otp: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **send_phone_otp_dto** | [**SendPhoneOTPDto**](SendPhoneOTPDto.md)|  | 

### Return type

[**SendPhoneOTPResponseDto**](SendPhoneOTPResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | OTP sent successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **send_verification_email**
> SendVerificationEmailResponseDto send_verification_email(send_verification_email_dto)

Send Verification Email

Send a verification email to the user

### Example


```python
import cashful
from cashful.models.send_verification_email_dto import SendVerificationEmailDto
from cashful.models.send_verification_email_response_dto import SendVerificationEmailResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    send_verification_email_dto = cashful.SendVerificationEmailDto() # SendVerificationEmailDto | 

    try:
        # Send Verification Email
        api_response = api_instance.send_verification_email(send_verification_email_dto)
        print("The response of AuthenticationApi->send_verification_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->send_verification_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **send_verification_email_dto** | [**SendVerificationEmailDto**](SendVerificationEmailDto.md)|  | 

### Return type

[**SendVerificationEmailResponseDto**](SendVerificationEmailResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Verification email sent successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **set_active_organization**
> SetActiveOrganizationResponseDto set_active_organization(set_active_organization_dto)

Set Active Organization

Set the active organization for the current session

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.set_active_organization_dto import SetActiveOrganizationDto
from cashful.models.set_active_organization_response_dto import SetActiveOrganizationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    set_active_organization_dto = cashful.SetActiveOrganizationDto() # SetActiveOrganizationDto | 

    try:
        # Set Active Organization
        api_response = api_instance.set_active_organization(set_active_organization_dto)
        print("The response of AuthenticationApi->set_active_organization:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->set_active_organization: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **set_active_organization_dto** | [**SetActiveOrganizationDto**](SetActiveOrganizationDto.md)|  | 

### Return type

[**SetActiveOrganizationResponseDto**](SetActiveOrganizationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Active organization set successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sign_in_email**
> SignInResponseDto sign_in_email(sign_in_dto)

Sign in with email

Authenticate a user using email and password

### Example


```python
import cashful
from cashful.models.sign_in_dto import SignInDto
from cashful.models.sign_in_response_dto import SignInResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    sign_in_dto = cashful.SignInDto() # SignInDto | 

    try:
        # Sign in with email
        api_response = api_instance.sign_in_email(sign_in_dto)
        print("The response of AuthenticationApi->sign_in_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->sign_in_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sign_in_dto** | [**SignInDto**](SignInDto.md)|  | 

### Return type

[**SignInResponseDto**](SignInResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | User signed in successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sign_in_phone_number**
> SignInResponseDto sign_in_phone_number(sign_in_phone_number_dto)

Sign in with Phone Number

Sign in using phone number and password

### Example


```python
import cashful
from cashful.models.sign_in_phone_number_dto import SignInPhoneNumberDto
from cashful.models.sign_in_response_dto import SignInResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    sign_in_phone_number_dto = cashful.SignInPhoneNumberDto() # SignInPhoneNumberDto | 

    try:
        # Sign in with Phone Number
        api_response = api_instance.sign_in_phone_number(sign_in_phone_number_dto)
        print("The response of AuthenticationApi->sign_in_phone_number:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->sign_in_phone_number: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sign_in_phone_number_dto** | [**SignInPhoneNumberDto**](SignInPhoneNumberDto.md)|  | 

### Return type

[**SignInResponseDto**](SignInResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Signed in with phone number successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sign_out**
> SignOutResponseDto sign_out(body)

Sign out

Sign out the current user and invalidate the session

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.sign_out_response_dto import SignOutResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    body = None # object | 

    try:
        # Sign out
        api_response = api_instance.sign_out(body)
        print("The response of AuthenticationApi->sign_out:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->sign_out: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **object**|  | 

### Return type

[**SignOutResponseDto**](SignOutResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | User signed out successfully |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sign_up_email**
> SignUpResponseDto sign_up_email(sign_up_dto)

Sign up with email

Create a new user account using email and password

### Example


```python
import cashful
from cashful.models.sign_up_dto import SignUpDto
from cashful.models.sign_up_response_dto import SignUpResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    sign_up_dto = cashful.SignUpDto() # SignUpDto | 

    try:
        # Sign up with email
        api_response = api_instance.sign_up_email(sign_up_dto)
        print("The response of AuthenticationApi->sign_up_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->sign_up_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sign_up_dto** | [**SignUpDto**](SignUpDto.md)|  | 

### Return type

[**SignUpResponseDto**](SignUpResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | User created successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **social_sign_in**
> SignInResponseDto social_sign_in(social_sign_in_dto)

Sign in with social provider

Sign in with a social provider (OAuth, etc.)

### Example


```python
import cashful
from cashful.models.sign_in_response_dto import SignInResponseDto
from cashful.models.social_sign_in_dto import SocialSignInDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    social_sign_in_dto = cashful.SocialSignInDto() # SocialSignInDto | 

    try:
        # Sign in with social provider
        api_response = api_instance.social_sign_in(social_sign_in_dto)
        print("The response of AuthenticationApi->social_sign_in:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->social_sign_in: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **social_sign_in_dto** | [**SocialSignInDto**](SocialSignInDto.md)|  | 

### Return type

[**SignInResponseDto**](SignInResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully signed in with social provider |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **unlink_account**
> UnlinkAccountResponseDto unlink_account(unlink_account_dto)

Unlink Social Account

Unlink a social account from user

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.unlink_account_dto import UnlinkAccountDto
from cashful.models.unlink_account_response_dto import UnlinkAccountResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    unlink_account_dto = cashful.UnlinkAccountDto() # UnlinkAccountDto | 

    try:
        # Unlink Social Account
        api_response = api_instance.unlink_account(unlink_account_dto)
        print("The response of AuthenticationApi->unlink_account:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->unlink_account: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **unlink_account_dto** | [**UnlinkAccountDto**](UnlinkAccountDto.md)|  | 

### Return type

[**UnlinkAccountResponseDto**](UnlinkAccountResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Social account unlinked successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_api_key**
> UpdateApiKeyResponseDto update_api_key(update_api_key_dto)

Update API Key

Update an API key

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.update_api_key_dto import UpdateApiKeyDto
from cashful.models.update_api_key_response_dto import UpdateApiKeyResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    update_api_key_dto = cashful.UpdateApiKeyDto() # UpdateApiKeyDto | 

    try:
        # Update API Key
        api_response = api_instance.update_api_key(update_api_key_dto)
        print("The response of AuthenticationApi->update_api_key:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->update_api_key: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **update_api_key_dto** | [**UpdateApiKeyDto**](UpdateApiKeyDto.md)|  | 

### Return type

[**UpdateApiKeyResponseDto**](UpdateApiKeyResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | API key updated successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_member_role**
> UpdateMemberRoleResponseDto update_member_role(update_member_role_dto)

Update Member Role

Update a member's role in an organization

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.update_member_role_dto import UpdateMemberRoleDto
from cashful.models.update_member_role_response_dto import UpdateMemberRoleResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    update_member_role_dto = cashful.UpdateMemberRoleDto() # UpdateMemberRoleDto | 

    try:
        # Update Member Role
        api_response = api_instance.update_member_role(update_member_role_dto)
        print("The response of AuthenticationApi->update_member_role:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->update_member_role: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **update_member_role_dto** | [**UpdateMemberRoleDto**](UpdateMemberRoleDto.md)|  | 

### Return type

[**UpdateMemberRoleResponseDto**](UpdateMemberRoleResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Member role updated successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_organization**
> UpdateOrganizationResponseDto update_organization(update_organization_dto)

Update Organization

Update an organization's details

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.update_organization_dto import UpdateOrganizationDto
from cashful.models.update_organization_response_dto import UpdateOrganizationResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    update_organization_dto = cashful.UpdateOrganizationDto() # UpdateOrganizationDto | 

    try:
        # Update Organization
        api_response = api_instance.update_organization(update_organization_dto)
        print("The response of AuthenticationApi->update_organization:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->update_organization: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **update_organization_dto** | [**UpdateOrganizationDto**](UpdateOrganizationDto.md)|  | 

### Return type

[**UpdateOrganizationResponseDto**](UpdateOrganizationResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Organization updated successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_user**
> UpdateUserResponseDto update_user(update_user_dto)

Update User

Update the current user's information

### Example

* Bearer (JWT) Authentication (bearer):

```python
import cashful
from cashful.models.update_user_dto import UpdateUserDto
from cashful.models.update_user_response_dto import UpdateUserResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization (JWT): bearer
configuration = cashful.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    update_user_dto = cashful.UpdateUserDto() # UpdateUserDto | 

    try:
        # Update User
        api_response = api_instance.update_user(update_user_dto)
        print("The response of AuthenticationApi->update_user:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->update_user: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **update_user_dto** | [**UpdateUserDto**](UpdateUserDto.md)|  | 

### Return type

[**UpdateUserResponseDto**](UpdateUserResponseDto.md)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | User updated successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**401** | Unauthorized |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **verify_api_key**
> VerifyApiKeyResponseDto verify_api_key(verify_api_key_dto)

Verify API Key

Verify an API key

### Example


```python
import cashful
from cashful.models.verify_api_key_dto import VerifyApiKeyDto
from cashful.models.verify_api_key_response_dto import VerifyApiKeyResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    verify_api_key_dto = cashful.VerifyApiKeyDto() # VerifyApiKeyDto | 

    try:
        # Verify API Key
        api_response = api_instance.verify_api_key(verify_api_key_dto)
        print("The response of AuthenticationApi->verify_api_key:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->verify_api_key: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **verify_api_key_dto** | [**VerifyApiKeyDto**](VerifyApiKeyDto.md)|  | 

### Return type

[**VerifyApiKeyResponseDto**](VerifyApiKeyResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | API key verified successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **verify_email**
> VerifyEmailResponseDto verify_email(token, callback_url=callback_url)

Verify Email

Verify the email of a user

### Example


```python
import cashful
from cashful.models.verify_email_response_dto import VerifyEmailResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    token = 'verify_token_12345' # str | The token to verify email
    callback_url = 'https://example.com/callback' # str | The URL to redirect to after email verification (optional)

    try:
        # Verify Email
        api_response = api_instance.verify_email(token, callback_url=callback_url)
        print("The response of AuthenticationApi->verify_email:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->verify_email: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **str**| The token to verify email | 
 **callback_url** | **str**| The URL to redirect to after email verification | [optional] 

### Return type

[**VerifyEmailResponseDto**](VerifyEmailResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Email verified successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **verify_phone_number**
> VerifyPhoneNumberResponseDto verify_phone_number(verify_phone_number_dto)

Verify Phone Number

Verify phone number with OTP code

### Example


```python
import cashful
from cashful.models.verify_phone_number_dto import VerifyPhoneNumberDto
from cashful.models.verify_phone_number_response_dto import VerifyPhoneNumberResponseDto
from cashful.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:9000
# See configuration.py for a list of all supported configuration parameters.
configuration = cashful.Configuration(
    host = "http://localhost:9000"
)


# Enter a context with an instance of the API client
with cashful.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = cashful.AuthenticationApi(api_client)
    verify_phone_number_dto = cashful.VerifyPhoneNumberDto() # VerifyPhoneNumberDto | 

    try:
        # Verify Phone Number
        api_response = api_instance.verify_phone_number(verify_phone_number_dto)
        print("The response of AuthenticationApi->verify_phone_number:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AuthenticationApi->verify_phone_number: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **verify_phone_number_dto** | [**VerifyPhoneNumberDto**](VerifyPhoneNumberDto.md)|  | 

### Return type

[**VerifyPhoneNumberResponseDto**](VerifyPhoneNumberResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Phone number verified successfully |  -  |
**400** | Bad Request - Invalid input |  -  |
**500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

