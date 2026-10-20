# TrialRequestListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | [**[]TrialRequest**](TrialRequest.md) | Trial requests. | 
**Count** | **float32** | Number of results in this page. Can be less than &#x60;limit&#x60; on the last page. | 
**Total** | **float32** | Number of results across all pages, after any filters. | 
**Limit** | **float32** | The page size that was used (your &#x60;limit&#x60;, or the default 100). | 
**Offset** | **float32** | The offset that was used (your &#x60;offset&#x60;, or the default 0). | 
**HasMore** | **bool** | True if more results exist after this page. To read everything, keep requesting with &#x60;offset&#x60; increased by &#x60;limit&#x60; until this is false. | 

## Methods

### NewTrialRequestListResponse

`func NewTrialRequestListResponse(results []TrialRequest, count float32, total float32, limit float32, offset float32, hasMore bool, ) *TrialRequestListResponse`

NewTrialRequestListResponse instantiates a new TrialRequestListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrialRequestListResponseWithDefaults

`func NewTrialRequestListResponseWithDefaults() *TrialRequestListResponse`

NewTrialRequestListResponseWithDefaults instantiates a new TrialRequestListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *TrialRequestListResponse) GetResults() []TrialRequest`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *TrialRequestListResponse) GetResultsOk() (*[]TrialRequest, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *TrialRequestListResponse) SetResults(v []TrialRequest)`

SetResults sets Results field to given value.


### GetCount

`func (o *TrialRequestListResponse) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *TrialRequestListResponse) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *TrialRequestListResponse) SetCount(v float32)`

SetCount sets Count field to given value.


### GetTotal

`func (o *TrialRequestListResponse) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *TrialRequestListResponse) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *TrialRequestListResponse) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetLimit

`func (o *TrialRequestListResponse) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *TrialRequestListResponse) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *TrialRequestListResponse) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *TrialRequestListResponse) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *TrialRequestListResponse) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *TrialRequestListResponse) SetOffset(v float32)`

SetOffset sets Offset field to given value.


### GetHasMore

`func (o *TrialRequestListResponse) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *TrialRequestListResponse) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *TrialRequestListResponse) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


