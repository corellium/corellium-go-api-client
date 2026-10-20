# StorageDevice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique identifier for the storage device. | 
**Device** | **string** | Device node path (e.g. /dev/sdb1). | 
**FsType** | **string** | Filesystem type (e.g. ext4, vfat). | 
**FsUuid** | **NullableString** | Filesystem UUID. | 
**Label** | **string** | Filesystem label. | 
**Serial** | **string** | Device serial number. | 
**Vendor** | **string** | Device vendor. | 
**Model** | **string** | Device model. | 
**MountPolicy** | **string** | Mount policy for the device. | 
**Status** | **string** | Current mount status. | 
**CreatedAt** | **time.Time** | Timestamp when the record was created. | 
**UpdatedAt** | **time.Time** | Timestamp when the record was last updated. | 

## Methods

### NewStorageDevice

`func NewStorageDevice(id string, device string, fsType string, fsUuid NullableString, label string, serial string, vendor string, model string, mountPolicy string, status string, createdAt time.Time, updatedAt time.Time, ) *StorageDevice`

NewStorageDevice instantiates a new StorageDevice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStorageDeviceWithDefaults

`func NewStorageDeviceWithDefaults() *StorageDevice`

NewStorageDeviceWithDefaults instantiates a new StorageDevice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *StorageDevice) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StorageDevice) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StorageDevice) SetId(v string)`

SetId sets Id field to given value.


### GetDevice

`func (o *StorageDevice) GetDevice() string`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *StorageDevice) GetDeviceOk() (*string, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *StorageDevice) SetDevice(v string)`

SetDevice sets Device field to given value.


### GetFsType

`func (o *StorageDevice) GetFsType() string`

GetFsType returns the FsType field if non-nil, zero value otherwise.

### GetFsTypeOk

`func (o *StorageDevice) GetFsTypeOk() (*string, bool)`

GetFsTypeOk returns a tuple with the FsType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFsType

`func (o *StorageDevice) SetFsType(v string)`

SetFsType sets FsType field to given value.


### GetFsUuid

`func (o *StorageDevice) GetFsUuid() string`

GetFsUuid returns the FsUuid field if non-nil, zero value otherwise.

### GetFsUuidOk

`func (o *StorageDevice) GetFsUuidOk() (*string, bool)`

GetFsUuidOk returns a tuple with the FsUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFsUuid

`func (o *StorageDevice) SetFsUuid(v string)`

SetFsUuid sets FsUuid field to given value.


### SetFsUuidNil

`func (o *StorageDevice) SetFsUuidNil(b bool)`

 SetFsUuidNil sets the value for FsUuid to be an explicit nil

### UnsetFsUuid
`func (o *StorageDevice) UnsetFsUuid()`

UnsetFsUuid ensures that no value is present for FsUuid, not even an explicit nil
### GetLabel

`func (o *StorageDevice) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *StorageDevice) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *StorageDevice) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetSerial

`func (o *StorageDevice) GetSerial() string`

GetSerial returns the Serial field if non-nil, zero value otherwise.

### GetSerialOk

`func (o *StorageDevice) GetSerialOk() (*string, bool)`

GetSerialOk returns a tuple with the Serial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerial

`func (o *StorageDevice) SetSerial(v string)`

SetSerial sets Serial field to given value.


### GetVendor

`func (o *StorageDevice) GetVendor() string`

GetVendor returns the Vendor field if non-nil, zero value otherwise.

### GetVendorOk

`func (o *StorageDevice) GetVendorOk() (*string, bool)`

GetVendorOk returns a tuple with the Vendor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendor

`func (o *StorageDevice) SetVendor(v string)`

SetVendor sets Vendor field to given value.


### GetModel

`func (o *StorageDevice) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *StorageDevice) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *StorageDevice) SetModel(v string)`

SetModel sets Model field to given value.


### GetMountPolicy

`func (o *StorageDevice) GetMountPolicy() string`

GetMountPolicy returns the MountPolicy field if non-nil, zero value otherwise.

### GetMountPolicyOk

`func (o *StorageDevice) GetMountPolicyOk() (*string, bool)`

GetMountPolicyOk returns a tuple with the MountPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMountPolicy

`func (o *StorageDevice) SetMountPolicy(v string)`

SetMountPolicy sets MountPolicy field to given value.


### GetStatus

`func (o *StorageDevice) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StorageDevice) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StorageDevice) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *StorageDevice) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *StorageDevice) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *StorageDevice) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *StorageDevice) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *StorageDevice) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *StorageDevice) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


