# InstallFirmwareResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskId** | **string** | Identifier of the asynchronous install task. | 

## Methods

### NewInstallFirmwareResponse

`func NewInstallFirmwareResponse(taskId string, ) *InstallFirmwareResponse`

NewInstallFirmwareResponse instantiates a new InstallFirmwareResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstallFirmwareResponseWithDefaults

`func NewInstallFirmwareResponseWithDefaults() *InstallFirmwareResponse`

NewInstallFirmwareResponseWithDefaults instantiates a new InstallFirmwareResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskId

`func (o *InstallFirmwareResponse) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *InstallFirmwareResponse) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *InstallFirmwareResponse) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


