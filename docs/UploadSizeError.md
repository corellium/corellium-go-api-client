# UploadSizeError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Error text. | 
**ErrorID** | **string** | Error ID. | 
**Field** | Pointer to **string** | Limit that was exceeded, e.g. &#39;storageQuota&#39; or the image type. | [optional] 

## Methods

### NewUploadSizeError

`func NewUploadSizeError(error_ string, errorID string, ) *UploadSizeError`

NewUploadSizeError instantiates a new UploadSizeError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUploadSizeErrorWithDefaults

`func NewUploadSizeErrorWithDefaults() *UploadSizeError`

NewUploadSizeErrorWithDefaults instantiates a new UploadSizeError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *UploadSizeError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UploadSizeError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UploadSizeError) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *UploadSizeError) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *UploadSizeError) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *UploadSizeError) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetField

`func (o *UploadSizeError) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *UploadSizeError) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *UploadSizeError) SetField(v string)`

SetField sets Field field to given value.

### HasField

`func (o *UploadSizeError) HasField() bool`

HasField returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


