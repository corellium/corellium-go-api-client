# ClusterNodeStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClusterTotals** | [**ClusterNodeStatusClusterTotals**](ClusterNodeStatusClusterTotals.md) |  | 
**Nodes** | [**[]ClusterNode**](ClusterNode.md) | Individual node statuses. | 

## Methods

### NewClusterNodeStatus

`func NewClusterNodeStatus(clusterTotals ClusterNodeStatusClusterTotals, nodes []ClusterNode, ) *ClusterNodeStatus`

NewClusterNodeStatus instantiates a new ClusterNodeStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterNodeStatusWithDefaults

`func NewClusterNodeStatusWithDefaults() *ClusterNodeStatus`

NewClusterNodeStatusWithDefaults instantiates a new ClusterNodeStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClusterTotals

`func (o *ClusterNodeStatus) GetClusterTotals() ClusterNodeStatusClusterTotals`

GetClusterTotals returns the ClusterTotals field if non-nil, zero value otherwise.

### GetClusterTotalsOk

`func (o *ClusterNodeStatus) GetClusterTotalsOk() (*ClusterNodeStatusClusterTotals, bool)`

GetClusterTotalsOk returns a tuple with the ClusterTotals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterTotals

`func (o *ClusterNodeStatus) SetClusterTotals(v ClusterNodeStatusClusterTotals)`

SetClusterTotals sets ClusterTotals field to given value.


### GetNodes

`func (o *ClusterNodeStatus) GetNodes() []ClusterNode`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *ClusterNodeStatus) GetNodesOk() (*[]ClusterNode, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *ClusterNodeStatus) SetNodes(v []ClusterNode)`

SetNodes sets Nodes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


