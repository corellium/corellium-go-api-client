# UserErrorItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Error text | 
**ErrorID** | **string** | Error ID | 
**Field** | Pointer to **NullableString** | Field associated with error | [optional] 
**Validator** | Pointer to **NullableString** | Validator that rejected the field | [optional] 
**ProjectIds** | Pointer to **[]string** | Projects still using this resource, when the error is a usage conflict. | [optional] 

## Methods

### NewUserErrorItem

`func NewUserErrorItem(error_ string, errorID string, ) *UserErrorItem`

NewUserErrorItem instantiates a new UserErrorItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserErrorItemWithDefaults

`func NewUserErrorItemWithDefaults() *UserErrorItem`

NewUserErrorItemWithDefaults instantiates a new UserErrorItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *UserErrorItem) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UserErrorItem) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UserErrorItem) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *UserErrorItem) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *UserErrorItem) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *UserErrorItem) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetField

`func (o *UserErrorItem) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *UserErrorItem) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *UserErrorItem) SetField(v string)`

SetField sets Field field to given value.

### HasField

`func (o *UserErrorItem) HasField() bool`

HasField returns a boolean if a field has been set.

### SetFieldNil

`func (o *UserErrorItem) SetFieldNil(b bool)`

 SetFieldNil sets the value for Field to be an explicit nil

### UnsetField
`func (o *UserErrorItem) UnsetField()`

UnsetField ensures that no value is present for Field, not even an explicit nil
### GetValidator

`func (o *UserErrorItem) GetValidator() string`

GetValidator returns the Validator field if non-nil, zero value otherwise.

### GetValidatorOk

`func (o *UserErrorItem) GetValidatorOk() (*string, bool)`

GetValidatorOk returns a tuple with the Validator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidator

`func (o *UserErrorItem) SetValidator(v string)`

SetValidator sets Validator field to given value.

### HasValidator

`func (o *UserErrorItem) HasValidator() bool`

HasValidator returns a boolean if a field has been set.

### SetValidatorNil

`func (o *UserErrorItem) SetValidatorNil(b bool)`

 SetValidatorNil sets the value for Validator to be an explicit nil

### UnsetValidator
`func (o *UserErrorItem) UnsetValidator()`

UnsetValidator ensures that no value is present for Validator, not even an explicit nil
### GetProjectIds

`func (o *UserErrorItem) GetProjectIds() []string`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *UserErrorItem) GetProjectIdsOk() (*[]string, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *UserErrorItem) SetProjectIds(v []string)`

SetProjectIds sets ProjectIds field to given value.

### HasProjectIds

`func (o *UserErrorItem) HasProjectIds() bool`

HasProjectIds returns a boolean if a field has been set.

### SetProjectIdsNil

`func (o *UserErrorItem) SetProjectIdsNil(b bool)`

 SetProjectIdsNil sets the value for ProjectIds to be an explicit nil

### UnsetProjectIds
`func (o *UserErrorItem) UnsetProjectIds()`

UnsetProjectIds ensures that no value is present for ProjectIds, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


