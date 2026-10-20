# ImageV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **NullableString** | Image status | [optional] 
**Id** | Pointer to **NullableString** | Image ID | [optional] 
**Identifier** | Pointer to **NullableString** | Image ID | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**Type** | Pointer to **NullableString** | Type of image | [optional] 
**Size** | Pointer to **NullableFloat32** |  | [optional] 
**Checksum** | Pointer to **NullableString** | MD5 checksum of the image | [optional] 
**CorelliumChecksum** | Pointer to **NullableString** | Corellium checksum of the image (format: algorithm$blocksize$hash) | [optional] 
**Encoding** | Pointer to **NullableString** | Encoding type of the image | [optional] 
**Filename** | Pointer to **NullableString** |  | [optional] 
**Uniqueid** | Pointer to **NullableString** |  | [optional] 
**Project** | Pointer to **NullableString** | Project ID | [optional] 
**Instance** | Pointer to **NullableString** | Instance ID | [optional] 
**CreatedAt** | Pointer to **NullableTime** | When Image was created | [optional] 
**UpdatedAt** | Pointer to **NullableTime** | When Image was last updated | [optional] 
**Extended** | Pointer to [**ImageExtended**](ImageExtended.md) |  | [optional] 

## Methods

### NewImageV1

`func NewImageV1() *ImageV1`

NewImageV1 instantiates a new ImageV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageV1WithDefaults

`func NewImageV1WithDefaults() *ImageV1`

NewImageV1WithDefaults instantiates a new ImageV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ImageV1) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ImageV1) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ImageV1) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ImageV1) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *ImageV1) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *ImageV1) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetId

`func (o *ImageV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ImageV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ImageV1) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ImageV1) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *ImageV1) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *ImageV1) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetIdentifier

`func (o *ImageV1) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ImageV1) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ImageV1) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *ImageV1) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### SetIdentifierNil

`func (o *ImageV1) SetIdentifierNil(b bool)`

 SetIdentifierNil sets the value for Identifier to be an explicit nil

### UnsetIdentifier
`func (o *ImageV1) UnsetIdentifier()`

UnsetIdentifier ensures that no value is present for Identifier, not even an explicit nil
### GetName

`func (o *ImageV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ImageV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ImageV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ImageV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ImageV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ImageV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetType

`func (o *ImageV1) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ImageV1) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ImageV1) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ImageV1) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *ImageV1) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *ImageV1) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetSize

`func (o *ImageV1) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *ImageV1) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *ImageV1) SetSize(v float32)`

SetSize sets Size field to given value.

### HasSize

`func (o *ImageV1) HasSize() bool`

HasSize returns a boolean if a field has been set.

### SetSizeNil

`func (o *ImageV1) SetSizeNil(b bool)`

 SetSizeNil sets the value for Size to be an explicit nil

### UnsetSize
`func (o *ImageV1) UnsetSize()`

UnsetSize ensures that no value is present for Size, not even an explicit nil
### GetChecksum

`func (o *ImageV1) GetChecksum() string`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *ImageV1) GetChecksumOk() (*string, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *ImageV1) SetChecksum(v string)`

SetChecksum sets Checksum field to given value.

### HasChecksum

`func (o *ImageV1) HasChecksum() bool`

HasChecksum returns a boolean if a field has been set.

### SetChecksumNil

`func (o *ImageV1) SetChecksumNil(b bool)`

 SetChecksumNil sets the value for Checksum to be an explicit nil

### UnsetChecksum
`func (o *ImageV1) UnsetChecksum()`

UnsetChecksum ensures that no value is present for Checksum, not even an explicit nil
### GetCorelliumChecksum

`func (o *ImageV1) GetCorelliumChecksum() string`

GetCorelliumChecksum returns the CorelliumChecksum field if non-nil, zero value otherwise.

### GetCorelliumChecksumOk

`func (o *ImageV1) GetCorelliumChecksumOk() (*string, bool)`

GetCorelliumChecksumOk returns a tuple with the CorelliumChecksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorelliumChecksum

`func (o *ImageV1) SetCorelliumChecksum(v string)`

SetCorelliumChecksum sets CorelliumChecksum field to given value.

### HasCorelliumChecksum

`func (o *ImageV1) HasCorelliumChecksum() bool`

HasCorelliumChecksum returns a boolean if a field has been set.

### SetCorelliumChecksumNil

`func (o *ImageV1) SetCorelliumChecksumNil(b bool)`

 SetCorelliumChecksumNil sets the value for CorelliumChecksum to be an explicit nil

### UnsetCorelliumChecksum
`func (o *ImageV1) UnsetCorelliumChecksum()`

UnsetCorelliumChecksum ensures that no value is present for CorelliumChecksum, not even an explicit nil
### GetEncoding

`func (o *ImageV1) GetEncoding() string`

GetEncoding returns the Encoding field if non-nil, zero value otherwise.

### GetEncodingOk

`func (o *ImageV1) GetEncodingOk() (*string, bool)`

GetEncodingOk returns a tuple with the Encoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncoding

`func (o *ImageV1) SetEncoding(v string)`

SetEncoding sets Encoding field to given value.

### HasEncoding

`func (o *ImageV1) HasEncoding() bool`

HasEncoding returns a boolean if a field has been set.

### SetEncodingNil

`func (o *ImageV1) SetEncodingNil(b bool)`

 SetEncodingNil sets the value for Encoding to be an explicit nil

### UnsetEncoding
`func (o *ImageV1) UnsetEncoding()`

UnsetEncoding ensures that no value is present for Encoding, not even an explicit nil
### GetFilename

`func (o *ImageV1) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *ImageV1) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *ImageV1) SetFilename(v string)`

SetFilename sets Filename field to given value.

### HasFilename

`func (o *ImageV1) HasFilename() bool`

HasFilename returns a boolean if a field has been set.

### SetFilenameNil

`func (o *ImageV1) SetFilenameNil(b bool)`

 SetFilenameNil sets the value for Filename to be an explicit nil

### UnsetFilename
`func (o *ImageV1) UnsetFilename()`

UnsetFilename ensures that no value is present for Filename, not even an explicit nil
### GetUniqueid

`func (o *ImageV1) GetUniqueid() string`

GetUniqueid returns the Uniqueid field if non-nil, zero value otherwise.

### GetUniqueidOk

`func (o *ImageV1) GetUniqueidOk() (*string, bool)`

GetUniqueidOk returns a tuple with the Uniqueid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueid

`func (o *ImageV1) SetUniqueid(v string)`

SetUniqueid sets Uniqueid field to given value.

### HasUniqueid

`func (o *ImageV1) HasUniqueid() bool`

HasUniqueid returns a boolean if a field has been set.

### SetUniqueidNil

`func (o *ImageV1) SetUniqueidNil(b bool)`

 SetUniqueidNil sets the value for Uniqueid to be an explicit nil

### UnsetUniqueid
`func (o *ImageV1) UnsetUniqueid()`

UnsetUniqueid ensures that no value is present for Uniqueid, not even an explicit nil
### GetProject

`func (o *ImageV1) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ImageV1) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ImageV1) SetProject(v string)`

SetProject sets Project field to given value.

### HasProject

`func (o *ImageV1) HasProject() bool`

HasProject returns a boolean if a field has been set.

### SetProjectNil

`func (o *ImageV1) SetProjectNil(b bool)`

 SetProjectNil sets the value for Project to be an explicit nil

### UnsetProject
`func (o *ImageV1) UnsetProject()`

UnsetProject ensures that no value is present for Project, not even an explicit nil
### GetInstance

`func (o *ImageV1) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *ImageV1) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *ImageV1) SetInstance(v string)`

SetInstance sets Instance field to given value.

### HasInstance

`func (o *ImageV1) HasInstance() bool`

HasInstance returns a boolean if a field has been set.

### SetInstanceNil

`func (o *ImageV1) SetInstanceNil(b bool)`

 SetInstanceNil sets the value for Instance to be an explicit nil

### UnsetInstance
`func (o *ImageV1) UnsetInstance()`

UnsetInstance ensures that no value is present for Instance, not even an explicit nil
### GetCreatedAt

`func (o *ImageV1) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ImageV1) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ImageV1) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ImageV1) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *ImageV1) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ImageV1) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *ImageV1) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ImageV1) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ImageV1) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ImageV1) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *ImageV1) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *ImageV1) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetExtended

`func (o *ImageV1) GetExtended() ImageExtended`

GetExtended returns the Extended field if non-nil, zero value otherwise.

### GetExtendedOk

`func (o *ImageV1) GetExtendedOk() (*ImageExtended, bool)`

GetExtendedOk returns a tuple with the Extended field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtended

`func (o *ImageV1) SetExtended(v ImageExtended)`

SetExtended sets Extended field to given value.

### HasExtended

`func (o *ImageV1) HasExtended() bool`

HasExtended returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


