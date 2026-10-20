# Firmware

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | **[]string** | Device models the firmware supports. | 
**FirmwareAssets** | Pointer to **[]string** | Associated firmware asset URLs; null when assets have not been checked for yet. | [optional] 
**Filename** | **string** | Firmware filename. | 
**Type** | Pointer to **string** | Firmware type. | [optional] 
**Size** | **float64** | Firmware size in bytes. | 
**Url** | Pointer to **NullableString** | Firmware download URL. | [optional] 
**Version** | **string** | Firmware version. | 
**BuildId** | Pointer to **NullableString** | Firmware build ID. | [optional] 
**Md5sum** | Pointer to **NullableString** | MD5 checksum. | [optional] 
**Sha1sum** | Pointer to **NullableString** | SHA-1 checksum. | [optional] 
**Sha256sum** | Pointer to **NullableString** | SHA-256 checksum. | [optional] 
**CorelliumChecksum** | Pointer to **NullableString** | Corellium chunked checksum (&lt;algo&gt;$&lt;chunkSize&gt;$&lt;hash&gt;); used for upload preflight. | [optional] 
**ReleaseDate** | Pointer to **NullableString** | Release date; may be an empty string. | [optional] 
**UploadDate** | Pointer to **NullableString** | Upload date; may be an empty string. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Firmware metadata. | [optional] 
**UniqueId** | Pointer to **NullableString** | Customer-provided identifier; an arbitrary string, not a UUID. | [optional] 
**AndroidFlavor** | Pointer to **NullableString** | Android device flavor; only present for coreimg firmwares. | [optional] 
**ApiVersion** | Pointer to **NullableString** | Android API version; only present for coreimg firmwares. | [optional] 
**Rooted** | Pointer to **NullableBool** | Whether a device created from this firmware is rooted. Android publishes a &#x60;&lt;rev&gt; user&#x60; (not rooted) and a &#x60;&lt;rev&gt; userdebug&#x60; (rooted) build per version. Null on iOS, where rooting is not a property of the firmware. | [optional] 
**Installed** | Pointer to **NullableBool** | Whether the firmware is installed. | [optional] 
**CreatedAt** | Pointer to **time.Time** | When the record was created. | [optional] 
**UpdatedAt** | Pointer to **time.Time** | When the record was last updated. | [optional] 

## Methods

### NewFirmware

`func NewFirmware(model []string, filename string, size float64, version string, ) *Firmware`

NewFirmware instantiates a new Firmware object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareWithDefaults

`func NewFirmwareWithDefaults() *Firmware`

NewFirmwareWithDefaults instantiates a new Firmware object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *Firmware) GetModel() []string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *Firmware) GetModelOk() (*[]string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *Firmware) SetModel(v []string)`

SetModel sets Model field to given value.


### GetFirmwareAssets

`func (o *Firmware) GetFirmwareAssets() []string`

GetFirmwareAssets returns the FirmwareAssets field if non-nil, zero value otherwise.

### GetFirmwareAssetsOk

`func (o *Firmware) GetFirmwareAssetsOk() (*[]string, bool)`

GetFirmwareAssetsOk returns a tuple with the FirmwareAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmwareAssets

`func (o *Firmware) SetFirmwareAssets(v []string)`

SetFirmwareAssets sets FirmwareAssets field to given value.

### HasFirmwareAssets

`func (o *Firmware) HasFirmwareAssets() bool`

HasFirmwareAssets returns a boolean if a field has been set.

### SetFirmwareAssetsNil

`func (o *Firmware) SetFirmwareAssetsNil(b bool)`

 SetFirmwareAssetsNil sets the value for FirmwareAssets to be an explicit nil

### UnsetFirmwareAssets
`func (o *Firmware) UnsetFirmwareAssets()`

UnsetFirmwareAssets ensures that no value is present for FirmwareAssets, not even an explicit nil
### GetFilename

`func (o *Firmware) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *Firmware) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *Firmware) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetType

`func (o *Firmware) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Firmware) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Firmware) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Firmware) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSize

`func (o *Firmware) GetSize() float64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Firmware) GetSizeOk() (*float64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Firmware) SetSize(v float64)`

SetSize sets Size field to given value.


### GetUrl

`func (o *Firmware) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Firmware) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Firmware) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *Firmware) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *Firmware) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *Firmware) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetVersion

`func (o *Firmware) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *Firmware) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *Firmware) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetBuildId

`func (o *Firmware) GetBuildId() string`

GetBuildId returns the BuildId field if non-nil, zero value otherwise.

### GetBuildIdOk

`func (o *Firmware) GetBuildIdOk() (*string, bool)`

GetBuildIdOk returns a tuple with the BuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildId

`func (o *Firmware) SetBuildId(v string)`

SetBuildId sets BuildId field to given value.

### HasBuildId

`func (o *Firmware) HasBuildId() bool`

HasBuildId returns a boolean if a field has been set.

### SetBuildIdNil

`func (o *Firmware) SetBuildIdNil(b bool)`

 SetBuildIdNil sets the value for BuildId to be an explicit nil

### UnsetBuildId
`func (o *Firmware) UnsetBuildId()`

UnsetBuildId ensures that no value is present for BuildId, not even an explicit nil
### GetMd5sum

`func (o *Firmware) GetMd5sum() string`

GetMd5sum returns the Md5sum field if non-nil, zero value otherwise.

### GetMd5sumOk

`func (o *Firmware) GetMd5sumOk() (*string, bool)`

GetMd5sumOk returns a tuple with the Md5sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5sum

`func (o *Firmware) SetMd5sum(v string)`

SetMd5sum sets Md5sum field to given value.

### HasMd5sum

`func (o *Firmware) HasMd5sum() bool`

HasMd5sum returns a boolean if a field has been set.

### SetMd5sumNil

`func (o *Firmware) SetMd5sumNil(b bool)`

 SetMd5sumNil sets the value for Md5sum to be an explicit nil

### UnsetMd5sum
`func (o *Firmware) UnsetMd5sum()`

UnsetMd5sum ensures that no value is present for Md5sum, not even an explicit nil
### GetSha1sum

`func (o *Firmware) GetSha1sum() string`

GetSha1sum returns the Sha1sum field if non-nil, zero value otherwise.

### GetSha1sumOk

`func (o *Firmware) GetSha1sumOk() (*string, bool)`

GetSha1sumOk returns a tuple with the Sha1sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha1sum

`func (o *Firmware) SetSha1sum(v string)`

SetSha1sum sets Sha1sum field to given value.

### HasSha1sum

`func (o *Firmware) HasSha1sum() bool`

HasSha1sum returns a boolean if a field has been set.

### SetSha1sumNil

`func (o *Firmware) SetSha1sumNil(b bool)`

 SetSha1sumNil sets the value for Sha1sum to be an explicit nil

### UnsetSha1sum
`func (o *Firmware) UnsetSha1sum()`

UnsetSha1sum ensures that no value is present for Sha1sum, not even an explicit nil
### GetSha256sum

`func (o *Firmware) GetSha256sum() string`

GetSha256sum returns the Sha256sum field if non-nil, zero value otherwise.

### GetSha256sumOk

`func (o *Firmware) GetSha256sumOk() (*string, bool)`

GetSha256sumOk returns a tuple with the Sha256sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256sum

`func (o *Firmware) SetSha256sum(v string)`

SetSha256sum sets Sha256sum field to given value.

### HasSha256sum

`func (o *Firmware) HasSha256sum() bool`

HasSha256sum returns a boolean if a field has been set.

### SetSha256sumNil

`func (o *Firmware) SetSha256sumNil(b bool)`

 SetSha256sumNil sets the value for Sha256sum to be an explicit nil

### UnsetSha256sum
`func (o *Firmware) UnsetSha256sum()`

UnsetSha256sum ensures that no value is present for Sha256sum, not even an explicit nil
### GetCorelliumChecksum

`func (o *Firmware) GetCorelliumChecksum() string`

GetCorelliumChecksum returns the CorelliumChecksum field if non-nil, zero value otherwise.

### GetCorelliumChecksumOk

`func (o *Firmware) GetCorelliumChecksumOk() (*string, bool)`

GetCorelliumChecksumOk returns a tuple with the CorelliumChecksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorelliumChecksum

`func (o *Firmware) SetCorelliumChecksum(v string)`

SetCorelliumChecksum sets CorelliumChecksum field to given value.

### HasCorelliumChecksum

`func (o *Firmware) HasCorelliumChecksum() bool`

HasCorelliumChecksum returns a boolean if a field has been set.

### SetCorelliumChecksumNil

`func (o *Firmware) SetCorelliumChecksumNil(b bool)`

 SetCorelliumChecksumNil sets the value for CorelliumChecksum to be an explicit nil

### UnsetCorelliumChecksum
`func (o *Firmware) UnsetCorelliumChecksum()`

UnsetCorelliumChecksum ensures that no value is present for CorelliumChecksum, not even an explicit nil
### GetReleaseDate

`func (o *Firmware) GetReleaseDate() string`

GetReleaseDate returns the ReleaseDate field if non-nil, zero value otherwise.

### GetReleaseDateOk

`func (o *Firmware) GetReleaseDateOk() (*string, bool)`

GetReleaseDateOk returns a tuple with the ReleaseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseDate

`func (o *Firmware) SetReleaseDate(v string)`

SetReleaseDate sets ReleaseDate field to given value.

### HasReleaseDate

`func (o *Firmware) HasReleaseDate() bool`

HasReleaseDate returns a boolean if a field has been set.

### SetReleaseDateNil

`func (o *Firmware) SetReleaseDateNil(b bool)`

 SetReleaseDateNil sets the value for ReleaseDate to be an explicit nil

### UnsetReleaseDate
`func (o *Firmware) UnsetReleaseDate()`

UnsetReleaseDate ensures that no value is present for ReleaseDate, not even an explicit nil
### GetUploadDate

`func (o *Firmware) GetUploadDate() string`

GetUploadDate returns the UploadDate field if non-nil, zero value otherwise.

### GetUploadDateOk

`func (o *Firmware) GetUploadDateOk() (*string, bool)`

GetUploadDateOk returns a tuple with the UploadDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadDate

`func (o *Firmware) SetUploadDate(v string)`

SetUploadDate sets UploadDate field to given value.

### HasUploadDate

`func (o *Firmware) HasUploadDate() bool`

HasUploadDate returns a boolean if a field has been set.

### SetUploadDateNil

`func (o *Firmware) SetUploadDateNil(b bool)`

 SetUploadDateNil sets the value for UploadDate to be an explicit nil

### UnsetUploadDate
`func (o *Firmware) UnsetUploadDate()`

UnsetUploadDate ensures that no value is present for UploadDate, not even an explicit nil
### GetMetadata

`func (o *Firmware) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Firmware) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Firmware) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *Firmware) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *Firmware) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *Firmware) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetUniqueId

`func (o *Firmware) GetUniqueId() string`

GetUniqueId returns the UniqueId field if non-nil, zero value otherwise.

### GetUniqueIdOk

`func (o *Firmware) GetUniqueIdOk() (*string, bool)`

GetUniqueIdOk returns a tuple with the UniqueId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueId

`func (o *Firmware) SetUniqueId(v string)`

SetUniqueId sets UniqueId field to given value.

### HasUniqueId

`func (o *Firmware) HasUniqueId() bool`

HasUniqueId returns a boolean if a field has been set.

### SetUniqueIdNil

`func (o *Firmware) SetUniqueIdNil(b bool)`

 SetUniqueIdNil sets the value for UniqueId to be an explicit nil

### UnsetUniqueId
`func (o *Firmware) UnsetUniqueId()`

UnsetUniqueId ensures that no value is present for UniqueId, not even an explicit nil
### GetAndroidFlavor

`func (o *Firmware) GetAndroidFlavor() string`

GetAndroidFlavor returns the AndroidFlavor field if non-nil, zero value otherwise.

### GetAndroidFlavorOk

`func (o *Firmware) GetAndroidFlavorOk() (*string, bool)`

GetAndroidFlavorOk returns a tuple with the AndroidFlavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAndroidFlavor

`func (o *Firmware) SetAndroidFlavor(v string)`

SetAndroidFlavor sets AndroidFlavor field to given value.

### HasAndroidFlavor

`func (o *Firmware) HasAndroidFlavor() bool`

HasAndroidFlavor returns a boolean if a field has been set.

### SetAndroidFlavorNil

`func (o *Firmware) SetAndroidFlavorNil(b bool)`

 SetAndroidFlavorNil sets the value for AndroidFlavor to be an explicit nil

### UnsetAndroidFlavor
`func (o *Firmware) UnsetAndroidFlavor()`

UnsetAndroidFlavor ensures that no value is present for AndroidFlavor, not even an explicit nil
### GetApiVersion

`func (o *Firmware) GetApiVersion() string`

GetApiVersion returns the ApiVersion field if non-nil, zero value otherwise.

### GetApiVersionOk

`func (o *Firmware) GetApiVersionOk() (*string, bool)`

GetApiVersionOk returns a tuple with the ApiVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiVersion

`func (o *Firmware) SetApiVersion(v string)`

SetApiVersion sets ApiVersion field to given value.

### HasApiVersion

`func (o *Firmware) HasApiVersion() bool`

HasApiVersion returns a boolean if a field has been set.

### SetApiVersionNil

`func (o *Firmware) SetApiVersionNil(b bool)`

 SetApiVersionNil sets the value for ApiVersion to be an explicit nil

### UnsetApiVersion
`func (o *Firmware) UnsetApiVersion()`

UnsetApiVersion ensures that no value is present for ApiVersion, not even an explicit nil
### GetRooted

`func (o *Firmware) GetRooted() bool`

GetRooted returns the Rooted field if non-nil, zero value otherwise.

### GetRootedOk

`func (o *Firmware) GetRootedOk() (*bool, bool)`

GetRootedOk returns a tuple with the Rooted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRooted

`func (o *Firmware) SetRooted(v bool)`

SetRooted sets Rooted field to given value.

### HasRooted

`func (o *Firmware) HasRooted() bool`

HasRooted returns a boolean if a field has been set.

### SetRootedNil

`func (o *Firmware) SetRootedNil(b bool)`

 SetRootedNil sets the value for Rooted to be an explicit nil

### UnsetRooted
`func (o *Firmware) UnsetRooted()`

UnsetRooted ensures that no value is present for Rooted, not even an explicit nil
### GetInstalled

`func (o *Firmware) GetInstalled() bool`

GetInstalled returns the Installed field if non-nil, zero value otherwise.

### GetInstalledOk

`func (o *Firmware) GetInstalledOk() (*bool, bool)`

GetInstalledOk returns a tuple with the Installed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstalled

`func (o *Firmware) SetInstalled(v bool)`

SetInstalled sets Installed field to given value.

### HasInstalled

`func (o *Firmware) HasInstalled() bool`

HasInstalled returns a boolean if a field has been set.

### SetInstalledNil

`func (o *Firmware) SetInstalledNil(b bool)`

 SetInstalledNil sets the value for Installed to be an explicit nil

### UnsetInstalled
`func (o *Firmware) UnsetInstalled()`

UnsetInstalled ensures that no value is present for Installed, not even an explicit nil
### GetCreatedAt

`func (o *Firmware) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Firmware) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Firmware) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Firmware) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Firmware) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Firmware) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Firmware) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Firmware) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


