# FirmwareAsset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **string** | Owning domain identifier. | 
**Url** | **string** | Asset URL. | 
**Payload** | **string** | Base64-encoded asset payload. | 
**Size** | **float64** | Asset size in bytes. | 
**Md5sum** | Pointer to **string** | MD5 checksum. | [optional] 
**Sha1sum** | Pointer to **string** | SHA-1 checksum. | [optional] 
**Sha256sum** | Pointer to **string** | SHA-256 checksum. | [optional] 
**UploadDate** | Pointer to **NullableString** | Upload date; may be an empty string. | [optional] 
**CreatedAt** | Pointer to **time.Time** | When the record was created. | [optional] 
**UpdatedAt** | Pointer to **time.Time** | When the record was last updated. | [optional] 

## Methods

### NewFirmwareAsset

`func NewFirmwareAsset(domain string, url string, payload string, size float64, ) *FirmwareAsset`

NewFirmwareAsset instantiates a new FirmwareAsset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareAssetWithDefaults

`func NewFirmwareAssetWithDefaults() *FirmwareAsset`

NewFirmwareAssetWithDefaults instantiates a new FirmwareAsset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *FirmwareAsset) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *FirmwareAsset) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *FirmwareAsset) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetUrl

`func (o *FirmwareAsset) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FirmwareAsset) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FirmwareAsset) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetPayload

`func (o *FirmwareAsset) GetPayload() string`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *FirmwareAsset) GetPayloadOk() (*string, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *FirmwareAsset) SetPayload(v string)`

SetPayload sets Payload field to given value.


### GetSize

`func (o *FirmwareAsset) GetSize() float64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FirmwareAsset) GetSizeOk() (*float64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FirmwareAsset) SetSize(v float64)`

SetSize sets Size field to given value.


### GetMd5sum

`func (o *FirmwareAsset) GetMd5sum() string`

GetMd5sum returns the Md5sum field if non-nil, zero value otherwise.

### GetMd5sumOk

`func (o *FirmwareAsset) GetMd5sumOk() (*string, bool)`

GetMd5sumOk returns a tuple with the Md5sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5sum

`func (o *FirmwareAsset) SetMd5sum(v string)`

SetMd5sum sets Md5sum field to given value.

### HasMd5sum

`func (o *FirmwareAsset) HasMd5sum() bool`

HasMd5sum returns a boolean if a field has been set.

### GetSha1sum

`func (o *FirmwareAsset) GetSha1sum() string`

GetSha1sum returns the Sha1sum field if non-nil, zero value otherwise.

### GetSha1sumOk

`func (o *FirmwareAsset) GetSha1sumOk() (*string, bool)`

GetSha1sumOk returns a tuple with the Sha1sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha1sum

`func (o *FirmwareAsset) SetSha1sum(v string)`

SetSha1sum sets Sha1sum field to given value.

### HasSha1sum

`func (o *FirmwareAsset) HasSha1sum() bool`

HasSha1sum returns a boolean if a field has been set.

### GetSha256sum

`func (o *FirmwareAsset) GetSha256sum() string`

GetSha256sum returns the Sha256sum field if non-nil, zero value otherwise.

### GetSha256sumOk

`func (o *FirmwareAsset) GetSha256sumOk() (*string, bool)`

GetSha256sumOk returns a tuple with the Sha256sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256sum

`func (o *FirmwareAsset) SetSha256sum(v string)`

SetSha256sum sets Sha256sum field to given value.

### HasSha256sum

`func (o *FirmwareAsset) HasSha256sum() bool`

HasSha256sum returns a boolean if a field has been set.

### GetUploadDate

`func (o *FirmwareAsset) GetUploadDate() string`

GetUploadDate returns the UploadDate field if non-nil, zero value otherwise.

### GetUploadDateOk

`func (o *FirmwareAsset) GetUploadDateOk() (*string, bool)`

GetUploadDateOk returns a tuple with the UploadDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadDate

`func (o *FirmwareAsset) SetUploadDate(v string)`

SetUploadDate sets UploadDate field to given value.

### HasUploadDate

`func (o *FirmwareAsset) HasUploadDate() bool`

HasUploadDate returns a boolean if a field has been set.

### SetUploadDateNil

`func (o *FirmwareAsset) SetUploadDateNil(b bool)`

 SetUploadDateNil sets the value for UploadDate to be an explicit nil

### UnsetUploadDate
`func (o *FirmwareAsset) UnsetUploadDate()`

UnsetUploadDate ensures that no value is present for UploadDate, not even an explicit nil
### GetCreatedAt

`func (o *FirmwareAsset) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FirmwareAsset) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FirmwareAsset) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FirmwareAsset) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *FirmwareAsset) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FirmwareAsset) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FirmwareAsset) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FirmwareAsset) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


