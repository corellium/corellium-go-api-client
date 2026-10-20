# ApiNotFoundErrorV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Error text | 
**ErrorID** | **string** | Error ID | 
**Name** | Pointer to **NullableString** | Name of the object requested | [optional] 
**Params** | Pointer to **map[string]interface{}** | params provided by user | [optional] 

## Methods

### NewApiNotFoundErrorV1

`func NewApiNotFoundErrorV1(error_ string, errorID string, ) *ApiNotFoundErrorV1`

NewApiNotFoundErrorV1 instantiates a new ApiNotFoundErrorV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiNotFoundErrorV1WithDefaults

`func NewApiNotFoundErrorV1WithDefaults() *ApiNotFoundErrorV1`

NewApiNotFoundErrorV1WithDefaults instantiates a new ApiNotFoundErrorV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ApiNotFoundErrorV1) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ApiNotFoundErrorV1) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ApiNotFoundErrorV1) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *ApiNotFoundErrorV1) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *ApiNotFoundErrorV1) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *ApiNotFoundErrorV1) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetName

`func (o *ApiNotFoundErrorV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApiNotFoundErrorV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApiNotFoundErrorV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ApiNotFoundErrorV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ApiNotFoundErrorV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ApiNotFoundErrorV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetParams

`func (o *ApiNotFoundErrorV1) GetParams() map[string]interface{}`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *ApiNotFoundErrorV1) GetParamsOk() (*map[string]interface{}, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *ApiNotFoundErrorV1) SetParams(v map[string]interface{})`

SetParams sets Params field to given value.

### HasParams

`func (o *ApiNotFoundErrorV1) HasParams() bool`

HasParams returns a boolean if a field has been set.

### SetParamsNil

`func (o *ApiNotFoundErrorV1) SetParamsNil(b bool)`

 SetParamsNil sets the value for Params to be an explicit nil

### UnsetParams
`func (o *ApiNotFoundErrorV1) UnsetParams()`

UnsetParams ensures that no value is present for Params, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


