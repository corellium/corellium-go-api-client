# TotpEnableBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Secret** | **string** | Base32-encoded TOTP secret returned by generate. | 
**TotpToken** | **string** | Current TOTP token, used to confirm the secret. | 
**Password** | **string** | User password. | 

## Methods

### NewTotpEnableBody

`func NewTotpEnableBody(secret string, totpToken string, password string, ) *TotpEnableBody`

NewTotpEnableBody instantiates a new TotpEnableBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTotpEnableBodyWithDefaults

`func NewTotpEnableBodyWithDefaults() *TotpEnableBody`

NewTotpEnableBodyWithDefaults instantiates a new TotpEnableBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSecret

`func (o *TotpEnableBody) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *TotpEnableBody) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *TotpEnableBody) SetSecret(v string)`

SetSecret sets Secret field to given value.


### GetTotpToken

`func (o *TotpEnableBody) GetTotpToken() string`

GetTotpToken returns the TotpToken field if non-nil, zero value otherwise.

### GetTotpTokenOk

`func (o *TotpEnableBody) GetTotpTokenOk() (*string, bool)`

GetTotpTokenOk returns a tuple with the TotpToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpToken

`func (o *TotpEnableBody) SetTotpToken(v string)`

SetTotpToken sets TotpToken field to given value.


### GetPassword

`func (o *TotpEnableBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *TotpEnableBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *TotpEnableBody) SetPassword(v string)`

SetPassword sets Password field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


