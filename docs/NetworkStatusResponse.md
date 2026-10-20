# NetworkStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **NullableString** | Network Provider. Omitted when no egress network is configured | [optional] 
**Name** | Pointer to **NullableString** | User defined name. Omitted when no egress network is configured | [optional] 
**State** | **string** | Current state of the network connection | 
**Params** | Pointer to **map[string]interface{}** | Additional state information. Omitted when no egress network is configured | [optional] 

## Methods

### NewNetworkStatusResponse

`func NewNetworkStatusResponse(state string, ) *NetworkStatusResponse`

NewNetworkStatusResponse instantiates a new NetworkStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkStatusResponseWithDefaults

`func NewNetworkStatusResponseWithDefaults() *NetworkStatusResponse`

NewNetworkStatusResponseWithDefaults instantiates a new NetworkStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *NetworkStatusResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *NetworkStatusResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *NetworkStatusResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *NetworkStatusResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *NetworkStatusResponse) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *NetworkStatusResponse) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetName

`func (o *NetworkStatusResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *NetworkStatusResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *NetworkStatusResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *NetworkStatusResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *NetworkStatusResponse) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *NetworkStatusResponse) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetState

`func (o *NetworkStatusResponse) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *NetworkStatusResponse) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *NetworkStatusResponse) SetState(v string)`

SetState sets State field to given value.


### GetParams

`func (o *NetworkStatusResponse) GetParams() map[string]interface{}`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *NetworkStatusResponse) GetParamsOk() (*map[string]interface{}, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *NetworkStatusResponse) SetParams(v map[string]interface{})`

SetParams sets Params field to given value.

### HasParams

`func (o *NetworkStatusResponse) HasParams() bool`

HasParams returns a boolean if a field has been set.

### SetParamsNil

`func (o *NetworkStatusResponse) SetParamsNil(b bool)`

 SetParamsNil sets the value for Params to be an explicit nil

### UnsetParams
`func (o *NetworkStatusResponse) UnsetParams()`

UnsetParams ensures that no value is present for Params, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


