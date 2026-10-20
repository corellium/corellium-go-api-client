# UserErrorV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Error text | 
**ErrorID** | **string** | Error ID | 
**Field** | Pointer to **NullableString** | Field associated with error | [optional] 
**Validator** | Pointer to **NullableString** | Validator that rejected the field | [optional] 
**ProjectIds** | Pointer to **[]string** | Projects still using this resource, when the error is a usage conflict. | [optional] 
**Errors** | [**[]UserErrorItem**](UserErrorItem.md) | Individual field errors | 

## Methods

### NewUserErrorV1

`func NewUserErrorV1(error_ string, errorID string, errors []UserErrorItem, ) *UserErrorV1`

NewUserErrorV1 instantiates a new UserErrorV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserErrorV1WithDefaults

`func NewUserErrorV1WithDefaults() *UserErrorV1`

NewUserErrorV1WithDefaults instantiates a new UserErrorV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *UserErrorV1) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UserErrorV1) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UserErrorV1) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *UserErrorV1) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *UserErrorV1) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *UserErrorV1) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetField

`func (o *UserErrorV1) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *UserErrorV1) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *UserErrorV1) SetField(v string)`

SetField sets Field field to given value.

### HasField

`func (o *UserErrorV1) HasField() bool`

HasField returns a boolean if a field has been set.

### SetFieldNil

`func (o *UserErrorV1) SetFieldNil(b bool)`

 SetFieldNil sets the value for Field to be an explicit nil

### UnsetField
`func (o *UserErrorV1) UnsetField()`

UnsetField ensures that no value is present for Field, not even an explicit nil
### GetValidator

`func (o *UserErrorV1) GetValidator() string`

GetValidator returns the Validator field if non-nil, zero value otherwise.

### GetValidatorOk

`func (o *UserErrorV1) GetValidatorOk() (*string, bool)`

GetValidatorOk returns a tuple with the Validator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidator

`func (o *UserErrorV1) SetValidator(v string)`

SetValidator sets Validator field to given value.

### HasValidator

`func (o *UserErrorV1) HasValidator() bool`

HasValidator returns a boolean if a field has been set.

### SetValidatorNil

`func (o *UserErrorV1) SetValidatorNil(b bool)`

 SetValidatorNil sets the value for Validator to be an explicit nil

### UnsetValidator
`func (o *UserErrorV1) UnsetValidator()`

UnsetValidator ensures that no value is present for Validator, not even an explicit nil
### GetProjectIds

`func (o *UserErrorV1) GetProjectIds() []string`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *UserErrorV1) GetProjectIdsOk() (*[]string, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *UserErrorV1) SetProjectIds(v []string)`

SetProjectIds sets ProjectIds field to given value.

### HasProjectIds

`func (o *UserErrorV1) HasProjectIds() bool`

HasProjectIds returns a boolean if a field has been set.

### SetProjectIdsNil

`func (o *UserErrorV1) SetProjectIdsNil(b bool)`

 SetProjectIdsNil sets the value for ProjectIds to be an explicit nil

### UnsetProjectIds
`func (o *UserErrorV1) UnsetProjectIds()`

UnsetProjectIds ensures that no value is present for ProjectIds, not even an explicit nil
### GetErrors

`func (o *UserErrorV1) GetErrors() []UserErrorItem`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *UserErrorV1) GetErrorsOk() (*[]UserErrorItem, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *UserErrorV1) SetErrors(v []UserErrorItem)`

SetErrors sets Errors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


