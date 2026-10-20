# DeleteNetworkConnectionOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Force** | Pointer to **NullableBool** | Force the deletion through constraint checks (e.g. stopping active instances). Defaults to false. | [optional] 

## Methods

### NewDeleteNetworkConnectionOptions

`func NewDeleteNetworkConnectionOptions() *DeleteNetworkConnectionOptions`

NewDeleteNetworkConnectionOptions instantiates a new DeleteNetworkConnectionOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteNetworkConnectionOptionsWithDefaults

`func NewDeleteNetworkConnectionOptionsWithDefaults() *DeleteNetworkConnectionOptions`

NewDeleteNetworkConnectionOptionsWithDefaults instantiates a new DeleteNetworkConnectionOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForce

`func (o *DeleteNetworkConnectionOptions) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *DeleteNetworkConnectionOptions) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *DeleteNetworkConnectionOptions) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *DeleteNetworkConnectionOptions) HasForce() bool`

HasForce returns a boolean if a field has been set.

### SetForceNil

`func (o *DeleteNetworkConnectionOptions) SetForceNil(b bool)`

 SetForceNil sets the value for Force to be an explicit nil

### UnsetForce
`func (o *DeleteNetworkConnectionOptions) UnsetForce()`

UnsetForce ensures that no value is present for Force, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


