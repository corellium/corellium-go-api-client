# SamlUserAttributeMapping

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Username** | Pointer to **string** | SAML assertion attribute mapped to username. | [optional] 
**Email** | **string** | SAML assertion attribute mapped to email. | 
**FirstName** | **string** | SAML assertion attribute mapped to first name. | 
**LastName** | **string** | SAML assertion attribute mapped to last name. | 
**Group** | **string** | SAML assertion attribute mapped to group. | 

## Methods

### NewSamlUserAttributeMapping

`func NewSamlUserAttributeMapping(email string, firstName string, lastName string, group string, ) *SamlUserAttributeMapping`

NewSamlUserAttributeMapping instantiates a new SamlUserAttributeMapping object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSamlUserAttributeMappingWithDefaults

`func NewSamlUserAttributeMappingWithDefaults() *SamlUserAttributeMapping`

NewSamlUserAttributeMappingWithDefaults instantiates a new SamlUserAttributeMapping object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsername

`func (o *SamlUserAttributeMapping) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *SamlUserAttributeMapping) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *SamlUserAttributeMapping) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *SamlUserAttributeMapping) HasUsername() bool`

HasUsername returns a boolean if a field has been set.

### GetEmail

`func (o *SamlUserAttributeMapping) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SamlUserAttributeMapping) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SamlUserAttributeMapping) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetFirstName

`func (o *SamlUserAttributeMapping) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *SamlUserAttributeMapping) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *SamlUserAttributeMapping) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *SamlUserAttributeMapping) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *SamlUserAttributeMapping) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *SamlUserAttributeMapping) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetGroup

`func (o *SamlUserAttributeMapping) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *SamlUserAttributeMapping) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *SamlUserAttributeMapping) SetGroup(v string)`

SetGroup sets Group field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


