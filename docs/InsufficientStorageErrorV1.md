# InsufficientStorageErrorV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ErrorID** | Pointer to **NullableString** | Error identifier | [optional] 
**Error** | Pointer to **NullableString** | Error message | [optional] 
**Total** | Pointer to **NullableFloat32** | Total image pool capacity in bytes | [optional] 
**Available** | Pointer to **NullableFloat32** | Currently available image pool space in bytes | [optional] 
**Required** | **float32** | Required space for the upload in bytes (from Content-Length) | 

## Methods

### NewInsufficientStorageErrorV1

`func NewInsufficientStorageErrorV1(required float32, ) *InsufficientStorageErrorV1`

NewInsufficientStorageErrorV1 instantiates a new InsufficientStorageErrorV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInsufficientStorageErrorV1WithDefaults

`func NewInsufficientStorageErrorV1WithDefaults() *InsufficientStorageErrorV1`

NewInsufficientStorageErrorV1WithDefaults instantiates a new InsufficientStorageErrorV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrorID

`func (o *InsufficientStorageErrorV1) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *InsufficientStorageErrorV1) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *InsufficientStorageErrorV1) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.

### HasErrorID

`func (o *InsufficientStorageErrorV1) HasErrorID() bool`

HasErrorID returns a boolean if a field has been set.

### SetErrorIDNil

`func (o *InsufficientStorageErrorV1) SetErrorIDNil(b bool)`

 SetErrorIDNil sets the value for ErrorID to be an explicit nil

### UnsetErrorID
`func (o *InsufficientStorageErrorV1) UnsetErrorID()`

UnsetErrorID ensures that no value is present for ErrorID, not even an explicit nil
### GetError

`func (o *InsufficientStorageErrorV1) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *InsufficientStorageErrorV1) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *InsufficientStorageErrorV1) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *InsufficientStorageErrorV1) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *InsufficientStorageErrorV1) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *InsufficientStorageErrorV1) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetTotal

`func (o *InsufficientStorageErrorV1) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *InsufficientStorageErrorV1) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *InsufficientStorageErrorV1) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *InsufficientStorageErrorV1) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### SetTotalNil

`func (o *InsufficientStorageErrorV1) SetTotalNil(b bool)`

 SetTotalNil sets the value for Total to be an explicit nil

### UnsetTotal
`func (o *InsufficientStorageErrorV1) UnsetTotal()`

UnsetTotal ensures that no value is present for Total, not even an explicit nil
### GetAvailable

`func (o *InsufficientStorageErrorV1) GetAvailable() float32`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *InsufficientStorageErrorV1) GetAvailableOk() (*float32, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *InsufficientStorageErrorV1) SetAvailable(v float32)`

SetAvailable sets Available field to given value.

### HasAvailable

`func (o *InsufficientStorageErrorV1) HasAvailable() bool`

HasAvailable returns a boolean if a field has been set.

### SetAvailableNil

`func (o *InsufficientStorageErrorV1) SetAvailableNil(b bool)`

 SetAvailableNil sets the value for Available to be an explicit nil

### UnsetAvailable
`func (o *InsufficientStorageErrorV1) UnsetAvailable()`

UnsetAvailable ensures that no value is present for Available, not even an explicit nil
### GetRequired

`func (o *InsufficientStorageErrorV1) GetRequired() float32`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *InsufficientStorageErrorV1) GetRequiredOk() (*float32, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *InsufficientStorageErrorV1) SetRequired(v float32)`

SetRequired sets Required field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


