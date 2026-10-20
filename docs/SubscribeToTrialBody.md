# SubscribeToTrialBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TrialRequestCode** | Pointer to **string** | Trial request code. | [optional] 
**Password** | Pointer to **string** | Account password. | [optional] 
**TermsOfService** | Pointer to **bool** | Whether terms of service were accepted. | [optional] 
**EnterpriseDomainName** | Pointer to **string** | Enterprise domain name. | [optional] 
**Sso** | Pointer to **bool** | Whether this is an SSO-based subscription. | [optional] 
**Email** | Pointer to **string** | Requester email. | [optional] 
**Name** | Pointer to **string** | Requester name. | [optional] 
**FederatedUserId** | Pointer to **string** | Federated user identifier. | [optional] 

## Methods

### NewSubscribeToTrialBody

`func NewSubscribeToTrialBody() *SubscribeToTrialBody`

NewSubscribeToTrialBody instantiates a new SubscribeToTrialBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscribeToTrialBodyWithDefaults

`func NewSubscribeToTrialBodyWithDefaults() *SubscribeToTrialBody`

NewSubscribeToTrialBodyWithDefaults instantiates a new SubscribeToTrialBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTrialRequestCode

`func (o *SubscribeToTrialBody) GetTrialRequestCode() string`

GetTrialRequestCode returns the TrialRequestCode field if non-nil, zero value otherwise.

### GetTrialRequestCodeOk

`func (o *SubscribeToTrialBody) GetTrialRequestCodeOk() (*string, bool)`

GetTrialRequestCodeOk returns a tuple with the TrialRequestCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialRequestCode

`func (o *SubscribeToTrialBody) SetTrialRequestCode(v string)`

SetTrialRequestCode sets TrialRequestCode field to given value.

### HasTrialRequestCode

`func (o *SubscribeToTrialBody) HasTrialRequestCode() bool`

HasTrialRequestCode returns a boolean if a field has been set.

### GetPassword

`func (o *SubscribeToTrialBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *SubscribeToTrialBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *SubscribeToTrialBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *SubscribeToTrialBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetTermsOfService

`func (o *SubscribeToTrialBody) GetTermsOfService() bool`

GetTermsOfService returns the TermsOfService field if non-nil, zero value otherwise.

### GetTermsOfServiceOk

`func (o *SubscribeToTrialBody) GetTermsOfServiceOk() (*bool, bool)`

GetTermsOfServiceOk returns a tuple with the TermsOfService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsOfService

`func (o *SubscribeToTrialBody) SetTermsOfService(v bool)`

SetTermsOfService sets TermsOfService field to given value.

### HasTermsOfService

`func (o *SubscribeToTrialBody) HasTermsOfService() bool`

HasTermsOfService returns a boolean if a field has been set.

### GetEnterpriseDomainName

`func (o *SubscribeToTrialBody) GetEnterpriseDomainName() string`

GetEnterpriseDomainName returns the EnterpriseDomainName field if non-nil, zero value otherwise.

### GetEnterpriseDomainNameOk

`func (o *SubscribeToTrialBody) GetEnterpriseDomainNameOk() (*string, bool)`

GetEnterpriseDomainNameOk returns a tuple with the EnterpriseDomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseDomainName

`func (o *SubscribeToTrialBody) SetEnterpriseDomainName(v string)`

SetEnterpriseDomainName sets EnterpriseDomainName field to given value.

### HasEnterpriseDomainName

`func (o *SubscribeToTrialBody) HasEnterpriseDomainName() bool`

HasEnterpriseDomainName returns a boolean if a field has been set.

### GetSso

`func (o *SubscribeToTrialBody) GetSso() bool`

GetSso returns the Sso field if non-nil, zero value otherwise.

### GetSsoOk

`func (o *SubscribeToTrialBody) GetSsoOk() (*bool, bool)`

GetSsoOk returns a tuple with the Sso field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSso

`func (o *SubscribeToTrialBody) SetSso(v bool)`

SetSso sets Sso field to given value.

### HasSso

`func (o *SubscribeToTrialBody) HasSso() bool`

HasSso returns a boolean if a field has been set.

### GetEmail

`func (o *SubscribeToTrialBody) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SubscribeToTrialBody) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SubscribeToTrialBody) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *SubscribeToTrialBody) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetName

`func (o *SubscribeToTrialBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SubscribeToTrialBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SubscribeToTrialBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SubscribeToTrialBody) HasName() bool`

HasName returns a boolean if a field has been set.

### GetFederatedUserId

`func (o *SubscribeToTrialBody) GetFederatedUserId() string`

GetFederatedUserId returns the FederatedUserId field if non-nil, zero value otherwise.

### GetFederatedUserIdOk

`func (o *SubscribeToTrialBody) GetFederatedUserIdOk() (*string, bool)`

GetFederatedUserIdOk returns a tuple with the FederatedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFederatedUserId

`func (o *SubscribeToTrialBody) SetFederatedUserId(v string)`

SetFederatedUserId sets FederatedUserId field to given value.

### HasFederatedUserId

`func (o *SubscribeToTrialBody) HasFederatedUserId() bool`

HasFederatedUserId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


