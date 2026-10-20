# UserErrorsV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Error text | 
**ErrorID** | **string** | Error ID | 
**Errors** | [**[]UserErrorItem**](UserErrorItem.md) | Individual field errors | 

## Methods

### NewUserErrorsV1

`func NewUserErrorsV1(error_ string, errorID string, errors []UserErrorItem, ) *UserErrorsV1`

NewUserErrorsV1 instantiates a new UserErrorsV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserErrorsV1WithDefaults

`func NewUserErrorsV1WithDefaults() *UserErrorsV1`

NewUserErrorsV1WithDefaults instantiates a new UserErrorsV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *UserErrorsV1) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UserErrorsV1) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UserErrorsV1) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *UserErrorsV1) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *UserErrorsV1) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *UserErrorsV1) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetErrors

`func (o *UserErrorsV1) GetErrors() []UserErrorItem`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *UserErrorsV1) GetErrorsOk() (*[]UserErrorItem, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *UserErrorsV1) SetErrors(v []UserErrorItem)`

SetErrors sets Errors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


