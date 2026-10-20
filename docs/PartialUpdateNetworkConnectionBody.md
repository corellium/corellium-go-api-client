# PartialUpdateNetworkConnectionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | User friendly name for Network connection. | [optional] 
**Config** | Pointer to [**NetworkConnectionConfig**](NetworkConnectionConfig.md) |  | [optional] 
**Force** | Pointer to **bool** | Force the operation through constraint checks (e.g. stopping active instances). | [optional] [default to false]

## Methods

### NewPartialUpdateNetworkConnectionBody

`func NewPartialUpdateNetworkConnectionBody() *PartialUpdateNetworkConnectionBody`

NewPartialUpdateNetworkConnectionBody instantiates a new PartialUpdateNetworkConnectionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartialUpdateNetworkConnectionBodyWithDefaults

`func NewPartialUpdateNetworkConnectionBodyWithDefaults() *PartialUpdateNetworkConnectionBody`

NewPartialUpdateNetworkConnectionBodyWithDefaults instantiates a new PartialUpdateNetworkConnectionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PartialUpdateNetworkConnectionBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartialUpdateNetworkConnectionBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartialUpdateNetworkConnectionBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PartialUpdateNetworkConnectionBody) HasName() bool`

HasName returns a boolean if a field has been set.

### GetConfig

`func (o *PartialUpdateNetworkConnectionBody) GetConfig() NetworkConnectionConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *PartialUpdateNetworkConnectionBody) GetConfigOk() (*NetworkConnectionConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *PartialUpdateNetworkConnectionBody) SetConfig(v NetworkConnectionConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *PartialUpdateNetworkConnectionBody) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetForce

`func (o *PartialUpdateNetworkConnectionBody) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *PartialUpdateNetworkConnectionBody) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *PartialUpdateNetworkConnectionBody) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *PartialUpdateNetworkConnectionBody) HasForce() bool`

HasForce returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


