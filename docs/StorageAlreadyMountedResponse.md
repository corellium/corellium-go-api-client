# StorageAlreadyMountedResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** | Human-readable status message. | 
**MountPoint** | **string** | Filesystem path where the device is mounted. | 
**Device** | **string** | Device node path. | 

## Methods

### NewStorageAlreadyMountedResponse

`func NewStorageAlreadyMountedResponse(message string, mountPoint string, device string, ) *StorageAlreadyMountedResponse`

NewStorageAlreadyMountedResponse instantiates a new StorageAlreadyMountedResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStorageAlreadyMountedResponseWithDefaults

`func NewStorageAlreadyMountedResponseWithDefaults() *StorageAlreadyMountedResponse`

NewStorageAlreadyMountedResponseWithDefaults instantiates a new StorageAlreadyMountedResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *StorageAlreadyMountedResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *StorageAlreadyMountedResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *StorageAlreadyMountedResponse) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetMountPoint

`func (o *StorageAlreadyMountedResponse) GetMountPoint() string`

GetMountPoint returns the MountPoint field if non-nil, zero value otherwise.

### GetMountPointOk

`func (o *StorageAlreadyMountedResponse) GetMountPointOk() (*string, bool)`

GetMountPointOk returns a tuple with the MountPoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMountPoint

`func (o *StorageAlreadyMountedResponse) SetMountPoint(v string)`

SetMountPoint sets MountPoint field to given value.


### GetDevice

`func (o *StorageAlreadyMountedResponse) GetDevice() string`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *StorageAlreadyMountedResponse) GetDeviceOk() (*string, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *StorageAlreadyMountedResponse) SetDevice(v string)`

SetDevice sets Device field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


