# OpenVPNNetworkConnectionProjectsValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**State** | **string** | State of the project network connection. | 
**Details** | Pointer to **map[string]interface{}** | Additional parameters for the network state. | [optional] 

## Methods

### NewOpenVPNNetworkConnectionProjectsValue

`func NewOpenVPNNetworkConnectionProjectsValue(state string, ) *OpenVPNNetworkConnectionProjectsValue`

NewOpenVPNNetworkConnectionProjectsValue instantiates a new OpenVPNNetworkConnectionProjectsValue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenVPNNetworkConnectionProjectsValueWithDefaults

`func NewOpenVPNNetworkConnectionProjectsValueWithDefaults() *OpenVPNNetworkConnectionProjectsValue`

NewOpenVPNNetworkConnectionProjectsValueWithDefaults instantiates a new OpenVPNNetworkConnectionProjectsValue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetState

`func (o *OpenVPNNetworkConnectionProjectsValue) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *OpenVPNNetworkConnectionProjectsValue) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *OpenVPNNetworkConnectionProjectsValue) SetState(v string)`

SetState sets State field to given value.


### GetDetails

`func (o *OpenVPNNetworkConnectionProjectsValue) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *OpenVPNNetworkConnectionProjectsValue) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *OpenVPNNetworkConnectionProjectsValue) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *OpenVPNNetworkConnectionProjectsValue) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


