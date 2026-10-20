# CreateVLANNetworkConnectionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | User friendly name for network connection. | 
**Provider** | **string** | Type of network connection. | 
**Config** | [**VLANConfig**](VLANConfig.md) |  | 

## Methods

### NewCreateVLANNetworkConnectionBody

`func NewCreateVLANNetworkConnectionBody(name string, provider string, config VLANConfig, ) *CreateVLANNetworkConnectionBody`

NewCreateVLANNetworkConnectionBody instantiates a new CreateVLANNetworkConnectionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateVLANNetworkConnectionBodyWithDefaults

`func NewCreateVLANNetworkConnectionBodyWithDefaults() *CreateVLANNetworkConnectionBody`

NewCreateVLANNetworkConnectionBodyWithDefaults instantiates a new CreateVLANNetworkConnectionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateVLANNetworkConnectionBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateVLANNetworkConnectionBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateVLANNetworkConnectionBody) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *CreateVLANNetworkConnectionBody) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateVLANNetworkConnectionBody) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateVLANNetworkConnectionBody) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetConfig

`func (o *CreateVLANNetworkConnectionBody) GetConfig() VLANConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateVLANNetworkConnectionBody) GetConfigOk() (*VLANConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateVLANNetworkConnectionBody) SetConfig(v VLANConfig)`

SetConfig sets Config field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


