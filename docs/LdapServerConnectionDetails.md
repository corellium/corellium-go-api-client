# LdapServerConnectionDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServerUrl** | **string** | LDAP server URL. | 
**Port** | Pointer to **string** | LDAP server port. | [optional] 
**ConnectionTimeout** | Pointer to **string** | Connection timeout. | [optional] 
**EnableLdaps** | Pointer to **bool** | Whether to connect over LDAPS. | [optional] 
**CaCert** | Pointer to **string** | CA certificate for LDAPS. | [optional] 
**CaVerify** | Pointer to **bool** | Whether to verify the server certificate. | [optional] 

## Methods

### NewLdapServerConnectionDetails

`func NewLdapServerConnectionDetails(serverUrl string, ) *LdapServerConnectionDetails`

NewLdapServerConnectionDetails instantiates a new LdapServerConnectionDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLdapServerConnectionDetailsWithDefaults

`func NewLdapServerConnectionDetailsWithDefaults() *LdapServerConnectionDetails`

NewLdapServerConnectionDetailsWithDefaults instantiates a new LdapServerConnectionDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServerUrl

`func (o *LdapServerConnectionDetails) GetServerUrl() string`

GetServerUrl returns the ServerUrl field if non-nil, zero value otherwise.

### GetServerUrlOk

`func (o *LdapServerConnectionDetails) GetServerUrlOk() (*string, bool)`

GetServerUrlOk returns a tuple with the ServerUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerUrl

`func (o *LdapServerConnectionDetails) SetServerUrl(v string)`

SetServerUrl sets ServerUrl field to given value.


### GetPort

`func (o *LdapServerConnectionDetails) GetPort() string`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *LdapServerConnectionDetails) GetPortOk() (*string, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *LdapServerConnectionDetails) SetPort(v string)`

SetPort sets Port field to given value.

### HasPort

`func (o *LdapServerConnectionDetails) HasPort() bool`

HasPort returns a boolean if a field has been set.

### GetConnectionTimeout

`func (o *LdapServerConnectionDetails) GetConnectionTimeout() string`

GetConnectionTimeout returns the ConnectionTimeout field if non-nil, zero value otherwise.

### GetConnectionTimeoutOk

`func (o *LdapServerConnectionDetails) GetConnectionTimeoutOk() (*string, bool)`

GetConnectionTimeoutOk returns a tuple with the ConnectionTimeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionTimeout

`func (o *LdapServerConnectionDetails) SetConnectionTimeout(v string)`

SetConnectionTimeout sets ConnectionTimeout field to given value.

### HasConnectionTimeout

`func (o *LdapServerConnectionDetails) HasConnectionTimeout() bool`

HasConnectionTimeout returns a boolean if a field has been set.

### GetEnableLdaps

`func (o *LdapServerConnectionDetails) GetEnableLdaps() bool`

GetEnableLdaps returns the EnableLdaps field if non-nil, zero value otherwise.

### GetEnableLdapsOk

`func (o *LdapServerConnectionDetails) GetEnableLdapsOk() (*bool, bool)`

GetEnableLdapsOk returns a tuple with the EnableLdaps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableLdaps

`func (o *LdapServerConnectionDetails) SetEnableLdaps(v bool)`

SetEnableLdaps sets EnableLdaps field to given value.

### HasEnableLdaps

`func (o *LdapServerConnectionDetails) HasEnableLdaps() bool`

HasEnableLdaps returns a boolean if a field has been set.

### GetCaCert

`func (o *LdapServerConnectionDetails) GetCaCert() string`

GetCaCert returns the CaCert field if non-nil, zero value otherwise.

### GetCaCertOk

`func (o *LdapServerConnectionDetails) GetCaCertOk() (*string, bool)`

GetCaCertOk returns a tuple with the CaCert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaCert

`func (o *LdapServerConnectionDetails) SetCaCert(v string)`

SetCaCert sets CaCert field to given value.

### HasCaCert

`func (o *LdapServerConnectionDetails) HasCaCert() bool`

HasCaCert returns a boolean if a field has been set.

### GetCaVerify

`func (o *LdapServerConnectionDetails) GetCaVerify() bool`

GetCaVerify returns the CaVerify field if non-nil, zero value otherwise.

### GetCaVerifyOk

`func (o *LdapServerConnectionDetails) GetCaVerifyOk() (*bool, bool)`

GetCaVerifyOk returns a tuple with the CaVerify field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaVerify

`func (o *LdapServerConnectionDetails) SetCaVerify(v bool)`

SetCaVerify sets CaVerify field to given value.

### HasCaVerify

`func (o *LdapServerConnectionDetails) HasCaVerify() bool`

HasCaVerify returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


