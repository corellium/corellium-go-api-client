# TotpDisableBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotpToken** | **string** | Current TOTP token. | 
**Password** | **string** | User password. | 

## Methods

### NewTotpDisableBody

`func NewTotpDisableBody(totpToken string, password string, ) *TotpDisableBody`

NewTotpDisableBody instantiates a new TotpDisableBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTotpDisableBodyWithDefaults

`func NewTotpDisableBodyWithDefaults() *TotpDisableBody`

NewTotpDisableBodyWithDefaults instantiates a new TotpDisableBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotpToken

`func (o *TotpDisableBody) GetTotpToken() string`

GetTotpToken returns the TotpToken field if non-nil, zero value otherwise.

### GetTotpTokenOk

`func (o *TotpDisableBody) GetTotpTokenOk() (*string, bool)`

GetTotpTokenOk returns a tuple with the TotpToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpToken

`func (o *TotpDisableBody) SetTotpToken(v string)`

SetTotpToken sets TotpToken field to given value.


### GetPassword

`func (o *TotpDisableBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *TotpDisableBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *TotpDisableBody) SetPassword(v string)`

SetPassword sets Password field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


