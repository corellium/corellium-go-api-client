# VolumeOptionsV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Blocks** | Pointer to **NullableFloat32** | blocks to resize partition to | [optional] 
**Name** | Pointer to **NullableString** | name of partition | [optional] 

## Methods

### NewVolumeOptionsV1

`func NewVolumeOptionsV1() *VolumeOptionsV1`

NewVolumeOptionsV1 instantiates a new VolumeOptionsV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeOptionsV1WithDefaults

`func NewVolumeOptionsV1WithDefaults() *VolumeOptionsV1`

NewVolumeOptionsV1WithDefaults instantiates a new VolumeOptionsV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlocks

`func (o *VolumeOptionsV1) GetBlocks() float32`

GetBlocks returns the Blocks field if non-nil, zero value otherwise.

### GetBlocksOk

`func (o *VolumeOptionsV1) GetBlocksOk() (*float32, bool)`

GetBlocksOk returns a tuple with the Blocks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocks

`func (o *VolumeOptionsV1) SetBlocks(v float32)`

SetBlocks sets Blocks field to given value.

### HasBlocks

`func (o *VolumeOptionsV1) HasBlocks() bool`

HasBlocks returns a boolean if a field has been set.

### SetBlocksNil

`func (o *VolumeOptionsV1) SetBlocksNil(b bool)`

 SetBlocksNil sets the value for Blocks to be an explicit nil

### UnsetBlocks
`func (o *VolumeOptionsV1) UnsetBlocks()`

UnsetBlocks ensures that no value is present for Blocks, not even an explicit nil
### GetName

`func (o *VolumeOptionsV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VolumeOptionsV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VolumeOptionsV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *VolumeOptionsV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *VolumeOptionsV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *VolumeOptionsV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


