# ComputeNodeFileList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Files** | [**[]ComputeNodeFile**](ComputeNodeFile.md) | Files that exist on disk, oldest first. Empty when there is nothing to read. | 

## Methods

### NewComputeNodeFileList

`func NewComputeNodeFileList(files []ComputeNodeFile, ) *ComputeNodeFileList`

NewComputeNodeFileList instantiates a new ComputeNodeFileList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComputeNodeFileListWithDefaults

`func NewComputeNodeFileListWithDefaults() *ComputeNodeFileList`

NewComputeNodeFileListWithDefaults instantiates a new ComputeNodeFileList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFiles

`func (o *ComputeNodeFileList) GetFiles() []ComputeNodeFile`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *ComputeNodeFileList) GetFilesOk() (*[]ComputeNodeFile, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *ComputeNodeFileList) SetFiles(v []ComputeNodeFile)`

SetFiles sets Files field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


