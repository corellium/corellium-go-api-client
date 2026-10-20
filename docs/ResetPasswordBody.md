# ResetPasswordBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Token** | **string** | Password reset token. | 
**NewPassword** | **string** | New password. | 
**TotpToken** | Pointer to **string** | TOTP token when two-factor is required. | [optional] 

## Methods

### NewResetPasswordBody

`func NewResetPasswordBody(token string, newPassword string, ) *ResetPasswordBody`

NewResetPasswordBody instantiates a new ResetPasswordBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResetPasswordBodyWithDefaults

`func NewResetPasswordBodyWithDefaults() *ResetPasswordBody`

NewResetPasswordBodyWithDefaults instantiates a new ResetPasswordBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToken

`func (o *ResetPasswordBody) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *ResetPasswordBody) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *ResetPasswordBody) SetToken(v string)`

SetToken sets Token field to given value.


### GetNewPassword

`func (o *ResetPasswordBody) GetNewPassword() string`

GetNewPassword returns the NewPassword field if non-nil, zero value otherwise.

### GetNewPasswordOk

`func (o *ResetPasswordBody) GetNewPasswordOk() (*string, bool)`

GetNewPasswordOk returns a tuple with the NewPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPassword

`func (o *ResetPasswordBody) SetNewPassword(v string)`

SetNewPassword sets NewPassword field to given value.


### GetTotpToken

`func (o *ResetPasswordBody) GetTotpToken() string`

GetTotpToken returns the TotpToken field if non-nil, zero value otherwise.

### GetTotpTokenOk

`func (o *ResetPasswordBody) GetTotpTokenOk() (*string, bool)`

GetTotpTokenOk returns a tuple with the TotpToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpToken

`func (o *ResetPasswordBody) SetTotpToken(v string)`

SetTotpToken sets TotpToken field to given value.

### HasTotpToken

`func (o *ResetPasswordBody) HasTotpToken() bool`

HasTotpToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


