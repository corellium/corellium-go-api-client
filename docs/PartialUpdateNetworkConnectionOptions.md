# PartialUpdateNetworkConnectionOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | User specified name for this network connection. e.g. My Network Connection | [optional] 
**Config** | Pointer to [**NullableUpdateNetworkConnectionOptionsConfig**](UpdateNetworkConnectionOptionsConfig.md) |  | [optional] 
**Force** | Pointer to **NullableBool** | Force the update through constraint checks (e.g. stopping active instances). Defaults to false. | [optional] 

## Methods

### NewPartialUpdateNetworkConnectionOptions

`func NewPartialUpdateNetworkConnectionOptions() *PartialUpdateNetworkConnectionOptions`

NewPartialUpdateNetworkConnectionOptions instantiates a new PartialUpdateNetworkConnectionOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartialUpdateNetworkConnectionOptionsWithDefaults

`func NewPartialUpdateNetworkConnectionOptionsWithDefaults() *PartialUpdateNetworkConnectionOptions`

NewPartialUpdateNetworkConnectionOptionsWithDefaults instantiates a new PartialUpdateNetworkConnectionOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PartialUpdateNetworkConnectionOptions) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartialUpdateNetworkConnectionOptions) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartialUpdateNetworkConnectionOptions) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PartialUpdateNetworkConnectionOptions) HasName() bool`

HasName returns a boolean if a field has been set.

### GetConfig

`func (o *PartialUpdateNetworkConnectionOptions) GetConfig() UpdateNetworkConnectionOptionsConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *PartialUpdateNetworkConnectionOptions) GetConfigOk() (*UpdateNetworkConnectionOptionsConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *PartialUpdateNetworkConnectionOptions) SetConfig(v UpdateNetworkConnectionOptionsConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *PartialUpdateNetworkConnectionOptions) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### SetConfigNil

`func (o *PartialUpdateNetworkConnectionOptions) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *PartialUpdateNetworkConnectionOptions) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetForce

`func (o *PartialUpdateNetworkConnectionOptions) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *PartialUpdateNetworkConnectionOptions) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *PartialUpdateNetworkConnectionOptions) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *PartialUpdateNetworkConnectionOptions) HasForce() bool`

HasForce returns a boolean if a field has been set.

### SetForceNil

`func (o *PartialUpdateNetworkConnectionOptions) SetForceNil(b bool)`

 SetForceNil sets the value for Force to be an explicit nil

### UnsetForce
`func (o *PartialUpdateNetworkConnectionOptions) UnsetForce()`

UnsetForce ensures that no value is present for Force, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


