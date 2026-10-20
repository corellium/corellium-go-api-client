# OpenVPNConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Username** | Pointer to **string** | Username for OpenVPN connection. | [optional] 
**Password** | Pointer to **string** | Password for OpenVPN connection. | [optional] 
**Config** | **string** | OpenVPN connection configuration. | 

## Methods

### NewOpenVPNConfig

`func NewOpenVPNConfig(config string, ) *OpenVPNConfig`

NewOpenVPNConfig instantiates a new OpenVPNConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenVPNConfigWithDefaults

`func NewOpenVPNConfigWithDefaults() *OpenVPNConfig`

NewOpenVPNConfigWithDefaults instantiates a new OpenVPNConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsername

`func (o *OpenVPNConfig) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *OpenVPNConfig) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *OpenVPNConfig) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *OpenVPNConfig) HasUsername() bool`

HasUsername returns a boolean if a field has been set.

### GetPassword

`func (o *OpenVPNConfig) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *OpenVPNConfig) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *OpenVPNConfig) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *OpenVPNConfig) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetConfig

`func (o *OpenVPNConfig) GetConfig() string`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *OpenVPNConfig) GetConfigOk() (*string, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *OpenVPNConfig) SetConfig(v string)`

SetConfig sets Config field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


