# VolumeOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Blocks** | **float32** | Blocks to resize partition to. | 
**Name** | **string** | Name of partition. | 

## Methods

### NewVolumeOptions

`func NewVolumeOptions(blocks float32, name string, ) *VolumeOptions`

NewVolumeOptions instantiates a new VolumeOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVolumeOptionsWithDefaults

`func NewVolumeOptionsWithDefaults() *VolumeOptions`

NewVolumeOptionsWithDefaults instantiates a new VolumeOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlocks

`func (o *VolumeOptions) GetBlocks() float32`

GetBlocks returns the Blocks field if non-nil, zero value otherwise.

### GetBlocksOk

`func (o *VolumeOptions) GetBlocksOk() (*float32, bool)`

GetBlocksOk returns a tuple with the Blocks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocks

`func (o *VolumeOptions) SetBlocks(v float32)`

SetBlocks sets Blocks field to given value.


### GetName

`func (o *VolumeOptions) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VolumeOptions) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VolumeOptions) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


