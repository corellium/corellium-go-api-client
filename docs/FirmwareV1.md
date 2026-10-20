# FirmwareV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Version** | Pointer to **NullableString** |  | [optional] 
**Buildid** | Pointer to **NullableString** |  | [optional] 
**AndroidFlavor** | Pointer to **NullableString** | Android only flavor | [optional] 
**APIVersion** | Pointer to **NullableString** | Android only API version | [optional] 
**Sha256sum** | Pointer to **NullableString** |  | [optional] 
**Sha1sum** | Pointer to **NullableString** |  | [optional] 
**Md5sum** | Pointer to **NullableString** |  | [optional] 
**Size** | Pointer to **NullableFloat32** |  | [optional] 
**UniqueId** | Pointer to **NullableString** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Firmware metadata | [optional] 
**Releasedate** | Pointer to **NullableTime** | Release Date | [optional] 
**Uploaddate** | Pointer to **NullableTime** | Date uploaded | [optional] 
**Url** | Pointer to **NullableString** | URL firmware is available at | [optional] 
**OrigUrl** | Pointer to **NullableString** | URL firmware is available at from vendor | [optional] 
**Filename** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewFirmwareV1

`func NewFirmwareV1() *FirmwareV1`

NewFirmwareV1 instantiates a new FirmwareV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareV1WithDefaults

`func NewFirmwareV1WithDefaults() *FirmwareV1`

NewFirmwareV1WithDefaults instantiates a new FirmwareV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersion

`func (o *FirmwareV1) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *FirmwareV1) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *FirmwareV1) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *FirmwareV1) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *FirmwareV1) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *FirmwareV1) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetBuildid

`func (o *FirmwareV1) GetBuildid() string`

GetBuildid returns the Buildid field if non-nil, zero value otherwise.

### GetBuildidOk

`func (o *FirmwareV1) GetBuildidOk() (*string, bool)`

GetBuildidOk returns a tuple with the Buildid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildid

`func (o *FirmwareV1) SetBuildid(v string)`

SetBuildid sets Buildid field to given value.

### HasBuildid

`func (o *FirmwareV1) HasBuildid() bool`

HasBuildid returns a boolean if a field has been set.

### SetBuildidNil

`func (o *FirmwareV1) SetBuildidNil(b bool)`

 SetBuildidNil sets the value for Buildid to be an explicit nil

### UnsetBuildid
`func (o *FirmwareV1) UnsetBuildid()`

UnsetBuildid ensures that no value is present for Buildid, not even an explicit nil
### GetAndroidFlavor

`func (o *FirmwareV1) GetAndroidFlavor() string`

GetAndroidFlavor returns the AndroidFlavor field if non-nil, zero value otherwise.

### GetAndroidFlavorOk

`func (o *FirmwareV1) GetAndroidFlavorOk() (*string, bool)`

GetAndroidFlavorOk returns a tuple with the AndroidFlavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAndroidFlavor

`func (o *FirmwareV1) SetAndroidFlavor(v string)`

SetAndroidFlavor sets AndroidFlavor field to given value.

### HasAndroidFlavor

`func (o *FirmwareV1) HasAndroidFlavor() bool`

HasAndroidFlavor returns a boolean if a field has been set.

### SetAndroidFlavorNil

`func (o *FirmwareV1) SetAndroidFlavorNil(b bool)`

 SetAndroidFlavorNil sets the value for AndroidFlavor to be an explicit nil

### UnsetAndroidFlavor
`func (o *FirmwareV1) UnsetAndroidFlavor()`

UnsetAndroidFlavor ensures that no value is present for AndroidFlavor, not even an explicit nil
### GetAPIVersion

`func (o *FirmwareV1) GetAPIVersion() string`

GetAPIVersion returns the APIVersion field if non-nil, zero value otherwise.

### GetAPIVersionOk

`func (o *FirmwareV1) GetAPIVersionOk() (*string, bool)`

GetAPIVersionOk returns a tuple with the APIVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAPIVersion

`func (o *FirmwareV1) SetAPIVersion(v string)`

SetAPIVersion sets APIVersion field to given value.

### HasAPIVersion

`func (o *FirmwareV1) HasAPIVersion() bool`

HasAPIVersion returns a boolean if a field has been set.

### SetAPIVersionNil

`func (o *FirmwareV1) SetAPIVersionNil(b bool)`

 SetAPIVersionNil sets the value for APIVersion to be an explicit nil

### UnsetAPIVersion
`func (o *FirmwareV1) UnsetAPIVersion()`

UnsetAPIVersion ensures that no value is present for APIVersion, not even an explicit nil
### GetSha256sum

`func (o *FirmwareV1) GetSha256sum() string`

GetSha256sum returns the Sha256sum field if non-nil, zero value otherwise.

### GetSha256sumOk

`func (o *FirmwareV1) GetSha256sumOk() (*string, bool)`

GetSha256sumOk returns a tuple with the Sha256sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256sum

`func (o *FirmwareV1) SetSha256sum(v string)`

SetSha256sum sets Sha256sum field to given value.

### HasSha256sum

`func (o *FirmwareV1) HasSha256sum() bool`

HasSha256sum returns a boolean if a field has been set.

### SetSha256sumNil

`func (o *FirmwareV1) SetSha256sumNil(b bool)`

 SetSha256sumNil sets the value for Sha256sum to be an explicit nil

### UnsetSha256sum
`func (o *FirmwareV1) UnsetSha256sum()`

UnsetSha256sum ensures that no value is present for Sha256sum, not even an explicit nil
### GetSha1sum

`func (o *FirmwareV1) GetSha1sum() string`

GetSha1sum returns the Sha1sum field if non-nil, zero value otherwise.

### GetSha1sumOk

`func (o *FirmwareV1) GetSha1sumOk() (*string, bool)`

GetSha1sumOk returns a tuple with the Sha1sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha1sum

`func (o *FirmwareV1) SetSha1sum(v string)`

SetSha1sum sets Sha1sum field to given value.

### HasSha1sum

`func (o *FirmwareV1) HasSha1sum() bool`

HasSha1sum returns a boolean if a field has been set.

### SetSha1sumNil

`func (o *FirmwareV1) SetSha1sumNil(b bool)`

 SetSha1sumNil sets the value for Sha1sum to be an explicit nil

### UnsetSha1sum
`func (o *FirmwareV1) UnsetSha1sum()`

UnsetSha1sum ensures that no value is present for Sha1sum, not even an explicit nil
### GetMd5sum

`func (o *FirmwareV1) GetMd5sum() string`

GetMd5sum returns the Md5sum field if non-nil, zero value otherwise.

### GetMd5sumOk

`func (o *FirmwareV1) GetMd5sumOk() (*string, bool)`

GetMd5sumOk returns a tuple with the Md5sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5sum

`func (o *FirmwareV1) SetMd5sum(v string)`

SetMd5sum sets Md5sum field to given value.

### HasMd5sum

`func (o *FirmwareV1) HasMd5sum() bool`

HasMd5sum returns a boolean if a field has been set.

### SetMd5sumNil

`func (o *FirmwareV1) SetMd5sumNil(b bool)`

 SetMd5sumNil sets the value for Md5sum to be an explicit nil

### UnsetMd5sum
`func (o *FirmwareV1) UnsetMd5sum()`

UnsetMd5sum ensures that no value is present for Md5sum, not even an explicit nil
### GetSize

`func (o *FirmwareV1) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FirmwareV1) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FirmwareV1) SetSize(v float32)`

SetSize sets Size field to given value.

### HasSize

`func (o *FirmwareV1) HasSize() bool`

HasSize returns a boolean if a field has been set.

### SetSizeNil

`func (o *FirmwareV1) SetSizeNil(b bool)`

 SetSizeNil sets the value for Size to be an explicit nil

### UnsetSize
`func (o *FirmwareV1) UnsetSize()`

UnsetSize ensures that no value is present for Size, not even an explicit nil
### GetUniqueId

`func (o *FirmwareV1) GetUniqueId() string`

GetUniqueId returns the UniqueId field if non-nil, zero value otherwise.

### GetUniqueIdOk

`func (o *FirmwareV1) GetUniqueIdOk() (*string, bool)`

GetUniqueIdOk returns a tuple with the UniqueId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueId

`func (o *FirmwareV1) SetUniqueId(v string)`

SetUniqueId sets UniqueId field to given value.

### HasUniqueId

`func (o *FirmwareV1) HasUniqueId() bool`

HasUniqueId returns a boolean if a field has been set.

### SetUniqueIdNil

`func (o *FirmwareV1) SetUniqueIdNil(b bool)`

 SetUniqueIdNil sets the value for UniqueId to be an explicit nil

### UnsetUniqueId
`func (o *FirmwareV1) UnsetUniqueId()`

UnsetUniqueId ensures that no value is present for UniqueId, not even an explicit nil
### GetMetadata

`func (o *FirmwareV1) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *FirmwareV1) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *FirmwareV1) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *FirmwareV1) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *FirmwareV1) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *FirmwareV1) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetReleasedate

`func (o *FirmwareV1) GetReleasedate() time.Time`

GetReleasedate returns the Releasedate field if non-nil, zero value otherwise.

### GetReleasedateOk

`func (o *FirmwareV1) GetReleasedateOk() (*time.Time, bool)`

GetReleasedateOk returns a tuple with the Releasedate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasedate

`func (o *FirmwareV1) SetReleasedate(v time.Time)`

SetReleasedate sets Releasedate field to given value.

### HasReleasedate

`func (o *FirmwareV1) HasReleasedate() bool`

HasReleasedate returns a boolean if a field has been set.

### SetReleasedateNil

`func (o *FirmwareV1) SetReleasedateNil(b bool)`

 SetReleasedateNil sets the value for Releasedate to be an explicit nil

### UnsetReleasedate
`func (o *FirmwareV1) UnsetReleasedate()`

UnsetReleasedate ensures that no value is present for Releasedate, not even an explicit nil
### GetUploaddate

`func (o *FirmwareV1) GetUploaddate() time.Time`

GetUploaddate returns the Uploaddate field if non-nil, zero value otherwise.

### GetUploaddateOk

`func (o *FirmwareV1) GetUploaddateOk() (*time.Time, bool)`

GetUploaddateOk returns a tuple with the Uploaddate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploaddate

`func (o *FirmwareV1) SetUploaddate(v time.Time)`

SetUploaddate sets Uploaddate field to given value.

### HasUploaddate

`func (o *FirmwareV1) HasUploaddate() bool`

HasUploaddate returns a boolean if a field has been set.

### SetUploaddateNil

`func (o *FirmwareV1) SetUploaddateNil(b bool)`

 SetUploaddateNil sets the value for Uploaddate to be an explicit nil

### UnsetUploaddate
`func (o *FirmwareV1) UnsetUploaddate()`

UnsetUploaddate ensures that no value is present for Uploaddate, not even an explicit nil
### GetUrl

`func (o *FirmwareV1) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FirmwareV1) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FirmwareV1) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *FirmwareV1) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *FirmwareV1) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *FirmwareV1) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetOrigUrl

`func (o *FirmwareV1) GetOrigUrl() string`

GetOrigUrl returns the OrigUrl field if non-nil, zero value otherwise.

### GetOrigUrlOk

`func (o *FirmwareV1) GetOrigUrlOk() (*string, bool)`

GetOrigUrlOk returns a tuple with the OrigUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigUrl

`func (o *FirmwareV1) SetOrigUrl(v string)`

SetOrigUrl sets OrigUrl field to given value.

### HasOrigUrl

`func (o *FirmwareV1) HasOrigUrl() bool`

HasOrigUrl returns a boolean if a field has been set.

### SetOrigUrlNil

`func (o *FirmwareV1) SetOrigUrlNil(b bool)`

 SetOrigUrlNil sets the value for OrigUrl to be an explicit nil

### UnsetOrigUrl
`func (o *FirmwareV1) UnsetOrigUrl()`

UnsetOrigUrl ensures that no value is present for OrigUrl, not even an explicit nil
### GetFilename

`func (o *FirmwareV1) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *FirmwareV1) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *FirmwareV1) SetFilename(v string)`

SetFilename sets Filename field to given value.

### HasFilename

`func (o *FirmwareV1) HasFilename() bool`

HasFilename returns a boolean if a field has been set.

### SetFilenameNil

`func (o *FirmwareV1) SetFilenameNil(b bool)`

 SetFilenameNil sets the value for Filename to be an explicit nil

### UnsetFilename
`func (o *FirmwareV1) UnsetFilename()`

UnsetFilename ensures that no value is present for Filename, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


