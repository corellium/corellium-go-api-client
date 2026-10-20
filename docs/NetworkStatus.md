# NetworkStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Network provider type (e.g. \&quot;openvpn\&quot;). | [optional] 
**Name** | Pointer to **string** | User-defined network connection name. | [optional] 
**State** | **string** | Current egress network connection state. | 
**Details** | Pointer to **map[string]interface{}** | Additional state information, such as the last error. | [optional] 

## Methods

### NewNetworkStatus

`func NewNetworkStatus(state string, ) *NetworkStatus`

NewNetworkStatus instantiates a new NetworkStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkStatusWithDefaults

`func NewNetworkStatusWithDefaults() *NetworkStatus`

NewNetworkStatusWithDefaults instantiates a new NetworkStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *NetworkStatus) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *NetworkStatus) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *NetworkStatus) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *NetworkStatus) HasType() bool`

HasType returns a boolean if a field has been set.

### GetName

`func (o *NetworkStatus) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *NetworkStatus) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *NetworkStatus) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *NetworkStatus) HasName() bool`

HasName returns a boolean if a field has been set.

### GetState

`func (o *NetworkStatus) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *NetworkStatus) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *NetworkStatus) SetState(v string)`

SetState sets State field to given value.


### GetDetails

`func (o *NetworkStatus) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *NetworkStatus) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *NetworkStatus) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *NetworkStatus) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


