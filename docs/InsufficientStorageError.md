# InsufficientStorageError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Error text. | 
**ErrorID** | **string** | Error ID. | 
**Total** | **float32** | Total storage capacity in bytes. | 
**Available** | **float32** | Available storage in bytes. | 
**Required** | **float32** | Storage required for the upload in bytes. | 

## Methods

### NewInsufficientStorageError

`func NewInsufficientStorageError(error_ string, errorID string, total float32, available float32, required float32, ) *InsufficientStorageError`

NewInsufficientStorageError instantiates a new InsufficientStorageError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInsufficientStorageErrorWithDefaults

`func NewInsufficientStorageErrorWithDefaults() *InsufficientStorageError`

NewInsufficientStorageErrorWithDefaults instantiates a new InsufficientStorageError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *InsufficientStorageError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *InsufficientStorageError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *InsufficientStorageError) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *InsufficientStorageError) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *InsufficientStorageError) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *InsufficientStorageError) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetTotal

`func (o *InsufficientStorageError) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *InsufficientStorageError) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *InsufficientStorageError) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetAvailable

`func (o *InsufficientStorageError) GetAvailable() float32`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *InsufficientStorageError) GetAvailableOk() (*float32, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *InsufficientStorageError) SetAvailable(v float32)`

SetAvailable sets Available field to given value.


### GetRequired

`func (o *InsufficientStorageError) GetRequired() float32`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *InsufficientStorageError) GetRequiredOk() (*float32, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *InsufficientStorageError) SetRequired(v float32)`

SetRequired sets Required field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


