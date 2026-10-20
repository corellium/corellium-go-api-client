# StorageFile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | File or directory name. | 
**Ext** | **NullableString** | File extension, or null for directories. | 
**Type** | **string** | Entry type. | 
**Size** | **float32** | Size in bytes (0 for directories). | 
**LastModifiedTime** | **NullableTime** | Last modified timestamp, or 1970-01-01T00:00:00.000Z when the entry could not be stat&#39;d. | 

## Methods

### NewStorageFile

`func NewStorageFile(name string, ext NullableString, type_ string, size float32, lastModifiedTime NullableTime, ) *StorageFile`

NewStorageFile instantiates a new StorageFile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStorageFileWithDefaults

`func NewStorageFileWithDefaults() *StorageFile`

NewStorageFileWithDefaults instantiates a new StorageFile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *StorageFile) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StorageFile) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StorageFile) SetName(v string)`

SetName sets Name field to given value.


### GetExt

`func (o *StorageFile) GetExt() string`

GetExt returns the Ext field if non-nil, zero value otherwise.

### GetExtOk

`func (o *StorageFile) GetExtOk() (*string, bool)`

GetExtOk returns a tuple with the Ext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExt

`func (o *StorageFile) SetExt(v string)`

SetExt sets Ext field to given value.


### SetExtNil

`func (o *StorageFile) SetExtNil(b bool)`

 SetExtNil sets the value for Ext to be an explicit nil

### UnsetExt
`func (o *StorageFile) UnsetExt()`

UnsetExt ensures that no value is present for Ext, not even an explicit nil
### GetType

`func (o *StorageFile) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *StorageFile) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *StorageFile) SetType(v string)`

SetType sets Type field to given value.


### GetSize

`func (o *StorageFile) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *StorageFile) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *StorageFile) SetSize(v float32)`

SetSize sets Size field to given value.


### GetLastModifiedTime

`func (o *StorageFile) GetLastModifiedTime() time.Time`

GetLastModifiedTime returns the LastModifiedTime field if non-nil, zero value otherwise.

### GetLastModifiedTimeOk

`func (o *StorageFile) GetLastModifiedTimeOk() (*time.Time, bool)`

GetLastModifiedTimeOk returns a tuple with the LastModifiedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifiedTime

`func (o *StorageFile) SetLastModifiedTime(v time.Time)`

SetLastModifiedTime sets LastModifiedTime field to given value.


### SetLastModifiedTimeNil

`func (o *StorageFile) SetLastModifiedTimeNil(b bool)`

 SetLastModifiedTimeNil sets the value for LastModifiedTime to be an explicit nil

### UnsetLastModifiedTime
`func (o *StorageFile) UnsetLastModifiedTime()`

UnsetLastModifiedTime ensures that no value is present for LastModifiedTime, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


