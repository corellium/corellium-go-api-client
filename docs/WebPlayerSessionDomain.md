# WebPlayerSessionDomain

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Domain name. | 
**Label** | Pointer to **NullableString** | Domain description/label. | [optional] 
**TermsPolicy** | Pointer to **NullableString** | Domain terms policy. | [optional] 
**Cores** | Pointer to **float32** | Core quota for the domain. | [optional] 
**Individual** | Pointer to **bool** | Whether the domain is an individual account nested under an aggregate parent domain. | [optional] 
**TotpRequired** | Pointer to **bool** | Whether two-factor is required for the domain. | [optional] 

## Methods

### NewWebPlayerSessionDomain

`func NewWebPlayerSessionDomain(name string, ) *WebPlayerSessionDomain`

NewWebPlayerSessionDomain instantiates a new WebPlayerSessionDomain object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebPlayerSessionDomainWithDefaults

`func NewWebPlayerSessionDomainWithDefaults() *WebPlayerSessionDomain`

NewWebPlayerSessionDomainWithDefaults instantiates a new WebPlayerSessionDomain object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *WebPlayerSessionDomain) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WebPlayerSessionDomain) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WebPlayerSessionDomain) SetName(v string)`

SetName sets Name field to given value.


### GetLabel

`func (o *WebPlayerSessionDomain) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *WebPlayerSessionDomain) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *WebPlayerSessionDomain) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *WebPlayerSessionDomain) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *WebPlayerSessionDomain) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *WebPlayerSessionDomain) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetTermsPolicy

`func (o *WebPlayerSessionDomain) GetTermsPolicy() string`

GetTermsPolicy returns the TermsPolicy field if non-nil, zero value otherwise.

### GetTermsPolicyOk

`func (o *WebPlayerSessionDomain) GetTermsPolicyOk() (*string, bool)`

GetTermsPolicyOk returns a tuple with the TermsPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsPolicy

`func (o *WebPlayerSessionDomain) SetTermsPolicy(v string)`

SetTermsPolicy sets TermsPolicy field to given value.

### HasTermsPolicy

`func (o *WebPlayerSessionDomain) HasTermsPolicy() bool`

HasTermsPolicy returns a boolean if a field has been set.

### SetTermsPolicyNil

`func (o *WebPlayerSessionDomain) SetTermsPolicyNil(b bool)`

 SetTermsPolicyNil sets the value for TermsPolicy to be an explicit nil

### UnsetTermsPolicy
`func (o *WebPlayerSessionDomain) UnsetTermsPolicy()`

UnsetTermsPolicy ensures that no value is present for TermsPolicy, not even an explicit nil
### GetCores

`func (o *WebPlayerSessionDomain) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *WebPlayerSessionDomain) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *WebPlayerSessionDomain) SetCores(v float32)`

SetCores sets Cores field to given value.

### HasCores

`func (o *WebPlayerSessionDomain) HasCores() bool`

HasCores returns a boolean if a field has been set.

### GetIndividual

`func (o *WebPlayerSessionDomain) GetIndividual() bool`

GetIndividual returns the Individual field if non-nil, zero value otherwise.

### GetIndividualOk

`func (o *WebPlayerSessionDomain) GetIndividualOk() (*bool, bool)`

GetIndividualOk returns a tuple with the Individual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndividual

`func (o *WebPlayerSessionDomain) SetIndividual(v bool)`

SetIndividual sets Individual field to given value.

### HasIndividual

`func (o *WebPlayerSessionDomain) HasIndividual() bool`

HasIndividual returns a boolean if a field has been set.

### GetTotpRequired

`func (o *WebPlayerSessionDomain) GetTotpRequired() bool`

GetTotpRequired returns the TotpRequired field if non-nil, zero value otherwise.

### GetTotpRequiredOk

`func (o *WebPlayerSessionDomain) GetTotpRequiredOk() (*bool, bool)`

GetTotpRequiredOk returns a tuple with the TotpRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpRequired

`func (o *WebPlayerSessionDomain) SetTotpRequired(v bool)`

SetTotpRequired sets TotpRequired field to given value.

### HasTotpRequired

`func (o *WebPlayerSessionDomain) HasTotpRequired() bool`

HasTotpRequired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


