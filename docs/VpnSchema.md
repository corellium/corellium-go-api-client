# VpnSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | VPN type. | 
**ProjectId** | **string** | Project identifier. | 
**State** | **string** | VPN state. | 
**Details** | **map[string]interface{}** | VPN details. | 

## Methods

### NewVpnSchema

`func NewVpnSchema(type_ string, projectId string, state string, details map[string]interface{}, ) *VpnSchema`

NewVpnSchema instantiates a new VpnSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVpnSchemaWithDefaults

`func NewVpnSchemaWithDefaults() *VpnSchema`

NewVpnSchemaWithDefaults instantiates a new VpnSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *VpnSchema) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VpnSchema) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VpnSchema) SetType(v string)`

SetType sets Type field to given value.


### GetProjectId

`func (o *VpnSchema) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *VpnSchema) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *VpnSchema) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetState

`func (o *VpnSchema) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *VpnSchema) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *VpnSchema) SetState(v string)`

SetState sets State field to given value.


### GetDetails

`func (o *VpnSchema) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *VpnSchema) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *VpnSchema) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


