# ClusterNode

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reserved** | [**ClusterNodeReserved**](ClusterNodeReserved.md) |  | 
**Total** | [**ClusterNodeTotal**](ClusterNodeTotal.md) |  | 
**Available** | [**ClusterNodeAvailable**](ClusterNodeAvailable.md) |  | 
**Hostname** | **NullableString** | Node hostname. | 
**Address** | **string** | Node address (host:port). | 
**LastSeen** | **time.Time** | ISO timestamp of last heartbeat. | 

## Methods

### NewClusterNode

`func NewClusterNode(reserved ClusterNodeReserved, total ClusterNodeTotal, available ClusterNodeAvailable, hostname NullableString, address string, lastSeen time.Time, ) *ClusterNode`

NewClusterNode instantiates a new ClusterNode object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterNodeWithDefaults

`func NewClusterNodeWithDefaults() *ClusterNode`

NewClusterNodeWithDefaults instantiates a new ClusterNode object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReserved

`func (o *ClusterNode) GetReserved() ClusterNodeReserved`

GetReserved returns the Reserved field if non-nil, zero value otherwise.

### GetReservedOk

`func (o *ClusterNode) GetReservedOk() (*ClusterNodeReserved, bool)`

GetReservedOk returns a tuple with the Reserved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReserved

`func (o *ClusterNode) SetReserved(v ClusterNodeReserved)`

SetReserved sets Reserved field to given value.


### GetTotal

`func (o *ClusterNode) GetTotal() ClusterNodeTotal`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ClusterNode) GetTotalOk() (*ClusterNodeTotal, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ClusterNode) SetTotal(v ClusterNodeTotal)`

SetTotal sets Total field to given value.


### GetAvailable

`func (o *ClusterNode) GetAvailable() ClusterNodeAvailable`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *ClusterNode) GetAvailableOk() (*ClusterNodeAvailable, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *ClusterNode) SetAvailable(v ClusterNodeAvailable)`

SetAvailable sets Available field to given value.


### GetHostname

`func (o *ClusterNode) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *ClusterNode) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *ClusterNode) SetHostname(v string)`

SetHostname sets Hostname field to given value.


### SetHostnameNil

`func (o *ClusterNode) SetHostnameNil(b bool)`

 SetHostnameNil sets the value for Hostname to be an explicit nil

### UnsetHostname
`func (o *ClusterNode) UnsetHostname()`

UnsetHostname ensures that no value is present for Hostname, not even an explicit nil
### GetAddress

`func (o *ClusterNode) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ClusterNode) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ClusterNode) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetLastSeen

`func (o *ClusterNode) GetLastSeen() time.Time`

GetLastSeen returns the LastSeen field if non-nil, zero value otherwise.

### GetLastSeenOk

`func (o *ClusterNode) GetLastSeenOk() (*time.Time, bool)`

GetLastSeenOk returns a tuple with the LastSeen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSeen

`func (o *ClusterNode) SetLastSeen(v time.Time)`

SetLastSeen sets LastSeen field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


