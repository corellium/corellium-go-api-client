# InviteSignupBodyParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | Pointer to **string** | Account email. | [optional] 
**Password** | **string** | Account password. | 
**Label** | **string** | Account label. | 
**Agreed** | **bool** | Whether the invitee agreed to the terms of service. | 

## Methods

### NewInviteSignupBodyParams

`func NewInviteSignupBodyParams(password string, label string, agreed bool, ) *InviteSignupBodyParams`

NewInviteSignupBodyParams instantiates a new InviteSignupBodyParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteSignupBodyParamsWithDefaults

`func NewInviteSignupBodyParamsWithDefaults() *InviteSignupBodyParams`

NewInviteSignupBodyParamsWithDefaults instantiates a new InviteSignupBodyParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *InviteSignupBodyParams) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *InviteSignupBodyParams) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *InviteSignupBodyParams) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *InviteSignupBodyParams) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetPassword

`func (o *InviteSignupBodyParams) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *InviteSignupBodyParams) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *InviteSignupBodyParams) SetPassword(v string)`

SetPassword sets Password field to given value.


### GetLabel

`func (o *InviteSignupBodyParams) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *InviteSignupBodyParams) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *InviteSignupBodyParams) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetAgreed

`func (o *InviteSignupBodyParams) GetAgreed() bool`

GetAgreed returns the Agreed field if non-nil, zero value otherwise.

### GetAgreedOk

`func (o *InviteSignupBodyParams) GetAgreedOk() (*bool, bool)`

GetAgreedOk returns a tuple with the Agreed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgreed

`func (o *InviteSignupBodyParams) SetAgreed(v bool)`

SetAgreed sets Agreed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


