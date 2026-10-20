# ProjectSettingsV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Version** | Pointer to **NullableFloat32** |  | [optional] 
**InternetAccess** | Pointer to **NullableBool** | Omitted when not configured for the project | [optional] 
**Connection** | Pointer to **NullableString** | UUIDv4 network connection identifier or null for no vpn connection | [optional] 
**Dhcp** | Pointer to **NullableBool** | Omitted when not configured for the project | [optional] 

## Methods

### NewProjectSettingsV1

`func NewProjectSettingsV1() *ProjectSettingsV1`

NewProjectSettingsV1 instantiates a new ProjectSettingsV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectSettingsV1WithDefaults

`func NewProjectSettingsV1WithDefaults() *ProjectSettingsV1`

NewProjectSettingsV1WithDefaults instantiates a new ProjectSettingsV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersion

`func (o *ProjectSettingsV1) GetVersion() float32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ProjectSettingsV1) GetVersionOk() (*float32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ProjectSettingsV1) SetVersion(v float32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ProjectSettingsV1) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *ProjectSettingsV1) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *ProjectSettingsV1) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetInternetAccess

`func (o *ProjectSettingsV1) GetInternetAccess() bool`

GetInternetAccess returns the InternetAccess field if non-nil, zero value otherwise.

### GetInternetAccessOk

`func (o *ProjectSettingsV1) GetInternetAccessOk() (*bool, bool)`

GetInternetAccessOk returns a tuple with the InternetAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternetAccess

`func (o *ProjectSettingsV1) SetInternetAccess(v bool)`

SetInternetAccess sets InternetAccess field to given value.

### HasInternetAccess

`func (o *ProjectSettingsV1) HasInternetAccess() bool`

HasInternetAccess returns a boolean if a field has been set.

### SetInternetAccessNil

`func (o *ProjectSettingsV1) SetInternetAccessNil(b bool)`

 SetInternetAccessNil sets the value for InternetAccess to be an explicit nil

### UnsetInternetAccess
`func (o *ProjectSettingsV1) UnsetInternetAccess()`

UnsetInternetAccess ensures that no value is present for InternetAccess, not even an explicit nil
### GetConnection

`func (o *ProjectSettingsV1) GetConnection() string`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *ProjectSettingsV1) GetConnectionOk() (*string, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *ProjectSettingsV1) SetConnection(v string)`

SetConnection sets Connection field to given value.

### HasConnection

`func (o *ProjectSettingsV1) HasConnection() bool`

HasConnection returns a boolean if a field has been set.

### SetConnectionNil

`func (o *ProjectSettingsV1) SetConnectionNil(b bool)`

 SetConnectionNil sets the value for Connection to be an explicit nil

### UnsetConnection
`func (o *ProjectSettingsV1) UnsetConnection()`

UnsetConnection ensures that no value is present for Connection, not even an explicit nil
### GetDhcp

`func (o *ProjectSettingsV1) GetDhcp() bool`

GetDhcp returns the Dhcp field if non-nil, zero value otherwise.

### GetDhcpOk

`func (o *ProjectSettingsV1) GetDhcpOk() (*bool, bool)`

GetDhcpOk returns a tuple with the Dhcp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcp

`func (o *ProjectSettingsV1) SetDhcp(v bool)`

SetDhcp sets Dhcp field to given value.

### HasDhcp

`func (o *ProjectSettingsV1) HasDhcp() bool`

HasDhcp returns a boolean if a field has been set.

### SetDhcpNil

`func (o *ProjectSettingsV1) SetDhcpNil(b bool)`

 SetDhcpNil sets the value for Dhcp to be an explicit nil

### UnsetDhcp
`func (o *ProjectSettingsV1) UnsetDhcp()`

UnsetDhcp ensures that no value is present for Dhcp, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


