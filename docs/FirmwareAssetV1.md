# FirmwareAssetV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **string** |  | 
**Url** | **string** |  | 
**Payload** | **string** |  | 
**Size** | **float32** |  | 
**Md5sum** | Pointer to **NullableString** |  | [optional] 
**Sha1sum** | Pointer to **NullableString** |  | [optional] 
**Sha256sum** | Pointer to **NullableString** |  | [optional] 
**Uploaddate** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **NullableString** |  | [optional] 
**UpdatedAt** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewFirmwareAssetV1

`func NewFirmwareAssetV1(domain string, url string, payload string, size float32, ) *FirmwareAssetV1`

NewFirmwareAssetV1 instantiates a new FirmwareAssetV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareAssetV1WithDefaults

`func NewFirmwareAssetV1WithDefaults() *FirmwareAssetV1`

NewFirmwareAssetV1WithDefaults instantiates a new FirmwareAssetV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *FirmwareAssetV1) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *FirmwareAssetV1) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *FirmwareAssetV1) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetUrl

`func (o *FirmwareAssetV1) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FirmwareAssetV1) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FirmwareAssetV1) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetPayload

`func (o *FirmwareAssetV1) GetPayload() string`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *FirmwareAssetV1) GetPayloadOk() (*string, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *FirmwareAssetV1) SetPayload(v string)`

SetPayload sets Payload field to given value.


### GetSize

`func (o *FirmwareAssetV1) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FirmwareAssetV1) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FirmwareAssetV1) SetSize(v float32)`

SetSize sets Size field to given value.


### GetMd5sum

`func (o *FirmwareAssetV1) GetMd5sum() string`

GetMd5sum returns the Md5sum field if non-nil, zero value otherwise.

### GetMd5sumOk

`func (o *FirmwareAssetV1) GetMd5sumOk() (*string, bool)`

GetMd5sumOk returns a tuple with the Md5sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5sum

`func (o *FirmwareAssetV1) SetMd5sum(v string)`

SetMd5sum sets Md5sum field to given value.

### HasMd5sum

`func (o *FirmwareAssetV1) HasMd5sum() bool`

HasMd5sum returns a boolean if a field has been set.

### SetMd5sumNil

`func (o *FirmwareAssetV1) SetMd5sumNil(b bool)`

 SetMd5sumNil sets the value for Md5sum to be an explicit nil

### UnsetMd5sum
`func (o *FirmwareAssetV1) UnsetMd5sum()`

UnsetMd5sum ensures that no value is present for Md5sum, not even an explicit nil
### GetSha1sum

`func (o *FirmwareAssetV1) GetSha1sum() string`

GetSha1sum returns the Sha1sum field if non-nil, zero value otherwise.

### GetSha1sumOk

`func (o *FirmwareAssetV1) GetSha1sumOk() (*string, bool)`

GetSha1sumOk returns a tuple with the Sha1sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha1sum

`func (o *FirmwareAssetV1) SetSha1sum(v string)`

SetSha1sum sets Sha1sum field to given value.

### HasSha1sum

`func (o *FirmwareAssetV1) HasSha1sum() bool`

HasSha1sum returns a boolean if a field has been set.

### SetSha1sumNil

`func (o *FirmwareAssetV1) SetSha1sumNil(b bool)`

 SetSha1sumNil sets the value for Sha1sum to be an explicit nil

### UnsetSha1sum
`func (o *FirmwareAssetV1) UnsetSha1sum()`

UnsetSha1sum ensures that no value is present for Sha1sum, not even an explicit nil
### GetSha256sum

`func (o *FirmwareAssetV1) GetSha256sum() string`

GetSha256sum returns the Sha256sum field if non-nil, zero value otherwise.

### GetSha256sumOk

`func (o *FirmwareAssetV1) GetSha256sumOk() (*string, bool)`

GetSha256sumOk returns a tuple with the Sha256sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256sum

`func (o *FirmwareAssetV1) SetSha256sum(v string)`

SetSha256sum sets Sha256sum field to given value.

### HasSha256sum

`func (o *FirmwareAssetV1) HasSha256sum() bool`

HasSha256sum returns a boolean if a field has been set.

### SetSha256sumNil

`func (o *FirmwareAssetV1) SetSha256sumNil(b bool)`

 SetSha256sumNil sets the value for Sha256sum to be an explicit nil

### UnsetSha256sum
`func (o *FirmwareAssetV1) UnsetSha256sum()`

UnsetSha256sum ensures that no value is present for Sha256sum, not even an explicit nil
### GetUploaddate

`func (o *FirmwareAssetV1) GetUploaddate() string`

GetUploaddate returns the Uploaddate field if non-nil, zero value otherwise.

### GetUploaddateOk

`func (o *FirmwareAssetV1) GetUploaddateOk() (*string, bool)`

GetUploaddateOk returns a tuple with the Uploaddate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploaddate

`func (o *FirmwareAssetV1) SetUploaddate(v string)`

SetUploaddate sets Uploaddate field to given value.

### HasUploaddate

`func (o *FirmwareAssetV1) HasUploaddate() bool`

HasUploaddate returns a boolean if a field has been set.

### SetUploaddateNil

`func (o *FirmwareAssetV1) SetUploaddateNil(b bool)`

 SetUploaddateNil sets the value for Uploaddate to be an explicit nil

### UnsetUploaddate
`func (o *FirmwareAssetV1) UnsetUploaddate()`

UnsetUploaddate ensures that no value is present for Uploaddate, not even an explicit nil
### GetCreatedAt

`func (o *FirmwareAssetV1) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FirmwareAssetV1) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FirmwareAssetV1) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FirmwareAssetV1) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *FirmwareAssetV1) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *FirmwareAssetV1) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *FirmwareAssetV1) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FirmwareAssetV1) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FirmwareAssetV1) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *FirmwareAssetV1) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *FirmwareAssetV1) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *FirmwareAssetV1) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


