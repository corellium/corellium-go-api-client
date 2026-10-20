# MediaStore

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Storage device identifier. | 
**Device** | **string** | Device name. | 
**FsType** | **string** | Filesystem type. | 
**FsUuid** | **NullableString** | Filesystem UUID. | 
**Label** | **string** | Volume label. | 
**Serial** | **string** | Device serial number. | 
**Vendor** | **string** | Device vendor. | 
**Model** | **string** | Device model. | 
**MountPolicy** | **string** | Mount policy (read-only or read-write). | 
**Status** | **string** | Mount status. | 
**CreatedAt** | **time.Time** | Creation timestamp. | 
**UpdatedAt** | **time.Time** | Last update timestamp. | 

## Methods

### NewMediaStore

`func NewMediaStore(identifier string, device string, fsType string, fsUuid NullableString, label string, serial string, vendor string, model string, mountPolicy string, status string, createdAt time.Time, updatedAt time.Time, ) *MediaStore`

NewMediaStore instantiates a new MediaStore object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMediaStoreWithDefaults

`func NewMediaStoreWithDefaults() *MediaStore`

NewMediaStoreWithDefaults instantiates a new MediaStore object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *MediaStore) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *MediaStore) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *MediaStore) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetDevice

`func (o *MediaStore) GetDevice() string`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *MediaStore) GetDeviceOk() (*string, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *MediaStore) SetDevice(v string)`

SetDevice sets Device field to given value.


### GetFsType

`func (o *MediaStore) GetFsType() string`

GetFsType returns the FsType field if non-nil, zero value otherwise.

### GetFsTypeOk

`func (o *MediaStore) GetFsTypeOk() (*string, bool)`

GetFsTypeOk returns a tuple with the FsType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFsType

`func (o *MediaStore) SetFsType(v string)`

SetFsType sets FsType field to given value.


### GetFsUuid

`func (o *MediaStore) GetFsUuid() string`

GetFsUuid returns the FsUuid field if non-nil, zero value otherwise.

### GetFsUuidOk

`func (o *MediaStore) GetFsUuidOk() (*string, bool)`

GetFsUuidOk returns a tuple with the FsUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFsUuid

`func (o *MediaStore) SetFsUuid(v string)`

SetFsUuid sets FsUuid field to given value.


### SetFsUuidNil

`func (o *MediaStore) SetFsUuidNil(b bool)`

 SetFsUuidNil sets the value for FsUuid to be an explicit nil

### UnsetFsUuid
`func (o *MediaStore) UnsetFsUuid()`

UnsetFsUuid ensures that no value is present for FsUuid, not even an explicit nil
### GetLabel

`func (o *MediaStore) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *MediaStore) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *MediaStore) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetSerial

`func (o *MediaStore) GetSerial() string`

GetSerial returns the Serial field if non-nil, zero value otherwise.

### GetSerialOk

`func (o *MediaStore) GetSerialOk() (*string, bool)`

GetSerialOk returns a tuple with the Serial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerial

`func (o *MediaStore) SetSerial(v string)`

SetSerial sets Serial field to given value.


### GetVendor

`func (o *MediaStore) GetVendor() string`

GetVendor returns the Vendor field if non-nil, zero value otherwise.

### GetVendorOk

`func (o *MediaStore) GetVendorOk() (*string, bool)`

GetVendorOk returns a tuple with the Vendor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendor

`func (o *MediaStore) SetVendor(v string)`

SetVendor sets Vendor field to given value.


### GetModel

`func (o *MediaStore) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *MediaStore) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *MediaStore) SetModel(v string)`

SetModel sets Model field to given value.


### GetMountPolicy

`func (o *MediaStore) GetMountPolicy() string`

GetMountPolicy returns the MountPolicy field if non-nil, zero value otherwise.

### GetMountPolicyOk

`func (o *MediaStore) GetMountPolicyOk() (*string, bool)`

GetMountPolicyOk returns a tuple with the MountPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMountPolicy

`func (o *MediaStore) SetMountPolicy(v string)`

SetMountPolicy sets MountPolicy field to given value.


### GetStatus

`func (o *MediaStore) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MediaStore) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MediaStore) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *MediaStore) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MediaStore) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MediaStore) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *MediaStore) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *MediaStore) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *MediaStore) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


