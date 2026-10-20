# InstanceUpgradeBodyV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Os** | **string** | iOS version | 
**Osbuild** | Pointer to **NullableString** | (optional) iOS build ID | [optional] 

## Methods

### NewInstanceUpgradeBodyV1

`func NewInstanceUpgradeBodyV1(os string, ) *InstanceUpgradeBodyV1`

NewInstanceUpgradeBodyV1 instantiates a new InstanceUpgradeBodyV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceUpgradeBodyV1WithDefaults

`func NewInstanceUpgradeBodyV1WithDefaults() *InstanceUpgradeBodyV1`

NewInstanceUpgradeBodyV1WithDefaults instantiates a new InstanceUpgradeBodyV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOs

`func (o *InstanceUpgradeBodyV1) GetOs() string`

GetOs returns the Os field if non-nil, zero value otherwise.

### GetOsOk

`func (o *InstanceUpgradeBodyV1) GetOsOk() (*string, bool)`

GetOsOk returns a tuple with the Os field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOs

`func (o *InstanceUpgradeBodyV1) SetOs(v string)`

SetOs sets Os field to given value.


### GetOsbuild

`func (o *InstanceUpgradeBodyV1) GetOsbuild() string`

GetOsbuild returns the Osbuild field if non-nil, zero value otherwise.

### GetOsbuildOk

`func (o *InstanceUpgradeBodyV1) GetOsbuildOk() (*string, bool)`

GetOsbuildOk returns a tuple with the Osbuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsbuild

`func (o *InstanceUpgradeBodyV1) SetOsbuild(v string)`

SetOsbuild sets Osbuild field to given value.

### HasOsbuild

`func (o *InstanceUpgradeBodyV1) HasOsbuild() bool`

HasOsbuild returns a boolean if a field has been set.

### SetOsbuildNil

`func (o *InstanceUpgradeBodyV1) SetOsbuildNil(b bool)`

 SetOsbuildNil sets the value for Osbuild to be an explicit nil

### UnsetOsbuild
`func (o *InstanceUpgradeBodyV1) UnsetOsbuild()`

UnsetOsbuild ensures that no value is present for Osbuild, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


