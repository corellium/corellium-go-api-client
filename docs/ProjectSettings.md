# ProjectSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Version** | Pointer to **float32** | Settings schema version. | [optional] 
**InternetAccess** | Pointer to **bool** | Whether devices in the project can reach the internet. When false, devices can talk only to each other and to the project VPN. | [optional] 
**Dhcp** | Pointer to **bool** | Whether DHCP is enabled for the project network. | [optional] 
**Connection** | Pointer to **NullableString** | ID of a network connection that routes the project&#39;s outbound traffic through a VPN, or null to use the normal network. Cannot be changed while any device in the project is running. | [optional] 

## Methods

### NewProjectSettings

`func NewProjectSettings() *ProjectSettings`

NewProjectSettings instantiates a new ProjectSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectSettingsWithDefaults

`func NewProjectSettingsWithDefaults() *ProjectSettings`

NewProjectSettingsWithDefaults instantiates a new ProjectSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersion

`func (o *ProjectSettings) GetVersion() float32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ProjectSettings) GetVersionOk() (*float32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ProjectSettings) SetVersion(v float32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ProjectSettings) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetInternetAccess

`func (o *ProjectSettings) GetInternetAccess() bool`

GetInternetAccess returns the InternetAccess field if non-nil, zero value otherwise.

### GetInternetAccessOk

`func (o *ProjectSettings) GetInternetAccessOk() (*bool, bool)`

GetInternetAccessOk returns a tuple with the InternetAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternetAccess

`func (o *ProjectSettings) SetInternetAccess(v bool)`

SetInternetAccess sets InternetAccess field to given value.

### HasInternetAccess

`func (o *ProjectSettings) HasInternetAccess() bool`

HasInternetAccess returns a boolean if a field has been set.

### GetDhcp

`func (o *ProjectSettings) GetDhcp() bool`

GetDhcp returns the Dhcp field if non-nil, zero value otherwise.

### GetDhcpOk

`func (o *ProjectSettings) GetDhcpOk() (*bool, bool)`

GetDhcpOk returns a tuple with the Dhcp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcp

`func (o *ProjectSettings) SetDhcp(v bool)`

SetDhcp sets Dhcp field to given value.

### HasDhcp

`func (o *ProjectSettings) HasDhcp() bool`

HasDhcp returns a boolean if a field has been set.

### GetConnection

`func (o *ProjectSettings) GetConnection() string`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *ProjectSettings) GetConnectionOk() (*string, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *ProjectSettings) SetConnection(v string)`

SetConnection sets Connection field to given value.

### HasConnection

`func (o *ProjectSettings) HasConnection() bool`

HasConnection returns a boolean if a field has been set.

### SetConnectionNil

`func (o *ProjectSettings) SetConnectionNil(b bool)`

 SetConnectionNil sets the value for Connection to be an explicit nil

### UnsetConnection
`func (o *ProjectSettings) UnsetConnection()`

UnsetConnection ensures that no value is present for Connection, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


