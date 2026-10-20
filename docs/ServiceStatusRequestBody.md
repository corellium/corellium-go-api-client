# ServiceStatusRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Healthy** | **bool** | Whether the service is healthy. | 
**ServiceName** | **string** | Service name. | 
**Address** | **string** | Service address (IP:Port). | 
**Hostname** | **string** | Service hostname. | 
**NodeId** | **string** | Node identifier. | 
**SysInfo** | Pointer to [**SysInfoSchema**](SysInfoSchema.md) |  | [optional] 
**Layout** | Pointer to [**LayoutSchema**](LayoutSchema.md) |  | [optional] 
**Vms** | Pointer to [**[]ServiceStatusRequestBodyVmsInner**](ServiceStatusRequestBodyVmsInner.md) | VM list reported by this node. | [optional] 
**PoolUsage** | Pointer to [**PoolUsageSchema**](PoolUsageSchema.md) |  | [optional] 
**Az** | Pointer to **NullableString** | Availability zone. | [optional] 
**Network** | Pointer to [**NetworkSchema**](NetworkSchema.md) |  | [optional] 
**Ec2InstanceType** | Pointer to **NullableString** | EC2 instance type, if applicable. | [optional] [default to ""]
**Op** | Pointer to **string** | Current operation. | [optional] 

## Methods

### NewServiceStatusRequestBody

`func NewServiceStatusRequestBody(healthy bool, serviceName string, address string, hostname string, nodeId string, ) *ServiceStatusRequestBody`

NewServiceStatusRequestBody instantiates a new ServiceStatusRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceStatusRequestBodyWithDefaults

`func NewServiceStatusRequestBodyWithDefaults() *ServiceStatusRequestBody`

NewServiceStatusRequestBodyWithDefaults instantiates a new ServiceStatusRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHealthy

`func (o *ServiceStatusRequestBody) GetHealthy() bool`

GetHealthy returns the Healthy field if non-nil, zero value otherwise.

### GetHealthyOk

`func (o *ServiceStatusRequestBody) GetHealthyOk() (*bool, bool)`

GetHealthyOk returns a tuple with the Healthy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthy

`func (o *ServiceStatusRequestBody) SetHealthy(v bool)`

SetHealthy sets Healthy field to given value.


### GetServiceName

`func (o *ServiceStatusRequestBody) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *ServiceStatusRequestBody) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *ServiceStatusRequestBody) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.


### GetAddress

`func (o *ServiceStatusRequestBody) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ServiceStatusRequestBody) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ServiceStatusRequestBody) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetHostname

`func (o *ServiceStatusRequestBody) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *ServiceStatusRequestBody) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *ServiceStatusRequestBody) SetHostname(v string)`

SetHostname sets Hostname field to given value.


### GetNodeId

`func (o *ServiceStatusRequestBody) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *ServiceStatusRequestBody) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *ServiceStatusRequestBody) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetSysInfo

`func (o *ServiceStatusRequestBody) GetSysInfo() SysInfoSchema`

GetSysInfo returns the SysInfo field if non-nil, zero value otherwise.

### GetSysInfoOk

`func (o *ServiceStatusRequestBody) GetSysInfoOk() (*SysInfoSchema, bool)`

GetSysInfoOk returns a tuple with the SysInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSysInfo

`func (o *ServiceStatusRequestBody) SetSysInfo(v SysInfoSchema)`

SetSysInfo sets SysInfo field to given value.

### HasSysInfo

`func (o *ServiceStatusRequestBody) HasSysInfo() bool`

HasSysInfo returns a boolean if a field has been set.

### GetLayout

`func (o *ServiceStatusRequestBody) GetLayout() LayoutSchema`

GetLayout returns the Layout field if non-nil, zero value otherwise.

### GetLayoutOk

`func (o *ServiceStatusRequestBody) GetLayoutOk() (*LayoutSchema, bool)`

GetLayoutOk returns a tuple with the Layout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLayout

`func (o *ServiceStatusRequestBody) SetLayout(v LayoutSchema)`

SetLayout sets Layout field to given value.

### HasLayout

`func (o *ServiceStatusRequestBody) HasLayout() bool`

HasLayout returns a boolean if a field has been set.

### GetVms

`func (o *ServiceStatusRequestBody) GetVms() []ServiceStatusRequestBodyVmsInner`

GetVms returns the Vms field if non-nil, zero value otherwise.

### GetVmsOk

`func (o *ServiceStatusRequestBody) GetVmsOk() (*[]ServiceStatusRequestBodyVmsInner, bool)`

GetVmsOk returns a tuple with the Vms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVms

`func (o *ServiceStatusRequestBody) SetVms(v []ServiceStatusRequestBodyVmsInner)`

SetVms sets Vms field to given value.

### HasVms

`func (o *ServiceStatusRequestBody) HasVms() bool`

HasVms returns a boolean if a field has been set.

### GetPoolUsage

`func (o *ServiceStatusRequestBody) GetPoolUsage() PoolUsageSchema`

GetPoolUsage returns the PoolUsage field if non-nil, zero value otherwise.

### GetPoolUsageOk

`func (o *ServiceStatusRequestBody) GetPoolUsageOk() (*PoolUsageSchema, bool)`

GetPoolUsageOk returns a tuple with the PoolUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolUsage

`func (o *ServiceStatusRequestBody) SetPoolUsage(v PoolUsageSchema)`

SetPoolUsage sets PoolUsage field to given value.

### HasPoolUsage

`func (o *ServiceStatusRequestBody) HasPoolUsage() bool`

HasPoolUsage returns a boolean if a field has been set.

### GetAz

`func (o *ServiceStatusRequestBody) GetAz() string`

GetAz returns the Az field if non-nil, zero value otherwise.

### GetAzOk

`func (o *ServiceStatusRequestBody) GetAzOk() (*string, bool)`

GetAzOk returns a tuple with the Az field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAz

`func (o *ServiceStatusRequestBody) SetAz(v string)`

SetAz sets Az field to given value.

### HasAz

`func (o *ServiceStatusRequestBody) HasAz() bool`

HasAz returns a boolean if a field has been set.

### SetAzNil

`func (o *ServiceStatusRequestBody) SetAzNil(b bool)`

 SetAzNil sets the value for Az to be an explicit nil

### UnsetAz
`func (o *ServiceStatusRequestBody) UnsetAz()`

UnsetAz ensures that no value is present for Az, not even an explicit nil
### GetNetwork

`func (o *ServiceStatusRequestBody) GetNetwork() NetworkSchema`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *ServiceStatusRequestBody) GetNetworkOk() (*NetworkSchema, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *ServiceStatusRequestBody) SetNetwork(v NetworkSchema)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *ServiceStatusRequestBody) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetEc2InstanceType

`func (o *ServiceStatusRequestBody) GetEc2InstanceType() string`

GetEc2InstanceType returns the Ec2InstanceType field if non-nil, zero value otherwise.

### GetEc2InstanceTypeOk

`func (o *ServiceStatusRequestBody) GetEc2InstanceTypeOk() (*string, bool)`

GetEc2InstanceTypeOk returns a tuple with the Ec2InstanceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEc2InstanceType

`func (o *ServiceStatusRequestBody) SetEc2InstanceType(v string)`

SetEc2InstanceType sets Ec2InstanceType field to given value.

### HasEc2InstanceType

`func (o *ServiceStatusRequestBody) HasEc2InstanceType() bool`

HasEc2InstanceType returns a boolean if a field has been set.

### SetEc2InstanceTypeNil

`func (o *ServiceStatusRequestBody) SetEc2InstanceTypeNil(b bool)`

 SetEc2InstanceTypeNil sets the value for Ec2InstanceType to be an explicit nil

### UnsetEc2InstanceType
`func (o *ServiceStatusRequestBody) UnsetEc2InstanceType()`

UnsetEc2InstanceType ensures that no value is present for Ec2InstanceType, not even an explicit nil
### GetOp

`func (o *ServiceStatusRequestBody) GetOp() string`

GetOp returns the Op field if non-nil, zero value otherwise.

### GetOpOk

`func (o *ServiceStatusRequestBody) GetOpOk() (*string, bool)`

GetOpOk returns a tuple with the Op field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOp

`func (o *ServiceStatusRequestBody) SetOp(v string)`

SetOp sets Op field to given value.

### HasOp

`func (o *ServiceStatusRequestBody) HasOp() bool`

HasOp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


