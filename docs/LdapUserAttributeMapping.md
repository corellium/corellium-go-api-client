# LdapUserAttributeMapping

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UsernameAttribute** | Pointer to **string** | LDAP attribute mapped to username. | [optional] 
**EmailAttribute** | Pointer to **string** | LDAP attribute mapped to email. | [optional] 
**FirstNameAttribute** | Pointer to **string** | LDAP attribute mapped to first name. | [optional] 
**LastNameAttribute** | Pointer to **string** | LDAP attribute mapped to last name. | [optional] 

## Methods

### NewLdapUserAttributeMapping

`func NewLdapUserAttributeMapping() *LdapUserAttributeMapping`

NewLdapUserAttributeMapping instantiates a new LdapUserAttributeMapping object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLdapUserAttributeMappingWithDefaults

`func NewLdapUserAttributeMappingWithDefaults() *LdapUserAttributeMapping`

NewLdapUserAttributeMappingWithDefaults instantiates a new LdapUserAttributeMapping object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsernameAttribute

`func (o *LdapUserAttributeMapping) GetUsernameAttribute() string`

GetUsernameAttribute returns the UsernameAttribute field if non-nil, zero value otherwise.

### GetUsernameAttributeOk

`func (o *LdapUserAttributeMapping) GetUsernameAttributeOk() (*string, bool)`

GetUsernameAttributeOk returns a tuple with the UsernameAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsernameAttribute

`func (o *LdapUserAttributeMapping) SetUsernameAttribute(v string)`

SetUsernameAttribute sets UsernameAttribute field to given value.

### HasUsernameAttribute

`func (o *LdapUserAttributeMapping) HasUsernameAttribute() bool`

HasUsernameAttribute returns a boolean if a field has been set.

### GetEmailAttribute

`func (o *LdapUserAttributeMapping) GetEmailAttribute() string`

GetEmailAttribute returns the EmailAttribute field if non-nil, zero value otherwise.

### GetEmailAttributeOk

`func (o *LdapUserAttributeMapping) GetEmailAttributeOk() (*string, bool)`

GetEmailAttributeOk returns a tuple with the EmailAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailAttribute

`func (o *LdapUserAttributeMapping) SetEmailAttribute(v string)`

SetEmailAttribute sets EmailAttribute field to given value.

### HasEmailAttribute

`func (o *LdapUserAttributeMapping) HasEmailAttribute() bool`

HasEmailAttribute returns a boolean if a field has been set.

### GetFirstNameAttribute

`func (o *LdapUserAttributeMapping) GetFirstNameAttribute() string`

GetFirstNameAttribute returns the FirstNameAttribute field if non-nil, zero value otherwise.

### GetFirstNameAttributeOk

`func (o *LdapUserAttributeMapping) GetFirstNameAttributeOk() (*string, bool)`

GetFirstNameAttributeOk returns a tuple with the FirstNameAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstNameAttribute

`func (o *LdapUserAttributeMapping) SetFirstNameAttribute(v string)`

SetFirstNameAttribute sets FirstNameAttribute field to given value.

### HasFirstNameAttribute

`func (o *LdapUserAttributeMapping) HasFirstNameAttribute() bool`

HasFirstNameAttribute returns a boolean if a field has been set.

### GetLastNameAttribute

`func (o *LdapUserAttributeMapping) GetLastNameAttribute() string`

GetLastNameAttribute returns the LastNameAttribute field if non-nil, zero value otherwise.

### GetLastNameAttributeOk

`func (o *LdapUserAttributeMapping) GetLastNameAttributeOk() (*string, bool)`

GetLastNameAttributeOk returns a tuple with the LastNameAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastNameAttribute

`func (o *LdapUserAttributeMapping) SetLastNameAttribute(v string)`

SetLastNameAttribute sets LastNameAttribute field to given value.

### HasLastNameAttribute

`func (o *LdapUserAttributeMapping) HasLastNameAttribute() bool`

HasLastNameAttribute returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


