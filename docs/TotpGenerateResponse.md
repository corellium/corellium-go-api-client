# TotpGenerateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**QrCode** | **string** | TOTP otpauth URL encoded as a data-URL QR code. | 
**Secret** | **string** | Base32-encoded TOTP secret. | 

## Methods

### NewTotpGenerateResponse

`func NewTotpGenerateResponse(qrCode string, secret string, ) *TotpGenerateResponse`

NewTotpGenerateResponse instantiates a new TotpGenerateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTotpGenerateResponseWithDefaults

`func NewTotpGenerateResponseWithDefaults() *TotpGenerateResponse`

NewTotpGenerateResponseWithDefaults instantiates a new TotpGenerateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQrCode

`func (o *TotpGenerateResponse) GetQrCode() string`

GetQrCode returns the QrCode field if non-nil, zero value otherwise.

### GetQrCodeOk

`func (o *TotpGenerateResponse) GetQrCodeOk() (*string, bool)`

GetQrCodeOk returns a tuple with the QrCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrCode

`func (o *TotpGenerateResponse) SetQrCode(v string)`

SetQrCode sets QrCode field to given value.


### GetSecret

`func (o *TotpGenerateResponse) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *TotpGenerateResponse) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *TotpGenerateResponse) SetSecret(v string)`

SetSecret sets Secret field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


