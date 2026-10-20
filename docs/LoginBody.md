# LoginBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Username** | Pointer to **string** | Account username. Send together with &#x60;password&#x60;. | [optional] 
**Password** | Pointer to **string** | Account password. Send together with &#x60;username&#x60;. | [optional] 
**TotpToken** | Pointer to **string** | One-time TOTP code. Required only when the account has two-factor authentication enabled, sent alongside &#x60;username&#x60;/&#x60;password&#x60;. | [optional] 
**ApiToken** | Pointer to **string** | Persistent API key, used as an alternative to username/password for programmatic access. Created by the user (in the web UI or via &#x60;POST /v3/auth/apitoken&#x60;) rather than issued by login, and sent back verbatim as an opaque string. Also accepted directly in the &#x60;Authorization: Bearer&#x60; header, and is the value the CLI stores as &#x60;--token&#x60;. Never returned by this endpoint, and distinct from the session &#x60;token&#x60;. | [optional] 
**Token** | Pointer to **string** | An existing session token to renew. This is the signed JWT bearer token previously returned by login. Login always issues a newly-regenerated session token in the response; the supplied token is neither echoed back nor invalidated. Distinct from &#x60;apiToken&#x60;. | [optional] 
**RevokeOld** | Pointer to **bool** | Revoke previously issued tokens on success. | [optional] 

## Methods

### NewLoginBody

`func NewLoginBody() *LoginBody`

NewLoginBody instantiates a new LoginBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginBodyWithDefaults

`func NewLoginBodyWithDefaults() *LoginBody`

NewLoginBodyWithDefaults instantiates a new LoginBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsername

`func (o *LoginBody) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *LoginBody) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *LoginBody) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *LoginBody) HasUsername() bool`

HasUsername returns a boolean if a field has been set.

### GetPassword

`func (o *LoginBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *LoginBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *LoginBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *LoginBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetTotpToken

`func (o *LoginBody) GetTotpToken() string`

GetTotpToken returns the TotpToken field if non-nil, zero value otherwise.

### GetTotpTokenOk

`func (o *LoginBody) GetTotpTokenOk() (*string, bool)`

GetTotpTokenOk returns a tuple with the TotpToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpToken

`func (o *LoginBody) SetTotpToken(v string)`

SetTotpToken sets TotpToken field to given value.

### HasTotpToken

`func (o *LoginBody) HasTotpToken() bool`

HasTotpToken returns a boolean if a field has been set.

### GetApiToken

`func (o *LoginBody) GetApiToken() string`

GetApiToken returns the ApiToken field if non-nil, zero value otherwise.

### GetApiTokenOk

`func (o *LoginBody) GetApiTokenOk() (*string, bool)`

GetApiTokenOk returns a tuple with the ApiToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiToken

`func (o *LoginBody) SetApiToken(v string)`

SetApiToken sets ApiToken field to given value.

### HasApiToken

`func (o *LoginBody) HasApiToken() bool`

HasApiToken returns a boolean if a field has been set.

### GetToken

`func (o *LoginBody) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *LoginBody) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *LoginBody) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *LoginBody) HasToken() bool`

HasToken returns a boolean if a field has been set.

### GetRevokeOld

`func (o *LoginBody) GetRevokeOld() bool`

GetRevokeOld returns the RevokeOld field if non-nil, zero value otherwise.

### GetRevokeOldOk

`func (o *LoginBody) GetRevokeOldOk() (*bool, bool)`

GetRevokeOldOk returns a tuple with the RevokeOld field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokeOld

`func (o *LoginBody) SetRevokeOld(v bool)`

SetRevokeOld sets RevokeOld field to given value.

### HasRevokeOld

`func (o *LoginBody) HasRevokeOld() bool`

HasRevokeOld returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


