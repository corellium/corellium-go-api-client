# InvalidTOTPError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Error text. | 
**ErrorID** | **string** | Error ID. | 

## Methods

### NewInvalidTOTPError

`func NewInvalidTOTPError(error_ string, errorID string, ) *InvalidTOTPError`

NewInvalidTOTPError instantiates a new InvalidTOTPError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvalidTOTPErrorWithDefaults

`func NewInvalidTOTPErrorWithDefaults() *InvalidTOTPError`

NewInvalidTOTPErrorWithDefaults instantiates a new InvalidTOTPError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *InvalidTOTPError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *InvalidTOTPError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *InvalidTOTPError) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *InvalidTOTPError) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *InvalidTOTPError) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *InvalidTOTPError) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


