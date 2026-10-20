# Device

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Model** | **string** |  | 
**Name** | **string** |  | 
**Platform** | Pointer to **NullableString** |  | [optional] 
**Hwmodel** | Pointer to **NullableString** |  | [optional] 
**Bdid** | Pointer to **NullableString** |  | [optional] 
**Cpid** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **NullableString** |  | [optional] 
**UpdatedAt** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDevice

`func NewDevice(type_ string, model string, name string, ) *Device`

NewDevice instantiates a new Device object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeviceWithDefaults

`func NewDeviceWithDefaults() *Device`

NewDeviceWithDefaults instantiates a new Device object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Device) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Device) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Device) SetType(v string)`

SetType sets Type field to given value.


### GetModel

`func (o *Device) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *Device) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *Device) SetModel(v string)`

SetModel sets Model field to given value.


### GetName

`func (o *Device) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Device) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Device) SetName(v string)`

SetName sets Name field to given value.


### GetPlatform

`func (o *Device) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *Device) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *Device) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *Device) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### SetPlatformNil

`func (o *Device) SetPlatformNil(b bool)`

 SetPlatformNil sets the value for Platform to be an explicit nil

### UnsetPlatform
`func (o *Device) UnsetPlatform()`

UnsetPlatform ensures that no value is present for Platform, not even an explicit nil
### GetHwmodel

`func (o *Device) GetHwmodel() string`

GetHwmodel returns the Hwmodel field if non-nil, zero value otherwise.

### GetHwmodelOk

`func (o *Device) GetHwmodelOk() (*string, bool)`

GetHwmodelOk returns a tuple with the Hwmodel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHwmodel

`func (o *Device) SetHwmodel(v string)`

SetHwmodel sets Hwmodel field to given value.

### HasHwmodel

`func (o *Device) HasHwmodel() bool`

HasHwmodel returns a boolean if a field has been set.

### SetHwmodelNil

`func (o *Device) SetHwmodelNil(b bool)`

 SetHwmodelNil sets the value for Hwmodel to be an explicit nil

### UnsetHwmodel
`func (o *Device) UnsetHwmodel()`

UnsetHwmodel ensures that no value is present for Hwmodel, not even an explicit nil
### GetBdid

`func (o *Device) GetBdid() string`

GetBdid returns the Bdid field if non-nil, zero value otherwise.

### GetBdidOk

`func (o *Device) GetBdidOk() (*string, bool)`

GetBdidOk returns a tuple with the Bdid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBdid

`func (o *Device) SetBdid(v string)`

SetBdid sets Bdid field to given value.

### HasBdid

`func (o *Device) HasBdid() bool`

HasBdid returns a boolean if a field has been set.

### SetBdidNil

`func (o *Device) SetBdidNil(b bool)`

 SetBdidNil sets the value for Bdid to be an explicit nil

### UnsetBdid
`func (o *Device) UnsetBdid()`

UnsetBdid ensures that no value is present for Bdid, not even an explicit nil
### GetCpid

`func (o *Device) GetCpid() string`

GetCpid returns the Cpid field if non-nil, zero value otherwise.

### GetCpidOk

`func (o *Device) GetCpidOk() (*string, bool)`

GetCpidOk returns a tuple with the Cpid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpid

`func (o *Device) SetCpid(v string)`

SetCpid sets Cpid field to given value.

### HasCpid

`func (o *Device) HasCpid() bool`

HasCpid returns a boolean if a field has been set.

### SetCpidNil

`func (o *Device) SetCpidNil(b bool)`

 SetCpidNil sets the value for Cpid to be an explicit nil

### UnsetCpid
`func (o *Device) UnsetCpid()`

UnsetCpid ensures that no value is present for Cpid, not even an explicit nil
### GetCreatedAt

`func (o *Device) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Device) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Device) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Device) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *Device) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Device) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *Device) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Device) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Device) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Device) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Device) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Device) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


