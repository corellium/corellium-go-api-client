# IpswFilterV3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Version** | Pointer to [**NullableIpswFilterV3Version**](IpswFilterV3Version.md) |  | [optional] 
**Device** | Pointer to [**NullableIpswFilterV3Device**](IpswFilterV3Device.md) |  | [optional] 
**Exclude** | Pointer to **NullableBool** | Exclude firmware matching this filter. | [optional] 
**Include** | Pointer to **NullableBool** | Include firmware matching this filter. | [optional] 

## Methods

### NewIpswFilterV3

`func NewIpswFilterV3() *IpswFilterV3`

NewIpswFilterV3 instantiates a new IpswFilterV3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpswFilterV3WithDefaults

`func NewIpswFilterV3WithDefaults() *IpswFilterV3`

NewIpswFilterV3WithDefaults instantiates a new IpswFilterV3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersion

`func (o *IpswFilterV3) GetVersion() IpswFilterV3Version`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *IpswFilterV3) GetVersionOk() (*IpswFilterV3Version, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *IpswFilterV3) SetVersion(v IpswFilterV3Version)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *IpswFilterV3) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *IpswFilterV3) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *IpswFilterV3) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetDevice

`func (o *IpswFilterV3) GetDevice() IpswFilterV3Device`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *IpswFilterV3) GetDeviceOk() (*IpswFilterV3Device, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *IpswFilterV3) SetDevice(v IpswFilterV3Device)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *IpswFilterV3) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### SetDeviceNil

`func (o *IpswFilterV3) SetDeviceNil(b bool)`

 SetDeviceNil sets the value for Device to be an explicit nil

### UnsetDevice
`func (o *IpswFilterV3) UnsetDevice()`

UnsetDevice ensures that no value is present for Device, not even an explicit nil
### GetExclude

`func (o *IpswFilterV3) GetExclude() bool`

GetExclude returns the Exclude field if non-nil, zero value otherwise.

### GetExcludeOk

`func (o *IpswFilterV3) GetExcludeOk() (*bool, bool)`

GetExcludeOk returns a tuple with the Exclude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExclude

`func (o *IpswFilterV3) SetExclude(v bool)`

SetExclude sets Exclude field to given value.

### HasExclude

`func (o *IpswFilterV3) HasExclude() bool`

HasExclude returns a boolean if a field has been set.

### SetExcludeNil

`func (o *IpswFilterV3) SetExcludeNil(b bool)`

 SetExcludeNil sets the value for Exclude to be an explicit nil

### UnsetExclude
`func (o *IpswFilterV3) UnsetExclude()`

UnsetExclude ensures that no value is present for Exclude, not even an explicit nil
### GetInclude

`func (o *IpswFilterV3) GetInclude() bool`

GetInclude returns the Include field if non-nil, zero value otherwise.

### GetIncludeOk

`func (o *IpswFilterV3) GetIncludeOk() (*bool, bool)`

GetIncludeOk returns a tuple with the Include field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInclude

`func (o *IpswFilterV3) SetInclude(v bool)`

SetInclude sets Include field to given value.

### HasInclude

`func (o *IpswFilterV3) HasInclude() bool`

HasInclude returns a boolean if a field has been set.

### SetIncludeNil

`func (o *IpswFilterV3) SetIncludeNil(b bool)`

 SetIncludeNil sets the value for Include to be an explicit nil

### UnsetInclude
`func (o *IpswFilterV3) UnsetInclude()`

UnsetInclude ensures that no value is present for Include, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


