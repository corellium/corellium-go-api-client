# ComputeNodeFile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Path** | **string** | Absolute path to the file on the compute node. | 
**Size** | **float32** | Size of the file in bytes. | 
**Mtime** | **time.Time** | Time the file was last modified. | 

## Methods

### NewComputeNodeFile

`func NewComputeNodeFile(path string, size float32, mtime time.Time, ) *ComputeNodeFile`

NewComputeNodeFile instantiates a new ComputeNodeFile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComputeNodeFileWithDefaults

`func NewComputeNodeFileWithDefaults() *ComputeNodeFile`

NewComputeNodeFileWithDefaults instantiates a new ComputeNodeFile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPath

`func (o *ComputeNodeFile) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ComputeNodeFile) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ComputeNodeFile) SetPath(v string)`

SetPath sets Path field to given value.


### GetSize

`func (o *ComputeNodeFile) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *ComputeNodeFile) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *ComputeNodeFile) SetSize(v float32)`

SetSize sets Size field to given value.


### GetMtime

`func (o *ComputeNodeFile) GetMtime() time.Time`

GetMtime returns the Mtime field if non-nil, zero value otherwise.

### GetMtimeOk

`func (o *ComputeNodeFile) GetMtimeOk() (*time.Time, bool)`

GetMtimeOk returns a tuple with the Mtime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMtime

`func (o *ComputeNodeFile) SetMtime(v time.Time)`

SetMtime sets Mtime field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


