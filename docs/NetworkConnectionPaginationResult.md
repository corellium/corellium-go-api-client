# NetworkConnectionPaginationResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **float32** | Total number of items. | 
**Count** | **float32** | The number of items returned in this result. | 
**Limit** | **float32** | The maximum number of items that could be returned for this result. | 
**Offset** | **float32** | That starting item 0-indexed. | 
**HasMore** | **bool** | Whether or not there are more results to fetch. | 
**Results** | [**[]NetworkConnection**](NetworkConnection.md) | Array of network connections associated with this domain. | 

## Methods

### NewNetworkConnectionPaginationResult

`func NewNetworkConnectionPaginationResult(total float32, count float32, limit float32, offset float32, hasMore bool, results []NetworkConnection, ) *NetworkConnectionPaginationResult`

NewNetworkConnectionPaginationResult instantiates a new NetworkConnectionPaginationResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkConnectionPaginationResultWithDefaults

`func NewNetworkConnectionPaginationResultWithDefaults() *NetworkConnectionPaginationResult`

NewNetworkConnectionPaginationResultWithDefaults instantiates a new NetworkConnectionPaginationResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *NetworkConnectionPaginationResult) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *NetworkConnectionPaginationResult) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *NetworkConnectionPaginationResult) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetCount

`func (o *NetworkConnectionPaginationResult) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *NetworkConnectionPaginationResult) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *NetworkConnectionPaginationResult) SetCount(v float32)`

SetCount sets Count field to given value.


### GetLimit

`func (o *NetworkConnectionPaginationResult) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *NetworkConnectionPaginationResult) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *NetworkConnectionPaginationResult) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *NetworkConnectionPaginationResult) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *NetworkConnectionPaginationResult) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *NetworkConnectionPaginationResult) SetOffset(v float32)`

SetOffset sets Offset field to given value.


### GetHasMore

`func (o *NetworkConnectionPaginationResult) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *NetworkConnectionPaginationResult) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *NetworkConnectionPaginationResult) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetResults

`func (o *NetworkConnectionPaginationResult) GetResults() []NetworkConnection`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *NetworkConnectionPaginationResult) GetResultsOk() (*[]NetworkConnection, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *NetworkConnectionPaginationResult) SetResults(v []NetworkConnection)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


