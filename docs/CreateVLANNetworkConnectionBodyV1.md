# CreateVLANNetworkConnectionBodyV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | User friendly name for network connection. | 
**Provider** | **string** | Type of network connection. | 
**Config** | [**VLANConfigV1**](VLANConfigV1.md) |  | 

## Methods

### NewCreateVLANNetworkConnectionBodyV1

`func NewCreateVLANNetworkConnectionBodyV1(name string, provider string, config VLANConfigV1, ) *CreateVLANNetworkConnectionBodyV1`

NewCreateVLANNetworkConnectionBodyV1 instantiates a new CreateVLANNetworkConnectionBodyV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateVLANNetworkConnectionBodyV1WithDefaults

`func NewCreateVLANNetworkConnectionBodyV1WithDefaults() *CreateVLANNetworkConnectionBodyV1`

NewCreateVLANNetworkConnectionBodyV1WithDefaults instantiates a new CreateVLANNetworkConnectionBodyV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateVLANNetworkConnectionBodyV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateVLANNetworkConnectionBodyV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateVLANNetworkConnectionBodyV1) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *CreateVLANNetworkConnectionBodyV1) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateVLANNetworkConnectionBodyV1) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateVLANNetworkConnectionBodyV1) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetConfig

`func (o *CreateVLANNetworkConnectionBodyV1) GetConfig() VLANConfigV1`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateVLANNetworkConnectionBodyV1) GetConfigOk() (*VLANConfigV1, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateVLANNetworkConnectionBodyV1) SetConfig(v VLANConfigV1)`

SetConfig sets Config field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


