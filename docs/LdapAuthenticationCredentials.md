# LdapAuthenticationCredentials

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BindDn** | **string** | Bind DN used to authenticate to the LDAP server. | 
**BindPassword** | **string** | Bind password. | 

## Methods

### NewLdapAuthenticationCredentials

`func NewLdapAuthenticationCredentials(bindDn string, bindPassword string, ) *LdapAuthenticationCredentials`

NewLdapAuthenticationCredentials instantiates a new LdapAuthenticationCredentials object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLdapAuthenticationCredentialsWithDefaults

`func NewLdapAuthenticationCredentialsWithDefaults() *LdapAuthenticationCredentials`

NewLdapAuthenticationCredentialsWithDefaults instantiates a new LdapAuthenticationCredentials object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBindDn

`func (o *LdapAuthenticationCredentials) GetBindDn() string`

GetBindDn returns the BindDn field if non-nil, zero value otherwise.

### GetBindDnOk

`func (o *LdapAuthenticationCredentials) GetBindDnOk() (*string, bool)`

GetBindDnOk returns a tuple with the BindDn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBindDn

`func (o *LdapAuthenticationCredentials) SetBindDn(v string)`

SetBindDn sets BindDn field to given value.


### GetBindPassword

`func (o *LdapAuthenticationCredentials) GetBindPassword() string`

GetBindPassword returns the BindPassword field if non-nil, zero value otherwise.

### GetBindPasswordOk

`func (o *LdapAuthenticationCredentials) GetBindPasswordOk() (*string, bool)`

GetBindPasswordOk returns a tuple with the BindPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBindPassword

`func (o *LdapAuthenticationCredentials) SetBindPassword(v string)`

SetBindPassword sets BindPassword field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


