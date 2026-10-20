# EnsureDomainSettingsResponseUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Admin user identifier. | 
**Created** | **bool** | Whether the user was newly created. | 

## Methods

### NewEnsureDomainSettingsResponseUser

`func NewEnsureDomainSettingsResponseUser(identifier string, created bool, ) *EnsureDomainSettingsResponseUser`

NewEnsureDomainSettingsResponseUser instantiates a new EnsureDomainSettingsResponseUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnsureDomainSettingsResponseUserWithDefaults

`func NewEnsureDomainSettingsResponseUserWithDefaults() *EnsureDomainSettingsResponseUser`

NewEnsureDomainSettingsResponseUserWithDefaults instantiates a new EnsureDomainSettingsResponseUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *EnsureDomainSettingsResponseUser) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *EnsureDomainSettingsResponseUser) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *EnsureDomainSettingsResponseUser) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetCreated

`func (o *EnsureDomainSettingsResponseUser) GetCreated() bool`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *EnsureDomainSettingsResponseUser) GetCreatedOk() (*bool, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *EnsureDomainSettingsResponseUser) SetCreated(v bool)`

SetCreated sets Created field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


