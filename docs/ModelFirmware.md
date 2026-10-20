# ModelFirmware

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OsVersion** | **string** | Operating-system version of this build. Pass it as &#x60;osVersion&#x60; when you create an instance. | 
**OsBuild** | **NullableString** | Build identifier of this version. Pass it as &#x60;osBuild&#x60; (together with &#x60;osVersion&#x60;) when you create an instance to get exactly this build. If you pass only &#x60;osVersion&#x60;, the newest build of that version is used. | 
**AndroidFlavor** | Pointer to **NullableString** | Android-only flavor. | [optional] 
**ApiVersion** | Pointer to **NullableString** | Android-only API version. | [optional] 
**Sha256sum** | Pointer to **NullableString** | SHA-256 checksum. | [optional] 
**Sha1sum** | Pointer to **NullableString** | SHA-1 checksum. | [optional] 
**Md5sum** | Pointer to **NullableString** | MD5 checksum. | [optional] 
**CorelliumChecksum** | Pointer to **NullableString** | Corellium checksum, in the form algorithm$chunkSize$checksum. Absent for a domain upload. | [optional] 
**Installed** | Pointer to **NullableBool** | Whether this build is already stored on your Corellium deployment. A build that is not installed can only be used if your deployment is allowed to fetch it from the vendor; an air-gapped deployment can use only installed builds. | [optional] 
**Size** | Pointer to **NullableFloat64** | Software size in bytes. | [optional] 
**UniqueId** | Pointer to **NullableString** | A label chosen by whoever packaged this firmware. It is not guaranteed to be unique and cannot be used to look up an image or firmware; select a build with &#x60;osVersion&#x60; and &#x60;osBuild&#x60; instead. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Software metadata. | [optional] 
**ReleaseDate** | Pointer to **NullableTime** | Release date. | [optional] 
**UploadDate** | Pointer to **NullableString** | Date uploaded; may be an empty string when unknown. | [optional] 
**Url** | Pointer to **NullableString** | URL the software is available at. | [optional] 
**OrigUrl** | Pointer to **NullableString** | URL the software is available at from the vendor. | [optional] 
**Filename** | Pointer to **NullableString** | Software filename. | [optional] 
**Rooted** | Pointer to **NullableBool** | Whether a device from this firmware is rooted. Android has a rooted and a not-rooted build for each version. Null for iOS. | [optional] 
**Signed** | Pointer to **NullableBool** | Whether the vendor still signs this build, from the upstream ipsw data. | [optional] 
**SpringboardSnapshot** | Pointer to [**NullableModelFirmwareSpringboardSnapshot**](ModelFirmwareSpringboardSnapshot.md) |  | [optional] 

## Methods

### NewModelFirmware

`func NewModelFirmware(osVersion string, osBuild NullableString, ) *ModelFirmware`

NewModelFirmware instantiates a new ModelFirmware object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelFirmwareWithDefaults

`func NewModelFirmwareWithDefaults() *ModelFirmware`

NewModelFirmwareWithDefaults instantiates a new ModelFirmware object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOsVersion

`func (o *ModelFirmware) GetOsVersion() string`

GetOsVersion returns the OsVersion field if non-nil, zero value otherwise.

### GetOsVersionOk

`func (o *ModelFirmware) GetOsVersionOk() (*string, bool)`

GetOsVersionOk returns a tuple with the OsVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsVersion

`func (o *ModelFirmware) SetOsVersion(v string)`

SetOsVersion sets OsVersion field to given value.


### GetOsBuild

`func (o *ModelFirmware) GetOsBuild() string`

GetOsBuild returns the OsBuild field if non-nil, zero value otherwise.

### GetOsBuildOk

`func (o *ModelFirmware) GetOsBuildOk() (*string, bool)`

GetOsBuildOk returns a tuple with the OsBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsBuild

`func (o *ModelFirmware) SetOsBuild(v string)`

SetOsBuild sets OsBuild field to given value.


### SetOsBuildNil

`func (o *ModelFirmware) SetOsBuildNil(b bool)`

 SetOsBuildNil sets the value for OsBuild to be an explicit nil

### UnsetOsBuild
`func (o *ModelFirmware) UnsetOsBuild()`

UnsetOsBuild ensures that no value is present for OsBuild, not even an explicit nil
### GetAndroidFlavor

`func (o *ModelFirmware) GetAndroidFlavor() string`

GetAndroidFlavor returns the AndroidFlavor field if non-nil, zero value otherwise.

### GetAndroidFlavorOk

`func (o *ModelFirmware) GetAndroidFlavorOk() (*string, bool)`

GetAndroidFlavorOk returns a tuple with the AndroidFlavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAndroidFlavor

`func (o *ModelFirmware) SetAndroidFlavor(v string)`

SetAndroidFlavor sets AndroidFlavor field to given value.

### HasAndroidFlavor

`func (o *ModelFirmware) HasAndroidFlavor() bool`

HasAndroidFlavor returns a boolean if a field has been set.

### SetAndroidFlavorNil

`func (o *ModelFirmware) SetAndroidFlavorNil(b bool)`

 SetAndroidFlavorNil sets the value for AndroidFlavor to be an explicit nil

### UnsetAndroidFlavor
`func (o *ModelFirmware) UnsetAndroidFlavor()`

UnsetAndroidFlavor ensures that no value is present for AndroidFlavor, not even an explicit nil
### GetApiVersion

`func (o *ModelFirmware) GetApiVersion() string`

GetApiVersion returns the ApiVersion field if non-nil, zero value otherwise.

### GetApiVersionOk

`func (o *ModelFirmware) GetApiVersionOk() (*string, bool)`

GetApiVersionOk returns a tuple with the ApiVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiVersion

`func (o *ModelFirmware) SetApiVersion(v string)`

SetApiVersion sets ApiVersion field to given value.

### HasApiVersion

`func (o *ModelFirmware) HasApiVersion() bool`

HasApiVersion returns a boolean if a field has been set.

### SetApiVersionNil

`func (o *ModelFirmware) SetApiVersionNil(b bool)`

 SetApiVersionNil sets the value for ApiVersion to be an explicit nil

### UnsetApiVersion
`func (o *ModelFirmware) UnsetApiVersion()`

UnsetApiVersion ensures that no value is present for ApiVersion, not even an explicit nil
### GetSha256sum

`func (o *ModelFirmware) GetSha256sum() string`

GetSha256sum returns the Sha256sum field if non-nil, zero value otherwise.

### GetSha256sumOk

`func (o *ModelFirmware) GetSha256sumOk() (*string, bool)`

GetSha256sumOk returns a tuple with the Sha256sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256sum

`func (o *ModelFirmware) SetSha256sum(v string)`

SetSha256sum sets Sha256sum field to given value.

### HasSha256sum

`func (o *ModelFirmware) HasSha256sum() bool`

HasSha256sum returns a boolean if a field has been set.

### SetSha256sumNil

`func (o *ModelFirmware) SetSha256sumNil(b bool)`

 SetSha256sumNil sets the value for Sha256sum to be an explicit nil

### UnsetSha256sum
`func (o *ModelFirmware) UnsetSha256sum()`

UnsetSha256sum ensures that no value is present for Sha256sum, not even an explicit nil
### GetSha1sum

`func (o *ModelFirmware) GetSha1sum() string`

GetSha1sum returns the Sha1sum field if non-nil, zero value otherwise.

### GetSha1sumOk

`func (o *ModelFirmware) GetSha1sumOk() (*string, bool)`

GetSha1sumOk returns a tuple with the Sha1sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha1sum

`func (o *ModelFirmware) SetSha1sum(v string)`

SetSha1sum sets Sha1sum field to given value.

### HasSha1sum

`func (o *ModelFirmware) HasSha1sum() bool`

HasSha1sum returns a boolean if a field has been set.

### SetSha1sumNil

`func (o *ModelFirmware) SetSha1sumNil(b bool)`

 SetSha1sumNil sets the value for Sha1sum to be an explicit nil

### UnsetSha1sum
`func (o *ModelFirmware) UnsetSha1sum()`

UnsetSha1sum ensures that no value is present for Sha1sum, not even an explicit nil
### GetMd5sum

`func (o *ModelFirmware) GetMd5sum() string`

GetMd5sum returns the Md5sum field if non-nil, zero value otherwise.

### GetMd5sumOk

`func (o *ModelFirmware) GetMd5sumOk() (*string, bool)`

GetMd5sumOk returns a tuple with the Md5sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5sum

`func (o *ModelFirmware) SetMd5sum(v string)`

SetMd5sum sets Md5sum field to given value.

### HasMd5sum

`func (o *ModelFirmware) HasMd5sum() bool`

HasMd5sum returns a boolean if a field has been set.

### SetMd5sumNil

`func (o *ModelFirmware) SetMd5sumNil(b bool)`

 SetMd5sumNil sets the value for Md5sum to be an explicit nil

### UnsetMd5sum
`func (o *ModelFirmware) UnsetMd5sum()`

UnsetMd5sum ensures that no value is present for Md5sum, not even an explicit nil
### GetCorelliumChecksum

`func (o *ModelFirmware) GetCorelliumChecksum() string`

GetCorelliumChecksum returns the CorelliumChecksum field if non-nil, zero value otherwise.

### GetCorelliumChecksumOk

`func (o *ModelFirmware) GetCorelliumChecksumOk() (*string, bool)`

GetCorelliumChecksumOk returns a tuple with the CorelliumChecksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorelliumChecksum

`func (o *ModelFirmware) SetCorelliumChecksum(v string)`

SetCorelliumChecksum sets CorelliumChecksum field to given value.

### HasCorelliumChecksum

`func (o *ModelFirmware) HasCorelliumChecksum() bool`

HasCorelliumChecksum returns a boolean if a field has been set.

### SetCorelliumChecksumNil

`func (o *ModelFirmware) SetCorelliumChecksumNil(b bool)`

 SetCorelliumChecksumNil sets the value for CorelliumChecksum to be an explicit nil

### UnsetCorelliumChecksum
`func (o *ModelFirmware) UnsetCorelliumChecksum()`

UnsetCorelliumChecksum ensures that no value is present for CorelliumChecksum, not even an explicit nil
### GetInstalled

`func (o *ModelFirmware) GetInstalled() bool`

GetInstalled returns the Installed field if non-nil, zero value otherwise.

### GetInstalledOk

`func (o *ModelFirmware) GetInstalledOk() (*bool, bool)`

GetInstalledOk returns a tuple with the Installed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstalled

`func (o *ModelFirmware) SetInstalled(v bool)`

SetInstalled sets Installed field to given value.

### HasInstalled

`func (o *ModelFirmware) HasInstalled() bool`

HasInstalled returns a boolean if a field has been set.

### SetInstalledNil

`func (o *ModelFirmware) SetInstalledNil(b bool)`

 SetInstalledNil sets the value for Installed to be an explicit nil

### UnsetInstalled
`func (o *ModelFirmware) UnsetInstalled()`

UnsetInstalled ensures that no value is present for Installed, not even an explicit nil
### GetSize

`func (o *ModelFirmware) GetSize() float64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *ModelFirmware) GetSizeOk() (*float64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *ModelFirmware) SetSize(v float64)`

SetSize sets Size field to given value.

### HasSize

`func (o *ModelFirmware) HasSize() bool`

HasSize returns a boolean if a field has been set.

### SetSizeNil

`func (o *ModelFirmware) SetSizeNil(b bool)`

 SetSizeNil sets the value for Size to be an explicit nil

### UnsetSize
`func (o *ModelFirmware) UnsetSize()`

UnsetSize ensures that no value is present for Size, not even an explicit nil
### GetUniqueId

`func (o *ModelFirmware) GetUniqueId() string`

GetUniqueId returns the UniqueId field if non-nil, zero value otherwise.

### GetUniqueIdOk

`func (o *ModelFirmware) GetUniqueIdOk() (*string, bool)`

GetUniqueIdOk returns a tuple with the UniqueId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueId

`func (o *ModelFirmware) SetUniqueId(v string)`

SetUniqueId sets UniqueId field to given value.

### HasUniqueId

`func (o *ModelFirmware) HasUniqueId() bool`

HasUniqueId returns a boolean if a field has been set.

### SetUniqueIdNil

`func (o *ModelFirmware) SetUniqueIdNil(b bool)`

 SetUniqueIdNil sets the value for UniqueId to be an explicit nil

### UnsetUniqueId
`func (o *ModelFirmware) UnsetUniqueId()`

UnsetUniqueId ensures that no value is present for UniqueId, not even an explicit nil
### GetMetadata

`func (o *ModelFirmware) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ModelFirmware) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ModelFirmware) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ModelFirmware) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *ModelFirmware) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *ModelFirmware) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetReleaseDate

`func (o *ModelFirmware) GetReleaseDate() time.Time`

GetReleaseDate returns the ReleaseDate field if non-nil, zero value otherwise.

### GetReleaseDateOk

`func (o *ModelFirmware) GetReleaseDateOk() (*time.Time, bool)`

GetReleaseDateOk returns a tuple with the ReleaseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseDate

`func (o *ModelFirmware) SetReleaseDate(v time.Time)`

SetReleaseDate sets ReleaseDate field to given value.

### HasReleaseDate

`func (o *ModelFirmware) HasReleaseDate() bool`

HasReleaseDate returns a boolean if a field has been set.

### SetReleaseDateNil

`func (o *ModelFirmware) SetReleaseDateNil(b bool)`

 SetReleaseDateNil sets the value for ReleaseDate to be an explicit nil

### UnsetReleaseDate
`func (o *ModelFirmware) UnsetReleaseDate()`

UnsetReleaseDate ensures that no value is present for ReleaseDate, not even an explicit nil
### GetUploadDate

`func (o *ModelFirmware) GetUploadDate() string`

GetUploadDate returns the UploadDate field if non-nil, zero value otherwise.

### GetUploadDateOk

`func (o *ModelFirmware) GetUploadDateOk() (*string, bool)`

GetUploadDateOk returns a tuple with the UploadDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadDate

`func (o *ModelFirmware) SetUploadDate(v string)`

SetUploadDate sets UploadDate field to given value.

### HasUploadDate

`func (o *ModelFirmware) HasUploadDate() bool`

HasUploadDate returns a boolean if a field has been set.

### SetUploadDateNil

`func (o *ModelFirmware) SetUploadDateNil(b bool)`

 SetUploadDateNil sets the value for UploadDate to be an explicit nil

### UnsetUploadDate
`func (o *ModelFirmware) UnsetUploadDate()`

UnsetUploadDate ensures that no value is present for UploadDate, not even an explicit nil
### GetUrl

`func (o *ModelFirmware) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ModelFirmware) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ModelFirmware) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ModelFirmware) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *ModelFirmware) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *ModelFirmware) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetOrigUrl

`func (o *ModelFirmware) GetOrigUrl() string`

GetOrigUrl returns the OrigUrl field if non-nil, zero value otherwise.

### GetOrigUrlOk

`func (o *ModelFirmware) GetOrigUrlOk() (*string, bool)`

GetOrigUrlOk returns a tuple with the OrigUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigUrl

`func (o *ModelFirmware) SetOrigUrl(v string)`

SetOrigUrl sets OrigUrl field to given value.

### HasOrigUrl

`func (o *ModelFirmware) HasOrigUrl() bool`

HasOrigUrl returns a boolean if a field has been set.

### SetOrigUrlNil

`func (o *ModelFirmware) SetOrigUrlNil(b bool)`

 SetOrigUrlNil sets the value for OrigUrl to be an explicit nil

### UnsetOrigUrl
`func (o *ModelFirmware) UnsetOrigUrl()`

UnsetOrigUrl ensures that no value is present for OrigUrl, not even an explicit nil
### GetFilename

`func (o *ModelFirmware) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *ModelFirmware) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *ModelFirmware) SetFilename(v string)`

SetFilename sets Filename field to given value.

### HasFilename

`func (o *ModelFirmware) HasFilename() bool`

HasFilename returns a boolean if a field has been set.

### SetFilenameNil

`func (o *ModelFirmware) SetFilenameNil(b bool)`

 SetFilenameNil sets the value for Filename to be an explicit nil

### UnsetFilename
`func (o *ModelFirmware) UnsetFilename()`

UnsetFilename ensures that no value is present for Filename, not even an explicit nil
### GetRooted

`func (o *ModelFirmware) GetRooted() bool`

GetRooted returns the Rooted field if non-nil, zero value otherwise.

### GetRootedOk

`func (o *ModelFirmware) GetRootedOk() (*bool, bool)`

GetRootedOk returns a tuple with the Rooted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRooted

`func (o *ModelFirmware) SetRooted(v bool)`

SetRooted sets Rooted field to given value.

### HasRooted

`func (o *ModelFirmware) HasRooted() bool`

HasRooted returns a boolean if a field has been set.

### SetRootedNil

`func (o *ModelFirmware) SetRootedNil(b bool)`

 SetRootedNil sets the value for Rooted to be an explicit nil

### UnsetRooted
`func (o *ModelFirmware) UnsetRooted()`

UnsetRooted ensures that no value is present for Rooted, not even an explicit nil
### GetSigned

`func (o *ModelFirmware) GetSigned() bool`

GetSigned returns the Signed field if non-nil, zero value otherwise.

### GetSignedOk

`func (o *ModelFirmware) GetSignedOk() (*bool, bool)`

GetSignedOk returns a tuple with the Signed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSigned

`func (o *ModelFirmware) SetSigned(v bool)`

SetSigned sets Signed field to given value.

### HasSigned

`func (o *ModelFirmware) HasSigned() bool`

HasSigned returns a boolean if a field has been set.

### SetSignedNil

`func (o *ModelFirmware) SetSignedNil(b bool)`

 SetSignedNil sets the value for Signed to be an explicit nil

### UnsetSigned
`func (o *ModelFirmware) UnsetSigned()`

UnsetSigned ensures that no value is present for Signed, not even an explicit nil
### GetSpringboardSnapshot

`func (o *ModelFirmware) GetSpringboardSnapshot() ModelFirmwareSpringboardSnapshot`

GetSpringboardSnapshot returns the SpringboardSnapshot field if non-nil, zero value otherwise.

### GetSpringboardSnapshotOk

`func (o *ModelFirmware) GetSpringboardSnapshotOk() (*ModelFirmwareSpringboardSnapshot, bool)`

GetSpringboardSnapshotOk returns a tuple with the SpringboardSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpringboardSnapshot

`func (o *ModelFirmware) SetSpringboardSnapshot(v ModelFirmwareSpringboardSnapshot)`

SetSpringboardSnapshot sets SpringboardSnapshot field to given value.

### HasSpringboardSnapshot

`func (o *ModelFirmware) HasSpringboardSnapshot() bool`

HasSpringboardSnapshot returns a boolean if a field has been set.

### SetSpringboardSnapshotNil

`func (o *ModelFirmware) SetSpringboardSnapshotNil(b bool)`

 SetSpringboardSnapshotNil sets the value for SpringboardSnapshot to be an explicit nil

### UnsetSpringboardSnapshot
`func (o *ModelFirmware) UnsetSpringboardSnapshot()`

UnsetSpringboardSnapshot ensures that no value is present for SpringboardSnapshot, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


