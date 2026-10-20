# LdapGroupSearchConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GroupBaseDn** | **string** | Base DN for group search. | 
**GroupSearchFilter** | Pointer to **string** | Filter used to locate groups. | [optional] 
**TeamId** | **string** | Corellium team the group maps to. | 
**Role** | Pointer to **string** | Role granted to members of the group. | [optional] 

## Methods

### NewLdapGroupSearchConfiguration

`func NewLdapGroupSearchConfiguration(groupBaseDn string, teamId string, ) *LdapGroupSearchConfiguration`

NewLdapGroupSearchConfiguration instantiates a new LdapGroupSearchConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLdapGroupSearchConfigurationWithDefaults

`func NewLdapGroupSearchConfigurationWithDefaults() *LdapGroupSearchConfiguration`

NewLdapGroupSearchConfigurationWithDefaults instantiates a new LdapGroupSearchConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroupBaseDn

`func (o *LdapGroupSearchConfiguration) GetGroupBaseDn() string`

GetGroupBaseDn returns the GroupBaseDn field if non-nil, zero value otherwise.

### GetGroupBaseDnOk

`func (o *LdapGroupSearchConfiguration) GetGroupBaseDnOk() (*string, bool)`

GetGroupBaseDnOk returns a tuple with the GroupBaseDn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupBaseDn

`func (o *LdapGroupSearchConfiguration) SetGroupBaseDn(v string)`

SetGroupBaseDn sets GroupBaseDn field to given value.


### GetGroupSearchFilter

`func (o *LdapGroupSearchConfiguration) GetGroupSearchFilter() string`

GetGroupSearchFilter returns the GroupSearchFilter field if non-nil, zero value otherwise.

### GetGroupSearchFilterOk

`func (o *LdapGroupSearchConfiguration) GetGroupSearchFilterOk() (*string, bool)`

GetGroupSearchFilterOk returns a tuple with the GroupSearchFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupSearchFilter

`func (o *LdapGroupSearchConfiguration) SetGroupSearchFilter(v string)`

SetGroupSearchFilter sets GroupSearchFilter field to given value.

### HasGroupSearchFilter

`func (o *LdapGroupSearchConfiguration) HasGroupSearchFilter() bool`

HasGroupSearchFilter returns a boolean if a field has been set.

### GetTeamId

`func (o *LdapGroupSearchConfiguration) GetTeamId() string`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *LdapGroupSearchConfiguration) GetTeamIdOk() (*string, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *LdapGroupSearchConfiguration) SetTeamId(v string)`

SetTeamId sets TeamId field to given value.


### GetRole

`func (o *LdapGroupSearchConfiguration) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *LdapGroupSearchConfiguration) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *LdapGroupSearchConfiguration) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *LdapGroupSearchConfiguration) HasRole() bool`

HasRole returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


