# Image

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** | Image status. | 
**Id** | **string** | Image ID. | 
**Name** | **string** | Name of the image, usually the original filename. Names are not unique: several images can share a name. | 
**Type** | [**ImageType**](ImageType.md) |  | 
**Size** | Pointer to **NullableFloat32** | Size in bytes; null until upload completes. | [optional] 
**Checksum** | Pointer to **NullableString** | MD5 checksum; null until upload completes. | [optional] 
**CorelliumChecksum** | Pointer to **NullableString** | Corellium checksum of the image; null until upload completes. | [optional] 
**Encoding** | Pointer to [**ImageEncoding**](ImageEncoding.md) |  | [optional] 
**Project** | Pointer to **NullableString** | ID of the project the image belongs to. Null for a domain-level image, which is available across your domain rather than to one project. | [optional] 
**Instance** | Pointer to **NullableString** | ID of the instance (device) the image is attached to, or null if it is not attached to one. | [optional] 
**CreatedAt** | Pointer to **time.Time** | When Image was created. | [optional] 
**UpdatedAt** | Pointer to **time.Time** | When Image was last updated. | [optional] 

## Methods

### NewImage

`func NewImage(status string, id string, name string, type_ ImageType, ) *Image`

NewImage instantiates a new Image object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageWithDefaults

`func NewImageWithDefaults() *Image`

NewImageWithDefaults instantiates a new Image object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *Image) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Image) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Image) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetId

`func (o *Image) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Image) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Image) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *Image) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Image) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Image) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *Image) GetType() ImageType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Image) GetTypeOk() (*ImageType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Image) SetType(v ImageType)`

SetType sets Type field to given value.


### GetSize

`func (o *Image) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Image) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Image) SetSize(v float32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Image) HasSize() bool`

HasSize returns a boolean if a field has been set.

### SetSizeNil

`func (o *Image) SetSizeNil(b bool)`

 SetSizeNil sets the value for Size to be an explicit nil

### UnsetSize
`func (o *Image) UnsetSize()`

UnsetSize ensures that no value is present for Size, not even an explicit nil
### GetChecksum

`func (o *Image) GetChecksum() string`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *Image) GetChecksumOk() (*string, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *Image) SetChecksum(v string)`

SetChecksum sets Checksum field to given value.

### HasChecksum

`func (o *Image) HasChecksum() bool`

HasChecksum returns a boolean if a field has been set.

### SetChecksumNil

`func (o *Image) SetChecksumNil(b bool)`

 SetChecksumNil sets the value for Checksum to be an explicit nil

### UnsetChecksum
`func (o *Image) UnsetChecksum()`

UnsetChecksum ensures that no value is present for Checksum, not even an explicit nil
### GetCorelliumChecksum

`func (o *Image) GetCorelliumChecksum() string`

GetCorelliumChecksum returns the CorelliumChecksum field if non-nil, zero value otherwise.

### GetCorelliumChecksumOk

`func (o *Image) GetCorelliumChecksumOk() (*string, bool)`

GetCorelliumChecksumOk returns a tuple with the CorelliumChecksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorelliumChecksum

`func (o *Image) SetCorelliumChecksum(v string)`

SetCorelliumChecksum sets CorelliumChecksum field to given value.

### HasCorelliumChecksum

`func (o *Image) HasCorelliumChecksum() bool`

HasCorelliumChecksum returns a boolean if a field has been set.

### SetCorelliumChecksumNil

`func (o *Image) SetCorelliumChecksumNil(b bool)`

 SetCorelliumChecksumNil sets the value for CorelliumChecksum to be an explicit nil

### UnsetCorelliumChecksum
`func (o *Image) UnsetCorelliumChecksum()`

UnsetCorelliumChecksum ensures that no value is present for CorelliumChecksum, not even an explicit nil
### GetEncoding

`func (o *Image) GetEncoding() ImageEncoding`

GetEncoding returns the Encoding field if non-nil, zero value otherwise.

### GetEncodingOk

`func (o *Image) GetEncodingOk() (*ImageEncoding, bool)`

GetEncodingOk returns a tuple with the Encoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncoding

`func (o *Image) SetEncoding(v ImageEncoding)`

SetEncoding sets Encoding field to given value.

### HasEncoding

`func (o *Image) HasEncoding() bool`

HasEncoding returns a boolean if a field has been set.

### GetProject

`func (o *Image) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *Image) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *Image) SetProject(v string)`

SetProject sets Project field to given value.

### HasProject

`func (o *Image) HasProject() bool`

HasProject returns a boolean if a field has been set.

### SetProjectNil

`func (o *Image) SetProjectNil(b bool)`

 SetProjectNil sets the value for Project to be an explicit nil

### UnsetProject
`func (o *Image) UnsetProject()`

UnsetProject ensures that no value is present for Project, not even an explicit nil
### GetInstance

`func (o *Image) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *Image) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *Image) SetInstance(v string)`

SetInstance sets Instance field to given value.

### HasInstance

`func (o *Image) HasInstance() bool`

HasInstance returns a boolean if a field has been set.

### SetInstanceNil

`func (o *Image) SetInstanceNil(b bool)`

 SetInstanceNil sets the value for Instance to be an explicit nil

### UnsetInstance
`func (o *Image) UnsetInstance()`

UnsetInstance ensures that no value is present for Instance, not even an explicit nil
### GetCreatedAt

`func (o *Image) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Image) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Image) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Image) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Image) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Image) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Image) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Image) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


