# UserErrorResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Summary of the problem. The individual problems are listed in &#x60;errors&#x60;. | 
**ErrorID** | **string** | Always &#x60;UserErrors&#x60;: more than one field in the request was invalid. | 
**Field** | Pointer to **string** | Name of the request field that was rejected, when the error is about one field. | [optional] 
**Validator** | Pointer to **string** | Validator that rejected the field. | [optional] 
**ProjectIds** | Pointer to **[]string** | Projects still using this resource, when the error is a usage conflict. | [optional] 
**MissingFwAssets** | Pointer to **[]string** | Firmware asset URLs required by the target firmware but absent from the domain, when field is &#39;firmware_asset&#39;. | [optional] 
**Errors** | [**[]UserError**](UserError.md) | One entry per rejected field. Fix every one before retrying. | 

## Methods

### NewUserErrorResponse

`func NewUserErrorResponse(error_ string, errorID string, errors []UserError, ) *UserErrorResponse`

NewUserErrorResponse instantiates a new UserErrorResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserErrorResponseWithDefaults

`func NewUserErrorResponseWithDefaults() *UserErrorResponse`

NewUserErrorResponseWithDefaults instantiates a new UserErrorResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *UserErrorResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UserErrorResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UserErrorResponse) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *UserErrorResponse) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *UserErrorResponse) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *UserErrorResponse) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetField

`func (o *UserErrorResponse) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *UserErrorResponse) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *UserErrorResponse) SetField(v string)`

SetField sets Field field to given value.

### HasField

`func (o *UserErrorResponse) HasField() bool`

HasField returns a boolean if a field has been set.

### GetValidator

`func (o *UserErrorResponse) GetValidator() string`

GetValidator returns the Validator field if non-nil, zero value otherwise.

### GetValidatorOk

`func (o *UserErrorResponse) GetValidatorOk() (*string, bool)`

GetValidatorOk returns a tuple with the Validator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidator

`func (o *UserErrorResponse) SetValidator(v string)`

SetValidator sets Validator field to given value.

### HasValidator

`func (o *UserErrorResponse) HasValidator() bool`

HasValidator returns a boolean if a field has been set.

### GetProjectIds

`func (o *UserErrorResponse) GetProjectIds() []string`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *UserErrorResponse) GetProjectIdsOk() (*[]string, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *UserErrorResponse) SetProjectIds(v []string)`

SetProjectIds sets ProjectIds field to given value.

### HasProjectIds

`func (o *UserErrorResponse) HasProjectIds() bool`

HasProjectIds returns a boolean if a field has been set.

### GetMissingFwAssets

`func (o *UserErrorResponse) GetMissingFwAssets() []string`

GetMissingFwAssets returns the MissingFwAssets field if non-nil, zero value otherwise.

### GetMissingFwAssetsOk

`func (o *UserErrorResponse) GetMissingFwAssetsOk() (*[]string, bool)`

GetMissingFwAssetsOk returns a tuple with the MissingFwAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMissingFwAssets

`func (o *UserErrorResponse) SetMissingFwAssets(v []string)`

SetMissingFwAssets sets MissingFwAssets field to given value.

### HasMissingFwAssets

`func (o *UserErrorResponse) HasMissingFwAssets() bool`

HasMissingFwAssets returns a boolean if a field has been set.

### GetErrors

`func (o *UserErrorResponse) GetErrors() []UserError`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *UserErrorResponse) GetErrorsOk() (*[]UserError, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *UserErrorResponse) SetErrors(v []UserError)`

SetErrors sets Errors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


