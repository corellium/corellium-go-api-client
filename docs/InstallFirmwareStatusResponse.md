# InstallFirmwareStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | [**NullableTaskStatus**](TaskStatus.md) |  | 
**InstalledFirmwareUrl** | Pointer to **NullableString** | URL of the installed firmware once status is \&quot;complete\&quot;; null otherwise. | [optional] 

## Methods

### NewInstallFirmwareStatusResponse

`func NewInstallFirmwareStatusResponse(status NullableTaskStatus, ) *InstallFirmwareStatusResponse`

NewInstallFirmwareStatusResponse instantiates a new InstallFirmwareStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstallFirmwareStatusResponseWithDefaults

`func NewInstallFirmwareStatusResponseWithDefaults() *InstallFirmwareStatusResponse`

NewInstallFirmwareStatusResponseWithDefaults instantiates a new InstallFirmwareStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *InstallFirmwareStatusResponse) GetStatus() TaskStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InstallFirmwareStatusResponse) GetStatusOk() (*TaskStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InstallFirmwareStatusResponse) SetStatus(v TaskStatus)`

SetStatus sets Status field to given value.


### SetStatusNil

`func (o *InstallFirmwareStatusResponse) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *InstallFirmwareStatusResponse) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetInstalledFirmwareUrl

`func (o *InstallFirmwareStatusResponse) GetInstalledFirmwareUrl() string`

GetInstalledFirmwareUrl returns the InstalledFirmwareUrl field if non-nil, zero value otherwise.

### GetInstalledFirmwareUrlOk

`func (o *InstallFirmwareStatusResponse) GetInstalledFirmwareUrlOk() (*string, bool)`

GetInstalledFirmwareUrlOk returns a tuple with the InstalledFirmwareUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstalledFirmwareUrl

`func (o *InstallFirmwareStatusResponse) SetInstalledFirmwareUrl(v string)`

SetInstalledFirmwareUrl sets InstalledFirmwareUrl field to given value.

### HasInstalledFirmwareUrl

`func (o *InstallFirmwareStatusResponse) HasInstalledFirmwareUrl() bool`

HasInstalledFirmwareUrl returns a boolean if a field has been set.

### SetInstalledFirmwareUrlNil

`func (o *InstallFirmwareStatusResponse) SetInstalledFirmwareUrlNil(b bool)`

 SetInstalledFirmwareUrlNil sets the value for InstalledFirmwareUrl to be an explicit nil

### UnsetInstalledFirmwareUrl
`func (o *InstallFirmwareStatusResponse) UnsetInstalledFirmwareUrl()`

UnsetInstalledFirmwareUrl ensures that no value is present for InstalledFirmwareUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


