# ClusterConfigIpswFiltersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | Pointer to [**ClusterConfigIpswFiltersInnerDevice**](ClusterConfigIpswFiltersInnerDevice.md) |  | [optional] 
**Version** | Pointer to [**ClusterConfigIpswFiltersInnerVersion**](ClusterConfigIpswFiltersInnerVersion.md) |  | [optional] 
**Include** | Pointer to **bool** |  | [optional] 
**Exclude** | Pointer to **bool** |  | [optional] 

## Methods

### NewClusterConfigIpswFiltersInner

`func NewClusterConfigIpswFiltersInner() *ClusterConfigIpswFiltersInner`

NewClusterConfigIpswFiltersInner instantiates a new ClusterConfigIpswFiltersInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterConfigIpswFiltersInnerWithDefaults

`func NewClusterConfigIpswFiltersInnerWithDefaults() *ClusterConfigIpswFiltersInner`

NewClusterConfigIpswFiltersInnerWithDefaults instantiates a new ClusterConfigIpswFiltersInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevice

`func (o *ClusterConfigIpswFiltersInner) GetDevice() ClusterConfigIpswFiltersInnerDevice`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *ClusterConfigIpswFiltersInner) GetDeviceOk() (*ClusterConfigIpswFiltersInnerDevice, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *ClusterConfigIpswFiltersInner) SetDevice(v ClusterConfigIpswFiltersInnerDevice)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *ClusterConfigIpswFiltersInner) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### GetVersion

`func (o *ClusterConfigIpswFiltersInner) GetVersion() ClusterConfigIpswFiltersInnerVersion`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ClusterConfigIpswFiltersInner) GetVersionOk() (*ClusterConfigIpswFiltersInnerVersion, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ClusterConfigIpswFiltersInner) SetVersion(v ClusterConfigIpswFiltersInnerVersion)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ClusterConfigIpswFiltersInner) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetInclude

`func (o *ClusterConfigIpswFiltersInner) GetInclude() bool`

GetInclude returns the Include field if non-nil, zero value otherwise.

### GetIncludeOk

`func (o *ClusterConfigIpswFiltersInner) GetIncludeOk() (*bool, bool)`

GetIncludeOk returns a tuple with the Include field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInclude

`func (o *ClusterConfigIpswFiltersInner) SetInclude(v bool)`

SetInclude sets Include field to given value.

### HasInclude

`func (o *ClusterConfigIpswFiltersInner) HasInclude() bool`

HasInclude returns a boolean if a field has been set.

### GetExclude

`func (o *ClusterConfigIpswFiltersInner) GetExclude() bool`

GetExclude returns the Exclude field if non-nil, zero value otherwise.

### GetExcludeOk

`func (o *ClusterConfigIpswFiltersInner) GetExcludeOk() (*bool, bool)`

GetExcludeOk returns a tuple with the Exclude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExclude

`func (o *ClusterConfigIpswFiltersInner) SetExclude(v bool)`

SetExclude sets Exclude field to given value.

### HasExclude

`func (o *ClusterConfigIpswFiltersInner) HasExclude() bool`

HasExclude returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


