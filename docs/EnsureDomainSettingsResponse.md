# EnsureDomainSettingsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **bool** | Whether the domain was newly created. | 
**Identifier** | **string** | Domain identifier. | 
**User** | [**EnsureDomainSettingsResponseUser**](EnsureDomainSettingsResponseUser.md) |  | 

## Methods

### NewEnsureDomainSettingsResponse

`func NewEnsureDomainSettingsResponse(created bool, identifier string, user EnsureDomainSettingsResponseUser, ) *EnsureDomainSettingsResponse`

NewEnsureDomainSettingsResponse instantiates a new EnsureDomainSettingsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnsureDomainSettingsResponseWithDefaults

`func NewEnsureDomainSettingsResponseWithDefaults() *EnsureDomainSettingsResponse`

NewEnsureDomainSettingsResponseWithDefaults instantiates a new EnsureDomainSettingsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *EnsureDomainSettingsResponse) GetCreated() bool`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *EnsureDomainSettingsResponse) GetCreatedOk() (*bool, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *EnsureDomainSettingsResponse) SetCreated(v bool)`

SetCreated sets Created field to given value.


### GetIdentifier

`func (o *EnsureDomainSettingsResponse) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *EnsureDomainSettingsResponse) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *EnsureDomainSettingsResponse) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetUser

`func (o *EnsureDomainSettingsResponse) GetUser() EnsureDomainSettingsResponseUser`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *EnsureDomainSettingsResponse) GetUserOk() (*EnsureDomainSettingsResponseUser, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *EnsureDomainSettingsResponse) SetUser(v EnsureDomainSettingsResponseUser)`

SetUser sets User field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


