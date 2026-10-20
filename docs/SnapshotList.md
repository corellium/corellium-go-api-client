# SnapshotList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | Pointer to [**[]ClusterSnapshotV1**](ClusterSnapshotV1.md) | List of snapshots | [optional] 
**Offset** | Pointer to **NullableFloat32** | Offset for pagination, defaults to 0 | [optional] 
**Limit** | Pointer to **NullableFloat32** | Number of items to return, defaults to 100, minimum of 1 and maximum of 1000 | [optional] 
**Count** | Pointer to **NullableFloat32** | Number of items in current response | [optional] 

## Methods

### NewSnapshotList

`func NewSnapshotList() *SnapshotList`

NewSnapshotList instantiates a new SnapshotList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnapshotListWithDefaults

`func NewSnapshotListWithDefaults() *SnapshotList`

NewSnapshotListWithDefaults instantiates a new SnapshotList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *SnapshotList) GetResults() []ClusterSnapshotV1`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *SnapshotList) GetResultsOk() (*[]ClusterSnapshotV1, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *SnapshotList) SetResults(v []ClusterSnapshotV1)`

SetResults sets Results field to given value.

### HasResults

`func (o *SnapshotList) HasResults() bool`

HasResults returns a boolean if a field has been set.

### SetResultsNil

`func (o *SnapshotList) SetResultsNil(b bool)`

 SetResultsNil sets the value for Results to be an explicit nil

### UnsetResults
`func (o *SnapshotList) UnsetResults()`

UnsetResults ensures that no value is present for Results, not even an explicit nil
### GetOffset

`func (o *SnapshotList) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *SnapshotList) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *SnapshotList) SetOffset(v float32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *SnapshotList) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### SetOffsetNil

`func (o *SnapshotList) SetOffsetNil(b bool)`

 SetOffsetNil sets the value for Offset to be an explicit nil

### UnsetOffset
`func (o *SnapshotList) UnsetOffset()`

UnsetOffset ensures that no value is present for Offset, not even an explicit nil
### GetLimit

`func (o *SnapshotList) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *SnapshotList) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *SnapshotList) SetLimit(v float32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *SnapshotList) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### SetLimitNil

`func (o *SnapshotList) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *SnapshotList) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetCount

`func (o *SnapshotList) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *SnapshotList) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *SnapshotList) SetCount(v float32)`

SetCount sets Count field to given value.

### HasCount

`func (o *SnapshotList) HasCount() bool`

HasCount returns a boolean if a field has been set.

### SetCountNil

`func (o *SnapshotList) SetCountNil(b bool)`

 SetCountNil sets the value for Count to be an explicit nil

### UnsetCount
`func (o *SnapshotList) UnsetCount()`

UnsetCount ensures that no value is present for Count, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


