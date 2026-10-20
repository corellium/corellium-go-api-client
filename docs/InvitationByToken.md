# InvitationByToken

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Invite ID. | 
**Email** | **string** | Invited email address. | 
**Domain** | **string** | Domain name. | 
**DisplayName** | **string** | Domain display name. | 
**TermsAgreementRequired** | **bool** | Whether the invitee must agree to terms. | 
**Settings** | [**InviteSettings**](InviteSettings.md) |  | 

## Methods

### NewInvitationByToken

`func NewInvitationByToken(id string, email string, domain string, displayName string, termsAgreementRequired bool, settings InviteSettings, ) *InvitationByToken`

NewInvitationByToken instantiates a new InvitationByToken object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvitationByTokenWithDefaults

`func NewInvitationByTokenWithDefaults() *InvitationByToken`

NewInvitationByTokenWithDefaults instantiates a new InvitationByToken object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InvitationByToken) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InvitationByToken) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InvitationByToken) SetId(v string)`

SetId sets Id field to given value.


### GetEmail

`func (o *InvitationByToken) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *InvitationByToken) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *InvitationByToken) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetDomain

`func (o *InvitationByToken) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *InvitationByToken) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *InvitationByToken) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetDisplayName

`func (o *InvitationByToken) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *InvitationByToken) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *InvitationByToken) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.


### GetTermsAgreementRequired

`func (o *InvitationByToken) GetTermsAgreementRequired() bool`

GetTermsAgreementRequired returns the TermsAgreementRequired field if non-nil, zero value otherwise.

### GetTermsAgreementRequiredOk

`func (o *InvitationByToken) GetTermsAgreementRequiredOk() (*bool, bool)`

GetTermsAgreementRequiredOk returns a tuple with the TermsAgreementRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsAgreementRequired

`func (o *InvitationByToken) SetTermsAgreementRequired(v bool)`

SetTermsAgreementRequired sets TermsAgreementRequired field to given value.


### GetSettings

`func (o *InvitationByToken) GetSettings() InviteSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *InvitationByToken) GetSettingsOk() (*InviteSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *InvitationByToken) SetSettings(v InviteSettings)`

SetSettings sets Settings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


