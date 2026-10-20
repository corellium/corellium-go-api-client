# DomainSoftware

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImageId** | **string** | Identifier of the uploaded image. Pass to &#x60;deleteImage&#x60; to remove the upload. | 
**Flavor** | **string** | Flavor the firmware applies to. | 
**Description** | **string** | Human-readable device name. | 
**Model** | **string** | Device product identifier. | 
**Platform** | **NullableString** | Device platform, when known. | 
**HasProductImage** | **bool** | Whether a product image is available for this flavor. | 
**OsVersion** | **NullableString** | OS version. | 
**OsBuild** | **NullableString** | OS build. | 
**Filename** | **string** | Uploaded filename. | 
**Size** | **NullableFloat64** | Firmware size in bytes. | 
**ReleaseDate** | **NullableTime** | Release date. | 
**UploadDate** | **time.Time** | Date the firmware was uploaded. | 
**DownloadUrl** | **NullableString** | Signed link the firmware can be downloaded from. | 

## Methods

### NewDomainSoftware

`func NewDomainSoftware(imageId string, flavor string, description string, model string, platform NullableString, hasProductImage bool, osVersion NullableString, osBuild NullableString, filename string, size NullableFloat64, releaseDate NullableTime, uploadDate time.Time, downloadUrl NullableString, ) *DomainSoftware`

NewDomainSoftware instantiates a new DomainSoftware object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainSoftwareWithDefaults

`func NewDomainSoftwareWithDefaults() *DomainSoftware`

NewDomainSoftwareWithDefaults instantiates a new DomainSoftware object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImageId

`func (o *DomainSoftware) GetImageId() string`

GetImageId returns the ImageId field if non-nil, zero value otherwise.

### GetImageIdOk

`func (o *DomainSoftware) GetImageIdOk() (*string, bool)`

GetImageIdOk returns a tuple with the ImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageId

`func (o *DomainSoftware) SetImageId(v string)`

SetImageId sets ImageId field to given value.


### GetFlavor

`func (o *DomainSoftware) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *DomainSoftware) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *DomainSoftware) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.


### GetDescription

`func (o *DomainSoftware) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DomainSoftware) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DomainSoftware) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetModel

`func (o *DomainSoftware) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *DomainSoftware) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *DomainSoftware) SetModel(v string)`

SetModel sets Model field to given value.


### GetPlatform

`func (o *DomainSoftware) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *DomainSoftware) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *DomainSoftware) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### SetPlatformNil

`func (o *DomainSoftware) SetPlatformNil(b bool)`

 SetPlatformNil sets the value for Platform to be an explicit nil

### UnsetPlatform
`func (o *DomainSoftware) UnsetPlatform()`

UnsetPlatform ensures that no value is present for Platform, not even an explicit nil
### GetHasProductImage

`func (o *DomainSoftware) GetHasProductImage() bool`

GetHasProductImage returns the HasProductImage field if non-nil, zero value otherwise.

### GetHasProductImageOk

`func (o *DomainSoftware) GetHasProductImageOk() (*bool, bool)`

GetHasProductImageOk returns a tuple with the HasProductImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasProductImage

`func (o *DomainSoftware) SetHasProductImage(v bool)`

SetHasProductImage sets HasProductImage field to given value.


### GetOsVersion

`func (o *DomainSoftware) GetOsVersion() string`

GetOsVersion returns the OsVersion field if non-nil, zero value otherwise.

### GetOsVersionOk

`func (o *DomainSoftware) GetOsVersionOk() (*string, bool)`

GetOsVersionOk returns a tuple with the OsVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsVersion

`func (o *DomainSoftware) SetOsVersion(v string)`

SetOsVersion sets OsVersion field to given value.


### SetOsVersionNil

`func (o *DomainSoftware) SetOsVersionNil(b bool)`

 SetOsVersionNil sets the value for OsVersion to be an explicit nil

### UnsetOsVersion
`func (o *DomainSoftware) UnsetOsVersion()`

UnsetOsVersion ensures that no value is present for OsVersion, not even an explicit nil
### GetOsBuild

`func (o *DomainSoftware) GetOsBuild() string`

GetOsBuild returns the OsBuild field if non-nil, zero value otherwise.

### GetOsBuildOk

`func (o *DomainSoftware) GetOsBuildOk() (*string, bool)`

GetOsBuildOk returns a tuple with the OsBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsBuild

`func (o *DomainSoftware) SetOsBuild(v string)`

SetOsBuild sets OsBuild field to given value.


### SetOsBuildNil

`func (o *DomainSoftware) SetOsBuildNil(b bool)`

 SetOsBuildNil sets the value for OsBuild to be an explicit nil

### UnsetOsBuild
`func (o *DomainSoftware) UnsetOsBuild()`

UnsetOsBuild ensures that no value is present for OsBuild, not even an explicit nil
### GetFilename

`func (o *DomainSoftware) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *DomainSoftware) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *DomainSoftware) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetSize

`func (o *DomainSoftware) GetSize() float64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *DomainSoftware) GetSizeOk() (*float64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *DomainSoftware) SetSize(v float64)`

SetSize sets Size field to given value.


### SetSizeNil

`func (o *DomainSoftware) SetSizeNil(b bool)`

 SetSizeNil sets the value for Size to be an explicit nil

### UnsetSize
`func (o *DomainSoftware) UnsetSize()`

UnsetSize ensures that no value is present for Size, not even an explicit nil
### GetReleaseDate

`func (o *DomainSoftware) GetReleaseDate() time.Time`

GetReleaseDate returns the ReleaseDate field if non-nil, zero value otherwise.

### GetReleaseDateOk

`func (o *DomainSoftware) GetReleaseDateOk() (*time.Time, bool)`

GetReleaseDateOk returns a tuple with the ReleaseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseDate

`func (o *DomainSoftware) SetReleaseDate(v time.Time)`

SetReleaseDate sets ReleaseDate field to given value.


### SetReleaseDateNil

`func (o *DomainSoftware) SetReleaseDateNil(b bool)`

 SetReleaseDateNil sets the value for ReleaseDate to be an explicit nil

### UnsetReleaseDate
`func (o *DomainSoftware) UnsetReleaseDate()`

UnsetReleaseDate ensures that no value is present for ReleaseDate, not even an explicit nil
### GetUploadDate

`func (o *DomainSoftware) GetUploadDate() time.Time`

GetUploadDate returns the UploadDate field if non-nil, zero value otherwise.

### GetUploadDateOk

`func (o *DomainSoftware) GetUploadDateOk() (*time.Time, bool)`

GetUploadDateOk returns a tuple with the UploadDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadDate

`func (o *DomainSoftware) SetUploadDate(v time.Time)`

SetUploadDate sets UploadDate field to given value.


### GetDownloadUrl

`func (o *DomainSoftware) GetDownloadUrl() string`

GetDownloadUrl returns the DownloadUrl field if non-nil, zero value otherwise.

### GetDownloadUrlOk

`func (o *DomainSoftware) GetDownloadUrlOk() (*string, bool)`

GetDownloadUrlOk returns a tuple with the DownloadUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadUrl

`func (o *DomainSoftware) SetDownloadUrl(v string)`

SetDownloadUrl sets DownloadUrl field to given value.


### SetDownloadUrlNil

`func (o *DomainSoftware) SetDownloadUrlNil(b bool)`

 SetDownloadUrlNil sets the value for DownloadUrl to be an explicit nil

### UnsetDownloadUrl
`func (o *DomainSoftware) UnsetDownloadUrl()`

UnsetDownloadUrl ensures that no value is present for DownloadUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


