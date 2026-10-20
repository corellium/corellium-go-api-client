# UserErrors

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Summary of the problem. The individual problems are listed in &#x60;errors&#x60;. | 
**ErrorID** | **string** | Always &#x60;UserErrors&#x60;: more than one field in the request was invalid. | 
**Errors** | [**[]UserError**](UserError.md) | One entry per rejected field. Fix every one before retrying. | 

## Methods

### NewUserErrors

`func NewUserErrors(error_ string, errorID string, errors []UserError, ) *UserErrors`

NewUserErrors instantiates a new UserErrors object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserErrorsWithDefaults

`func NewUserErrorsWithDefaults() *UserErrors`

NewUserErrorsWithDefaults instantiates a new UserErrors object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *UserErrors) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UserErrors) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UserErrors) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *UserErrors) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *UserErrors) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *UserErrors) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetErrors

`func (o *UserErrors) GetErrors() []UserError`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *UserErrors) GetErrorsOk() (*[]UserError, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *UserErrors) SetErrors(v []UserError)`

SetErrors sets Errors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


