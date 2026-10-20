# ImageCreationOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Image type | 
**Encoding** | **string** | How the file is stored | 
**Encapsulated** | Pointer to **NullableBool** | set to false if the uploaded file is not encapsulated inside an outer zipfile | [optional] 
**Name** | Pointer to **NullableString** | Image name | [optional] 
**FullPath** | Pointer to **NullableString** | Full local path to image file. When specified, this file MUST exist! | [optional] 
**Project** | Pointer to **NullableString** | Project ID | [optional] 
**Instance** | Pointer to **NullableString** | Instance ID | [optional] 
**File** | Pointer to ***os.File** | Optionally the actual file | [optional] 

## Methods

### NewImageCreationOptions

`func NewImageCreationOptions(type_ string, encoding string, ) *ImageCreationOptions`

NewImageCreationOptions instantiates a new ImageCreationOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageCreationOptionsWithDefaults

`func NewImageCreationOptionsWithDefaults() *ImageCreationOptions`

NewImageCreationOptionsWithDefaults instantiates a new ImageCreationOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ImageCreationOptions) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ImageCreationOptions) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ImageCreationOptions) SetType(v string)`

SetType sets Type field to given value.


### GetEncoding

`func (o *ImageCreationOptions) GetEncoding() string`

GetEncoding returns the Encoding field if non-nil, zero value otherwise.

### GetEncodingOk

`func (o *ImageCreationOptions) GetEncodingOk() (*string, bool)`

GetEncodingOk returns a tuple with the Encoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncoding

`func (o *ImageCreationOptions) SetEncoding(v string)`

SetEncoding sets Encoding field to given value.


### GetEncapsulated

`func (o *ImageCreationOptions) GetEncapsulated() bool`

GetEncapsulated returns the Encapsulated field if non-nil, zero value otherwise.

### GetEncapsulatedOk

`func (o *ImageCreationOptions) GetEncapsulatedOk() (*bool, bool)`

GetEncapsulatedOk returns a tuple with the Encapsulated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncapsulated

`func (o *ImageCreationOptions) SetEncapsulated(v bool)`

SetEncapsulated sets Encapsulated field to given value.

### HasEncapsulated

`func (o *ImageCreationOptions) HasEncapsulated() bool`

HasEncapsulated returns a boolean if a field has been set.

### SetEncapsulatedNil

`func (o *ImageCreationOptions) SetEncapsulatedNil(b bool)`

 SetEncapsulatedNil sets the value for Encapsulated to be an explicit nil

### UnsetEncapsulated
`func (o *ImageCreationOptions) UnsetEncapsulated()`

UnsetEncapsulated ensures that no value is present for Encapsulated, not even an explicit nil
### GetName

`func (o *ImageCreationOptions) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ImageCreationOptions) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ImageCreationOptions) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ImageCreationOptions) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ImageCreationOptions) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ImageCreationOptions) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetFullPath

`func (o *ImageCreationOptions) GetFullPath() string`

GetFullPath returns the FullPath field if non-nil, zero value otherwise.

### GetFullPathOk

`func (o *ImageCreationOptions) GetFullPathOk() (*string, bool)`

GetFullPathOk returns a tuple with the FullPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullPath

`func (o *ImageCreationOptions) SetFullPath(v string)`

SetFullPath sets FullPath field to given value.

### HasFullPath

`func (o *ImageCreationOptions) HasFullPath() bool`

HasFullPath returns a boolean if a field has been set.

### SetFullPathNil

`func (o *ImageCreationOptions) SetFullPathNil(b bool)`

 SetFullPathNil sets the value for FullPath to be an explicit nil

### UnsetFullPath
`func (o *ImageCreationOptions) UnsetFullPath()`

UnsetFullPath ensures that no value is present for FullPath, not even an explicit nil
### GetProject

`func (o *ImageCreationOptions) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ImageCreationOptions) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ImageCreationOptions) SetProject(v string)`

SetProject sets Project field to given value.

### HasProject

`func (o *ImageCreationOptions) HasProject() bool`

HasProject returns a boolean if a field has been set.

### SetProjectNil

`func (o *ImageCreationOptions) SetProjectNil(b bool)`

 SetProjectNil sets the value for Project to be an explicit nil

### UnsetProject
`func (o *ImageCreationOptions) UnsetProject()`

UnsetProject ensures that no value is present for Project, not even an explicit nil
### GetInstance

`func (o *ImageCreationOptions) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *ImageCreationOptions) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *ImageCreationOptions) SetInstance(v string)`

SetInstance sets Instance field to given value.

### HasInstance

`func (o *ImageCreationOptions) HasInstance() bool`

HasInstance returns a boolean if a field has been set.

### SetInstanceNil

`func (o *ImageCreationOptions) SetInstanceNil(b bool)`

 SetInstanceNil sets the value for Instance to be an explicit nil

### UnsetInstance
`func (o *ImageCreationOptions) UnsetInstance()`

UnsetInstance ensures that no value is present for Instance, not even an explicit nil
### GetFile

`func (o *ImageCreationOptions) GetFile() *os.File`

GetFile returns the File field if non-nil, zero value otherwise.

### GetFileOk

`func (o *ImageCreationOptions) GetFileOk() (**os.File, bool)`

GetFileOk returns a tuple with the File field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFile

`func (o *ImageCreationOptions) SetFile(v *os.File)`

SetFile sets File field to given value.

### HasFile

`func (o *ImageCreationOptions) HasFile() bool`

HasFile returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


