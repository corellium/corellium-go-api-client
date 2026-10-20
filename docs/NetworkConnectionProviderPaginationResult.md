# NetworkConnectionProviderPaginationResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **float32** | Total number of items. | 
**Count** | **float32** | The number of items returned in this result. | 
**Limit** | **float32** | The maximum number of items that could be returned for this result. | 
**Offset** | **float32** | That starting item 0-indexed. | 
**Results** | [**[]NetworkConnectionProvider**](NetworkConnectionProvider.md) | Array of network connection providers. | 

## Methods

### NewNetworkConnectionProviderPaginationResult

`func NewNetworkConnectionProviderPaginationResult(total float32, count float32, limit float32, offset float32, results []NetworkConnectionProvider, ) *NetworkConnectionProviderPaginationResult`

NewNetworkConnectionProviderPaginationResult instantiates a new NetworkConnectionProviderPaginationResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkConnectionProviderPaginationResultWithDefaults

`func NewNetworkConnectionProviderPaginationResultWithDefaults() *NetworkConnectionProviderPaginationResult`

NewNetworkConnectionProviderPaginationResultWithDefaults instantiates a new NetworkConnectionProviderPaginationResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *NetworkConnectionProviderPaginationResult) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *NetworkConnectionProviderPaginationResult) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *NetworkConnectionProviderPaginationResult) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetCount

`func (o *NetworkConnectionProviderPaginationResult) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *NetworkConnectionProviderPaginationResult) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *NetworkConnectionProviderPaginationResult) SetCount(v float32)`

SetCount sets Count field to given value.


### GetLimit

`func (o *NetworkConnectionProviderPaginationResult) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *NetworkConnectionProviderPaginationResult) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *NetworkConnectionProviderPaginationResult) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *NetworkConnectionProviderPaginationResult) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *NetworkConnectionProviderPaginationResult) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *NetworkConnectionProviderPaginationResult) SetOffset(v float32)`

SetOffset sets Offset field to given value.


### GetResults

`func (o *NetworkConnectionProviderPaginationResult) GetResults() []NetworkConnectionProvider`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *NetworkConnectionProviderPaginationResult) GetResultsOk() (*[]NetworkConnectionProvider, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *NetworkConnectionProviderPaginationResult) SetResults(v []NetworkConnectionProvider)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


