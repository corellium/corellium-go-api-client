# ClusterConfigUpdateError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** | Human-readable instruction to retry or resolve manually. | 
**Nodes** | Pointer to [**[]NodeInformation**](NodeInformation.md) | Nodes that failed to receive the configuration update. | [optional] 

## Methods

### NewClusterConfigUpdateError

`func NewClusterConfigUpdateError(message string, ) *ClusterConfigUpdateError`

NewClusterConfigUpdateError instantiates a new ClusterConfigUpdateError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterConfigUpdateErrorWithDefaults

`func NewClusterConfigUpdateErrorWithDefaults() *ClusterConfigUpdateError`

NewClusterConfigUpdateErrorWithDefaults instantiates a new ClusterConfigUpdateError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ClusterConfigUpdateError) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ClusterConfigUpdateError) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ClusterConfigUpdateError) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetNodes

`func (o *ClusterConfigUpdateError) GetNodes() []NodeInformation`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *ClusterConfigUpdateError) GetNodesOk() (*[]NodeInformation, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *ClusterConfigUpdateError) SetNodes(v []NodeInformation)`

SetNodes sets Nodes field to given value.

### HasNodes

`func (o *ClusterConfigUpdateError) HasNodes() bool`

HasNodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


