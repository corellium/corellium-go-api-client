# ImageFirmwareInfoBootArgs

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Normal** | Pointer to **string** | Boot arguments for normal boot. | [optional] 
**Restore** | Pointer to **string** | Boot arguments for restore boot. | [optional] 

## Methods

### NewImageFirmwareInfoBootArgs

`func NewImageFirmwareInfoBootArgs() *ImageFirmwareInfoBootArgs`

NewImageFirmwareInfoBootArgs instantiates a new ImageFirmwareInfoBootArgs object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageFirmwareInfoBootArgsWithDefaults

`func NewImageFirmwareInfoBootArgsWithDefaults() *ImageFirmwareInfoBootArgs`

NewImageFirmwareInfoBootArgsWithDefaults instantiates a new ImageFirmwareInfoBootArgs object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNormal

`func (o *ImageFirmwareInfoBootArgs) GetNormal() string`

GetNormal returns the Normal field if non-nil, zero value otherwise.

### GetNormalOk

`func (o *ImageFirmwareInfoBootArgs) GetNormalOk() (*string, bool)`

GetNormalOk returns a tuple with the Normal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormal

`func (o *ImageFirmwareInfoBootArgs) SetNormal(v string)`

SetNormal sets Normal field to given value.

### HasNormal

`func (o *ImageFirmwareInfoBootArgs) HasNormal() bool`

HasNormal returns a boolean if a field has been set.

### GetRestore

`func (o *ImageFirmwareInfoBootArgs) GetRestore() string`

GetRestore returns the Restore field if non-nil, zero value otherwise.

### GetRestoreOk

`func (o *ImageFirmwareInfoBootArgs) GetRestoreOk() (*string, bool)`

GetRestoreOk returns a tuple with the Restore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestore

`func (o *ImageFirmwareInfoBootArgs) SetRestore(v string)`

SetRestore sets Restore field to given value.

### HasRestore

`func (o *ImageFirmwareInfoBootArgs) HasRestore() bool`

HasRestore returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


