# IpswFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Version** | Pointer to [**IpswVersionConstraint**](IpswVersionConstraint.md) |  | [optional] 
**Device** | Pointer to [**IpswDeviceConstraint**](IpswDeviceConstraint.md) |  | [optional] 
**Exclude** | Pointer to **NullableBool** | Exclude firmware matching this filter | [optional] 
**Include** | Pointer to **NullableBool** | Include firmware matching this filter | [optional] 

## Methods

### NewIpswFilter

`func NewIpswFilter() *IpswFilter`

NewIpswFilter instantiates a new IpswFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpswFilterWithDefaults

`func NewIpswFilterWithDefaults() *IpswFilter`

NewIpswFilterWithDefaults instantiates a new IpswFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersion

`func (o *IpswFilter) GetVersion() IpswVersionConstraint`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *IpswFilter) GetVersionOk() (*IpswVersionConstraint, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *IpswFilter) SetVersion(v IpswVersionConstraint)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *IpswFilter) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetDevice

`func (o *IpswFilter) GetDevice() IpswDeviceConstraint`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *IpswFilter) GetDeviceOk() (*IpswDeviceConstraint, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *IpswFilter) SetDevice(v IpswDeviceConstraint)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *IpswFilter) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### GetExclude

`func (o *IpswFilter) GetExclude() bool`

GetExclude returns the Exclude field if non-nil, zero value otherwise.

### GetExcludeOk

`func (o *IpswFilter) GetExcludeOk() (*bool, bool)`

GetExcludeOk returns a tuple with the Exclude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExclude

`func (o *IpswFilter) SetExclude(v bool)`

SetExclude sets Exclude field to given value.

### HasExclude

`func (o *IpswFilter) HasExclude() bool`

HasExclude returns a boolean if a field has been set.

### SetExcludeNil

`func (o *IpswFilter) SetExcludeNil(b bool)`

 SetExcludeNil sets the value for Exclude to be an explicit nil

### UnsetExclude
`func (o *IpswFilter) UnsetExclude()`

UnsetExclude ensures that no value is present for Exclude, not even an explicit nil
### GetInclude

`func (o *IpswFilter) GetInclude() bool`

GetInclude returns the Include field if non-nil, zero value otherwise.

### GetIncludeOk

`func (o *IpswFilter) GetIncludeOk() (*bool, bool)`

GetIncludeOk returns a tuple with the Include field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInclude

`func (o *IpswFilter) SetInclude(v bool)`

SetInclude sets Include field to given value.

### HasInclude

`func (o *IpswFilter) HasInclude() bool`

HasInclude returns a boolean if a field has been set.

### SetIncludeNil

`func (o *IpswFilter) SetIncludeNil(b bool)`

 SetIncludeNil sets the value for Include to be an explicit nil

### UnsetInclude
`func (o *IpswFilter) UnsetInclude()`

UnsetInclude ensures that no value is present for Include, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


