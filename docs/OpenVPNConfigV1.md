# OpenVPNConfigV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Username** | Pointer to **string** | Username for OpenVPN connection. | [optional] 
**Password** | Pointer to **string** | Password for OpenVPN connection. | [optional] 
**Config** | **string** | OpenVPN connection configuration. | 

## Methods

### NewOpenVPNConfigV1

`func NewOpenVPNConfigV1(config string, ) *OpenVPNConfigV1`

NewOpenVPNConfigV1 instantiates a new OpenVPNConfigV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenVPNConfigV1WithDefaults

`func NewOpenVPNConfigV1WithDefaults() *OpenVPNConfigV1`

NewOpenVPNConfigV1WithDefaults instantiates a new OpenVPNConfigV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsername

`func (o *OpenVPNConfigV1) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *OpenVPNConfigV1) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *OpenVPNConfigV1) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *OpenVPNConfigV1) HasUsername() bool`

HasUsername returns a boolean if a field has been set.

### GetPassword

`func (o *OpenVPNConfigV1) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *OpenVPNConfigV1) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *OpenVPNConfigV1) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *OpenVPNConfigV1) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetConfig

`func (o *OpenVPNConfigV1) GetConfig() string`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *OpenVPNConfigV1) GetConfigOk() (*string, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *OpenVPNConfigV1) SetConfig(v string)`

SetConfig sets Config field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


