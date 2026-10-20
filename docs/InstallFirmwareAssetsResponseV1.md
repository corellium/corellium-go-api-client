# InstallFirmwareAssetsResponseV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **NullableString** | Message returned by the firmware service describing the outcome of the asset upload. | [optional] 

## Methods

### NewInstallFirmwareAssetsResponseV1

`func NewInstallFirmwareAssetsResponseV1() *InstallFirmwareAssetsResponseV1`

NewInstallFirmwareAssetsResponseV1 instantiates a new InstallFirmwareAssetsResponseV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstallFirmwareAssetsResponseV1WithDefaults

`func NewInstallFirmwareAssetsResponseV1WithDefaults() *InstallFirmwareAssetsResponseV1`

NewInstallFirmwareAssetsResponseV1WithDefaults instantiates a new InstallFirmwareAssetsResponseV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *InstallFirmwareAssetsResponseV1) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *InstallFirmwareAssetsResponseV1) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *InstallFirmwareAssetsResponseV1) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *InstallFirmwareAssetsResponseV1) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *InstallFirmwareAssetsResponseV1) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *InstallFirmwareAssetsResponseV1) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


