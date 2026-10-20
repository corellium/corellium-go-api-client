# CreateOpenVPNNetworkConnectionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | User friendly name for network connection. | 
**Provider** | **string** | Type of network connection. | 
**Config** | [**OpenVPNConfig**](OpenVPNConfig.md) |  | 

## Methods

### NewCreateOpenVPNNetworkConnectionBody

`func NewCreateOpenVPNNetworkConnectionBody(name string, provider string, config OpenVPNConfig, ) *CreateOpenVPNNetworkConnectionBody`

NewCreateOpenVPNNetworkConnectionBody instantiates a new CreateOpenVPNNetworkConnectionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOpenVPNNetworkConnectionBodyWithDefaults

`func NewCreateOpenVPNNetworkConnectionBodyWithDefaults() *CreateOpenVPNNetworkConnectionBody`

NewCreateOpenVPNNetworkConnectionBodyWithDefaults instantiates a new CreateOpenVPNNetworkConnectionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateOpenVPNNetworkConnectionBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOpenVPNNetworkConnectionBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOpenVPNNetworkConnectionBody) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *CreateOpenVPNNetworkConnectionBody) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateOpenVPNNetworkConnectionBody) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateOpenVPNNetworkConnectionBody) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetConfig

`func (o *CreateOpenVPNNetworkConnectionBody) GetConfig() OpenVPNConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateOpenVPNNetworkConnectionBody) GetConfigOk() (*OpenVPNConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateOpenVPNNetworkConnectionBody) SetConfig(v OpenVPNConfig)`

SetConfig sets Config field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


