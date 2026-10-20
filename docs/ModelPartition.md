# ModelPartition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Partition name. | 
**BlockSize** | **float32** | Block size in bytes. | 
**Blocks** | Pointer to **float32** | Default size in blocks. | [optional] 
**BlocksMin** | Pointer to **float32** | Minimum size in blocks. | [optional] 
**BlocksMax** | Pointer to **float32** | Maximum size in blocks. | [optional] 
**BlocksStep** | Pointer to **float32** | Block increment between selectable sizes. | [optional] 
**BlockValues** | Pointer to **[]float32** | Discrete selectable sizes in blocks. | [optional] 
**UserUploaded** | Pointer to **bool** | Whether this partition can be replaced by a user-supplied image. | [optional] 

## Methods

### NewModelPartition

`func NewModelPartition(name string, blockSize float32, ) *ModelPartition`

NewModelPartition instantiates a new ModelPartition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelPartitionWithDefaults

`func NewModelPartitionWithDefaults() *ModelPartition`

NewModelPartitionWithDefaults instantiates a new ModelPartition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ModelPartition) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ModelPartition) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ModelPartition) SetName(v string)`

SetName sets Name field to given value.


### GetBlockSize

`func (o *ModelPartition) GetBlockSize() float32`

GetBlockSize returns the BlockSize field if non-nil, zero value otherwise.

### GetBlockSizeOk

`func (o *ModelPartition) GetBlockSizeOk() (*float32, bool)`

GetBlockSizeOk returns a tuple with the BlockSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockSize

`func (o *ModelPartition) SetBlockSize(v float32)`

SetBlockSize sets BlockSize field to given value.


### GetBlocks

`func (o *ModelPartition) GetBlocks() float32`

GetBlocks returns the Blocks field if non-nil, zero value otherwise.

### GetBlocksOk

`func (o *ModelPartition) GetBlocksOk() (*float32, bool)`

GetBlocksOk returns a tuple with the Blocks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocks

`func (o *ModelPartition) SetBlocks(v float32)`

SetBlocks sets Blocks field to given value.

### HasBlocks

`func (o *ModelPartition) HasBlocks() bool`

HasBlocks returns a boolean if a field has been set.

### GetBlocksMin

`func (o *ModelPartition) GetBlocksMin() float32`

GetBlocksMin returns the BlocksMin field if non-nil, zero value otherwise.

### GetBlocksMinOk

`func (o *ModelPartition) GetBlocksMinOk() (*float32, bool)`

GetBlocksMinOk returns a tuple with the BlocksMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocksMin

`func (o *ModelPartition) SetBlocksMin(v float32)`

SetBlocksMin sets BlocksMin field to given value.

### HasBlocksMin

`func (o *ModelPartition) HasBlocksMin() bool`

HasBlocksMin returns a boolean if a field has been set.

### GetBlocksMax

`func (o *ModelPartition) GetBlocksMax() float32`

GetBlocksMax returns the BlocksMax field if non-nil, zero value otherwise.

### GetBlocksMaxOk

`func (o *ModelPartition) GetBlocksMaxOk() (*float32, bool)`

GetBlocksMaxOk returns a tuple with the BlocksMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocksMax

`func (o *ModelPartition) SetBlocksMax(v float32)`

SetBlocksMax sets BlocksMax field to given value.

### HasBlocksMax

`func (o *ModelPartition) HasBlocksMax() bool`

HasBlocksMax returns a boolean if a field has been set.

### GetBlocksStep

`func (o *ModelPartition) GetBlocksStep() float32`

GetBlocksStep returns the BlocksStep field if non-nil, zero value otherwise.

### GetBlocksStepOk

`func (o *ModelPartition) GetBlocksStepOk() (*float32, bool)`

GetBlocksStepOk returns a tuple with the BlocksStep field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocksStep

`func (o *ModelPartition) SetBlocksStep(v float32)`

SetBlocksStep sets BlocksStep field to given value.

### HasBlocksStep

`func (o *ModelPartition) HasBlocksStep() bool`

HasBlocksStep returns a boolean if a field has been set.

### GetBlockValues

`func (o *ModelPartition) GetBlockValues() []float32`

GetBlockValues returns the BlockValues field if non-nil, zero value otherwise.

### GetBlockValuesOk

`func (o *ModelPartition) GetBlockValuesOk() (*[]float32, bool)`

GetBlockValuesOk returns a tuple with the BlockValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockValues

`func (o *ModelPartition) SetBlockValues(v []float32)`

SetBlockValues sets BlockValues field to given value.

### HasBlockValues

`func (o *ModelPartition) HasBlockValues() bool`

HasBlockValues returns a boolean if a field has been set.

### GetUserUploaded

`func (o *ModelPartition) GetUserUploaded() bool`

GetUserUploaded returns the UserUploaded field if non-nil, zero value otherwise.

### GetUserUploadedOk

`func (o *ModelPartition) GetUserUploadedOk() (*bool, bool)`

GetUserUploadedOk returns a tuple with the UserUploaded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserUploaded

`func (o *ModelPartition) SetUserUploaded(v bool)`

SetUserUploaded sets UserUploaded field to given value.

### HasUserUploaded

`func (o *ModelPartition) HasUserUploaded() bool`

HasUserUploaded returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


