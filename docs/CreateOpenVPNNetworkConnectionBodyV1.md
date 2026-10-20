# CreateOpenVPNNetworkConnectionBodyV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | User friendly name for network connection. | 
**Provider** | **string** | Type of network connection. | 
**Config** | [**OpenVPNConfigV1**](OpenVPNConfigV1.md) |  | 

## Methods

### NewCreateOpenVPNNetworkConnectionBodyV1

`func NewCreateOpenVPNNetworkConnectionBodyV1(name string, provider string, config OpenVPNConfigV1, ) *CreateOpenVPNNetworkConnectionBodyV1`

NewCreateOpenVPNNetworkConnectionBodyV1 instantiates a new CreateOpenVPNNetworkConnectionBodyV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOpenVPNNetworkConnectionBodyV1WithDefaults

`func NewCreateOpenVPNNetworkConnectionBodyV1WithDefaults() *CreateOpenVPNNetworkConnectionBodyV1`

NewCreateOpenVPNNetworkConnectionBodyV1WithDefaults instantiates a new CreateOpenVPNNetworkConnectionBodyV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateOpenVPNNetworkConnectionBodyV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOpenVPNNetworkConnectionBodyV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOpenVPNNetworkConnectionBodyV1) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *CreateOpenVPNNetworkConnectionBodyV1) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateOpenVPNNetworkConnectionBodyV1) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateOpenVPNNetworkConnectionBodyV1) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetConfig

`func (o *CreateOpenVPNNetworkConnectionBodyV1) GetConfig() OpenVPNConfigV1`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateOpenVPNNetworkConnectionBodyV1) GetConfigOk() (*OpenVPNConfigV1, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateOpenVPNNetworkConnectionBodyV1) SetConfig(v OpenVPNConfigV1)`

SetConfig sets Config field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


