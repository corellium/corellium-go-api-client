# CreateImageBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**ImageType**](ImageType.md) |  | 
**Encoding** | [**ImageEncoding**](ImageEncoding.md) |  | 
**Encapsulated** | Pointer to **NullableBool** | Whether the uploaded file is a ZIP wrapper the server should unzip. Leave this unset or false when you upload a file directly (a one-shot multipart create defaults it to false); only browser-style wrapped uploads set it to true. | [optional] 
**Name** | Pointer to **NullableString** | Name for the image. In a multipart upload it defaults to the filename of the uploaded file; in a JSON request you must supply it. Names do not have to be unique. For &#x60;partition&#x60; images this must be the name of the partition to replace. | [optional] 
**FullPath** | Pointer to **NullableString** | Not for normal API use. Registers a file that already exists on the server instead of uploading one; it is used by cluster installation tools. Leave it unset. | [optional] 
**ProjectId** | Pointer to **NullableString** | Optional. Puts the image in this project. You must have access to the project (otherwise 403). Project images count against the project&#39;s storage quota.  **Lifetime.** The image is deleted automatically when the project is deleted, which makes a scratch project a simple way to clean up test uploads.  **Booting from it.** Project firmware images do not appear in &#x60;GET /v3/models/{model}/software&#x60;. To create a device from one, pass the image &#x60;id&#x60; as &#x60;fwPackage&#x60; to &#x60;POST /v3/instances&#x60;; no install step is needed. Also pass &#x60;osVersion&#x60; or &#x60;osBuild&#x60;; if you do not know them, read them from the file first with &#x60;POST /v3/images/{imageId}/fwinfo&#x60;. Models whose &#x60;supportsCustomFirmwareImage&#x60; is false reject an image ID in &#x60;fwPackage&#x60;.  Side effect: if the project already holds 5 or more images that are not attached to an instance, the oldest of them is deleted to make room.  Ignored when &#x60;instanceId&#x60; is set: the image then belongs to that instance&#39;s project. Leave both unset to create a domain-level image. | [optional] 
**InstanceId** | Pointer to **NullableString** | Optional. Attaches the image to this instance (device). The instance must exist (otherwise 404), and the image is placed in the instance&#39;s project. The instance can be running, paused or off.  **Lifetime.** The image is deleted automatically when the instance is deleted.  Side effect: any image of the same &#x60;type&#x60; already attached to the instance is deleted first, so each instance keeps at most one image per type. For &#x60;partition&#x60; images only the one with the same &#x60;name&#x60; is replaced. MATRIX types (&#x60;mast-*&#x60;) are never deleted this way, so a device can keep a history of MATRIX files. | [optional] 
**File** | Pointer to ***os.File** | Multipart requests only: the file contents. Send the &#x60;type&#x60; and other fields before this part. Omit it (or use a JSON request) to create the record now and upload the contents later. | [optional] 

## Methods

### NewCreateImageBody

`func NewCreateImageBody(type_ ImageType, encoding ImageEncoding, ) *CreateImageBody`

NewCreateImageBody instantiates a new CreateImageBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateImageBodyWithDefaults

`func NewCreateImageBodyWithDefaults() *CreateImageBody`

NewCreateImageBodyWithDefaults instantiates a new CreateImageBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateImageBody) GetType() ImageType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateImageBody) GetTypeOk() (*ImageType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateImageBody) SetType(v ImageType)`

SetType sets Type field to given value.


### GetEncoding

`func (o *CreateImageBody) GetEncoding() ImageEncoding`

GetEncoding returns the Encoding field if non-nil, zero value otherwise.

### GetEncodingOk

`func (o *CreateImageBody) GetEncodingOk() (*ImageEncoding, bool)`

GetEncodingOk returns a tuple with the Encoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncoding

`func (o *CreateImageBody) SetEncoding(v ImageEncoding)`

SetEncoding sets Encoding field to given value.


### GetEncapsulated

`func (o *CreateImageBody) GetEncapsulated() bool`

GetEncapsulated returns the Encapsulated field if non-nil, zero value otherwise.

### GetEncapsulatedOk

`func (o *CreateImageBody) GetEncapsulatedOk() (*bool, bool)`

GetEncapsulatedOk returns a tuple with the Encapsulated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncapsulated

`func (o *CreateImageBody) SetEncapsulated(v bool)`

SetEncapsulated sets Encapsulated field to given value.

### HasEncapsulated

`func (o *CreateImageBody) HasEncapsulated() bool`

HasEncapsulated returns a boolean if a field has been set.

### SetEncapsulatedNil

`func (o *CreateImageBody) SetEncapsulatedNil(b bool)`

 SetEncapsulatedNil sets the value for Encapsulated to be an explicit nil

### UnsetEncapsulated
`func (o *CreateImageBody) UnsetEncapsulated()`

UnsetEncapsulated ensures that no value is present for Encapsulated, not even an explicit nil
### GetName

`func (o *CreateImageBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateImageBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateImageBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateImageBody) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CreateImageBody) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CreateImageBody) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetFullPath

`func (o *CreateImageBody) GetFullPath() string`

GetFullPath returns the FullPath field if non-nil, zero value otherwise.

### GetFullPathOk

`func (o *CreateImageBody) GetFullPathOk() (*string, bool)`

GetFullPathOk returns a tuple with the FullPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullPath

`func (o *CreateImageBody) SetFullPath(v string)`

SetFullPath sets FullPath field to given value.

### HasFullPath

`func (o *CreateImageBody) HasFullPath() bool`

HasFullPath returns a boolean if a field has been set.

### SetFullPathNil

`func (o *CreateImageBody) SetFullPathNil(b bool)`

 SetFullPathNil sets the value for FullPath to be an explicit nil

### UnsetFullPath
`func (o *CreateImageBody) UnsetFullPath()`

UnsetFullPath ensures that no value is present for FullPath, not even an explicit nil
### GetProjectId

`func (o *CreateImageBody) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateImageBody) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateImageBody) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateImageBody) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### SetProjectIdNil

`func (o *CreateImageBody) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *CreateImageBody) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetInstanceId

`func (o *CreateImageBody) GetInstanceId() string`

GetInstanceId returns the InstanceId field if non-nil, zero value otherwise.

### GetInstanceIdOk

`func (o *CreateImageBody) GetInstanceIdOk() (*string, bool)`

GetInstanceIdOk returns a tuple with the InstanceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceId

`func (o *CreateImageBody) SetInstanceId(v string)`

SetInstanceId sets InstanceId field to given value.

### HasInstanceId

`func (o *CreateImageBody) HasInstanceId() bool`

HasInstanceId returns a boolean if a field has been set.

### SetInstanceIdNil

`func (o *CreateImageBody) SetInstanceIdNil(b bool)`

 SetInstanceIdNil sets the value for InstanceId to be an explicit nil

### UnsetInstanceId
`func (o *CreateImageBody) UnsetInstanceId()`

UnsetInstanceId ensures that no value is present for InstanceId, not even an explicit nil
### GetFile

`func (o *CreateImageBody) GetFile() *os.File`

GetFile returns the File field if non-nil, zero value otherwise.

### GetFileOk

`func (o *CreateImageBody) GetFileOk() (**os.File, bool)`

GetFileOk returns a tuple with the File field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFile

`func (o *CreateImageBody) SetFile(v *os.File)`

SetFile sets File field to given value.

### HasFile

`func (o *CreateImageBody) HasFile() bool`

HasFile returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


