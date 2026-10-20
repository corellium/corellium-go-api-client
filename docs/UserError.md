# UserError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Human-readable explanation of what was wrong with the request. Show it to the user or log it; do not parse it, because the wording can change. | 
**ErrorID** | **string** | Always &#x60;UserError&#x60;: the request itself was invalid. Fix the request before retrying; sending it again unchanged fails the same way. | 
**Field** | Pointer to **string** | Name of the request field that was rejected, when the error is about one field. | [optional] 
**Validator** | Pointer to **string** | Validator that rejected the field. | [optional] 
**ProjectIds** | Pointer to **[]string** | Projects still using this resource, when the error is a usage conflict. | [optional] 
**MissingFwAssets** | Pointer to **[]string** | Firmware asset URLs required by the target firmware but absent from the domain, when field is &#39;firmware_asset&#39;. | [optional] 

## Methods

### NewUserError

`func NewUserError(error_ string, errorID string, ) *UserError`

NewUserError instantiates a new UserError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserErrorWithDefaults

`func NewUserErrorWithDefaults() *UserError`

NewUserErrorWithDefaults instantiates a new UserError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *UserError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UserError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UserError) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *UserError) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *UserError) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *UserError) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetField

`func (o *UserError) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *UserError) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *UserError) SetField(v string)`

SetField sets Field field to given value.

### HasField

`func (o *UserError) HasField() bool`

HasField returns a boolean if a field has been set.

### GetValidator

`func (o *UserError) GetValidator() string`

GetValidator returns the Validator field if non-nil, zero value otherwise.

### GetValidatorOk

`func (o *UserError) GetValidatorOk() (*string, bool)`

GetValidatorOk returns a tuple with the Validator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidator

`func (o *UserError) SetValidator(v string)`

SetValidator sets Validator field to given value.

### HasValidator

`func (o *UserError) HasValidator() bool`

HasValidator returns a boolean if a field has been set.

### GetProjectIds

`func (o *UserError) GetProjectIds() []string`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *UserError) GetProjectIdsOk() (*[]string, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *UserError) SetProjectIds(v []string)`

SetProjectIds sets ProjectIds field to given value.

### HasProjectIds

`func (o *UserError) HasProjectIds() bool`

HasProjectIds returns a boolean if a field has been set.

### GetMissingFwAssets

`func (o *UserError) GetMissingFwAssets() []string`

GetMissingFwAssets returns the MissingFwAssets field if non-nil, zero value otherwise.

### GetMissingFwAssetsOk

`func (o *UserError) GetMissingFwAssetsOk() (*[]string, bool)`

GetMissingFwAssetsOk returns a tuple with the MissingFwAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMissingFwAssets

`func (o *UserError) SetMissingFwAssets(v []string)`

SetMissingFwAssets sets MissingFwAssets field to given value.

### HasMissingFwAssets

`func (o *UserError) HasMissingFwAssets() bool`

HasMissingFwAssets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


