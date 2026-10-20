# NetworkSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PhysicalInterfaces** | **[]string** | Physical interfaces. | 
**Vpns** | Pointer to [**[]VpnSchema**](VpnSchema.md) | Active VPN connections. | [optional] 

## Methods

### NewNetworkSchema

`func NewNetworkSchema(physicalInterfaces []string, ) *NetworkSchema`

NewNetworkSchema instantiates a new NetworkSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkSchemaWithDefaults

`func NewNetworkSchemaWithDefaults() *NetworkSchema`

NewNetworkSchemaWithDefaults instantiates a new NetworkSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhysicalInterfaces

`func (o *NetworkSchema) GetPhysicalInterfaces() []string`

GetPhysicalInterfaces returns the PhysicalInterfaces field if non-nil, zero value otherwise.

### GetPhysicalInterfacesOk

`func (o *NetworkSchema) GetPhysicalInterfacesOk() (*[]string, bool)`

GetPhysicalInterfacesOk returns a tuple with the PhysicalInterfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhysicalInterfaces

`func (o *NetworkSchema) SetPhysicalInterfaces(v []string)`

SetPhysicalInterfaces sets PhysicalInterfaces field to given value.


### GetVpns

`func (o *NetworkSchema) GetVpns() []VpnSchema`

GetVpns returns the Vpns field if non-nil, zero value otherwise.

### GetVpnsOk

`func (o *NetworkSchema) GetVpnsOk() (*[]VpnSchema, bool)`

GetVpnsOk returns a tuple with the Vpns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVpns

`func (o *NetworkSchema) SetVpns(v []VpnSchema)`

SetVpns sets Vpns field to given value.

### HasVpns

`func (o *NetworkSchema) HasVpns() bool`

HasVpns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


