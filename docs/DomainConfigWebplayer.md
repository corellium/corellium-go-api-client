# DomainConfigWebplayer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Whether webplayer is enabled. | 
**AllowedDomains** | Pointer to **[]string** | Allowed domains for webplayer. | [optional] 

## Methods

### NewDomainConfigWebplayer

`func NewDomainConfigWebplayer(enabled bool, ) *DomainConfigWebplayer`

NewDomainConfigWebplayer instantiates a new DomainConfigWebplayer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainConfigWebplayerWithDefaults

`func NewDomainConfigWebplayerWithDefaults() *DomainConfigWebplayer`

NewDomainConfigWebplayerWithDefaults instantiates a new DomainConfigWebplayer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *DomainConfigWebplayer) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DomainConfigWebplayer) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DomainConfigWebplayer) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetAllowedDomains

`func (o *DomainConfigWebplayer) GetAllowedDomains() []string`

GetAllowedDomains returns the AllowedDomains field if non-nil, zero value otherwise.

### GetAllowedDomainsOk

`func (o *DomainConfigWebplayer) GetAllowedDomainsOk() (*[]string, bool)`

GetAllowedDomainsOk returns a tuple with the AllowedDomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedDomains

`func (o *DomainConfigWebplayer) SetAllowedDomains(v []string)`

SetAllowedDomains sets AllowedDomains field to given value.

### HasAllowedDomains

`func (o *DomainConfigWebplayer) HasAllowedDomains() bool`

HasAllowedDomains returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


