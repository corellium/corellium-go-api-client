# UpdateNetworkConnectionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | User friendly name for Network connection. | 
**Config** | Pointer to [**NetworkConnectionConfig**](NetworkConnectionConfig.md) |  | [optional] 
**Force** | Pointer to **bool** | Force the operation through constraint checks (e.g. stopping active instances). | [optional] [default to false]

## Methods

### NewUpdateNetworkConnectionBody

`func NewUpdateNetworkConnectionBody(name string, ) *UpdateNetworkConnectionBody`

NewUpdateNetworkConnectionBody instantiates a new UpdateNetworkConnectionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateNetworkConnectionBodyWithDefaults

`func NewUpdateNetworkConnectionBodyWithDefaults() *UpdateNetworkConnectionBody`

NewUpdateNetworkConnectionBodyWithDefaults instantiates a new UpdateNetworkConnectionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateNetworkConnectionBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateNetworkConnectionBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateNetworkConnectionBody) SetName(v string)`

SetName sets Name field to given value.


### GetConfig

`func (o *UpdateNetworkConnectionBody) GetConfig() NetworkConnectionConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *UpdateNetworkConnectionBody) GetConfigOk() (*NetworkConnectionConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *UpdateNetworkConnectionBody) SetConfig(v NetworkConnectionConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *UpdateNetworkConnectionBody) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetForce

`func (o *UpdateNetworkConnectionBody) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *UpdateNetworkConnectionBody) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *UpdateNetworkConnectionBody) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *UpdateNetworkConnectionBody) HasForce() bool`

HasForce returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


