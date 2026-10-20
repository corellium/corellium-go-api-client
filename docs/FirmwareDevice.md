# FirmwareDevice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Device type. | [optional] 
**Model** | **string** | Device model. | 
**Name** | **string** | Device name. | 
**Platform** | Pointer to **string** | Device platform. | [optional] 
**HwModel** | Pointer to **string** | Hardware model. | [optional] 
**Bdid** | Pointer to **string** | Board ID. | [optional] 
**Cpid** | Pointer to **string** | Chip ID. | [optional] 
**CreatedAt** | Pointer to **time.Time** | Creation timestamp. | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Last update timestamp. | [optional] 

## Methods

### NewFirmwareDevice

`func NewFirmwareDevice(model string, name string, ) *FirmwareDevice`

NewFirmwareDevice instantiates a new FirmwareDevice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareDeviceWithDefaults

`func NewFirmwareDeviceWithDefaults() *FirmwareDevice`

NewFirmwareDeviceWithDefaults instantiates a new FirmwareDevice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *FirmwareDevice) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *FirmwareDevice) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *FirmwareDevice) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *FirmwareDevice) HasType() bool`

HasType returns a boolean if a field has been set.

### GetModel

`func (o *FirmwareDevice) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *FirmwareDevice) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *FirmwareDevice) SetModel(v string)`

SetModel sets Model field to given value.


### GetName

`func (o *FirmwareDevice) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FirmwareDevice) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FirmwareDevice) SetName(v string)`

SetName sets Name field to given value.


### GetPlatform

`func (o *FirmwareDevice) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *FirmwareDevice) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *FirmwareDevice) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *FirmwareDevice) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetHwModel

`func (o *FirmwareDevice) GetHwModel() string`

GetHwModel returns the HwModel field if non-nil, zero value otherwise.

### GetHwModelOk

`func (o *FirmwareDevice) GetHwModelOk() (*string, bool)`

GetHwModelOk returns a tuple with the HwModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHwModel

`func (o *FirmwareDevice) SetHwModel(v string)`

SetHwModel sets HwModel field to given value.

### HasHwModel

`func (o *FirmwareDevice) HasHwModel() bool`

HasHwModel returns a boolean if a field has been set.

### GetBdid

`func (o *FirmwareDevice) GetBdid() string`

GetBdid returns the Bdid field if non-nil, zero value otherwise.

### GetBdidOk

`func (o *FirmwareDevice) GetBdidOk() (*string, bool)`

GetBdidOk returns a tuple with the Bdid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBdid

`func (o *FirmwareDevice) SetBdid(v string)`

SetBdid sets Bdid field to given value.

### HasBdid

`func (o *FirmwareDevice) HasBdid() bool`

HasBdid returns a boolean if a field has been set.

### GetCpid

`func (o *FirmwareDevice) GetCpid() string`

GetCpid returns the Cpid field if non-nil, zero value otherwise.

### GetCpidOk

`func (o *FirmwareDevice) GetCpidOk() (*string, bool)`

GetCpidOk returns a tuple with the Cpid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpid

`func (o *FirmwareDevice) SetCpid(v string)`

SetCpid sets Cpid field to given value.

### HasCpid

`func (o *FirmwareDevice) HasCpid() bool`

HasCpid returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FirmwareDevice) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FirmwareDevice) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FirmwareDevice) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FirmwareDevice) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FirmwareDevice) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FirmwareDevice) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FirmwareDevice) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FirmwareDevice) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


