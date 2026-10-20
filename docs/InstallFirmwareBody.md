# InstallFirmwareBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImageId** | **string** | Identifier of a previously uploaded &#39;fw&#39; type Image. | 

## Methods

### NewInstallFirmwareBody

`func NewInstallFirmwareBody(imageId string, ) *InstallFirmwareBody`

NewInstallFirmwareBody instantiates a new InstallFirmwareBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstallFirmwareBodyWithDefaults

`func NewInstallFirmwareBodyWithDefaults() *InstallFirmwareBody`

NewInstallFirmwareBodyWithDefaults instantiates a new InstallFirmwareBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImageId

`func (o *InstallFirmwareBody) GetImageId() string`

GetImageId returns the ImageId field if non-nil, zero value otherwise.

### GetImageIdOk

`func (o *InstallFirmwareBody) GetImageIdOk() (*string, bool)`

GetImageIdOk returns a tuple with the ImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageId

`func (o *InstallFirmwareBody) SetImageId(v string)`

SetImageId sets ImageId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


