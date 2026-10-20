# LdapUserSearchConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BaseDn** | **string** | Base DN for user search. | 
**UserSearchBase** | Pointer to **string** | Sub-tree to search for users. | [optional] 
**UserSearchFilter** | Pointer to **string** | Filter used to locate users. | [optional] 

## Methods

### NewLdapUserSearchConfiguration

`func NewLdapUserSearchConfiguration(baseDn string, ) *LdapUserSearchConfiguration`

NewLdapUserSearchConfiguration instantiates a new LdapUserSearchConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLdapUserSearchConfigurationWithDefaults

`func NewLdapUserSearchConfigurationWithDefaults() *LdapUserSearchConfiguration`

NewLdapUserSearchConfigurationWithDefaults instantiates a new LdapUserSearchConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBaseDn

`func (o *LdapUserSearchConfiguration) GetBaseDn() string`

GetBaseDn returns the BaseDn field if non-nil, zero value otherwise.

### GetBaseDnOk

`func (o *LdapUserSearchConfiguration) GetBaseDnOk() (*string, bool)`

GetBaseDnOk returns a tuple with the BaseDn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseDn

`func (o *LdapUserSearchConfiguration) SetBaseDn(v string)`

SetBaseDn sets BaseDn field to given value.


### GetUserSearchBase

`func (o *LdapUserSearchConfiguration) GetUserSearchBase() string`

GetUserSearchBase returns the UserSearchBase field if non-nil, zero value otherwise.

### GetUserSearchBaseOk

`func (o *LdapUserSearchConfiguration) GetUserSearchBaseOk() (*string, bool)`

GetUserSearchBaseOk returns a tuple with the UserSearchBase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserSearchBase

`func (o *LdapUserSearchConfiguration) SetUserSearchBase(v string)`

SetUserSearchBase sets UserSearchBase field to given value.

### HasUserSearchBase

`func (o *LdapUserSearchConfiguration) HasUserSearchBase() bool`

HasUserSearchBase returns a boolean if a field has been set.

### GetUserSearchFilter

`func (o *LdapUserSearchConfiguration) GetUserSearchFilter() string`

GetUserSearchFilter returns the UserSearchFilter field if non-nil, zero value otherwise.

### GetUserSearchFilterOk

`func (o *LdapUserSearchConfiguration) GetUserSearchFilterOk() (*string, bool)`

GetUserSearchFilterOk returns a tuple with the UserSearchFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserSearchFilter

`func (o *LdapUserSearchConfiguration) SetUserSearchFilter(v string)`

SetUserSearchFilter sets UserSearchFilter field to given value.

### HasUserSearchFilter

`func (o *LdapUserSearchConfiguration) HasUserSearchFilter() bool`

HasUserSearchFilter returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


