# InstanceUefiBootloader

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Label** | **string** | Human-readable label for the UEFI boot option. | 
**Name** | **string** | UEFI bootloader file name. | 

## Methods

### NewInstanceUefiBootloader

`func NewInstanceUefiBootloader(label string, name string, ) *InstanceUefiBootloader`

NewInstanceUefiBootloader instantiates a new InstanceUefiBootloader object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceUefiBootloaderWithDefaults

`func NewInstanceUefiBootloaderWithDefaults() *InstanceUefiBootloader`

NewInstanceUefiBootloaderWithDefaults instantiates a new InstanceUefiBootloader object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLabel

`func (o *InstanceUefiBootloader) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *InstanceUefiBootloader) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *InstanceUefiBootloader) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetName

`func (o *InstanceUefiBootloader) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InstanceUefiBootloader) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InstanceUefiBootloader) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


