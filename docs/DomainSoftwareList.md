# DomainSoftwareList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | [**[]DomainSoftware**](DomainSoftware.md) | Domain-level firmware images: uploads not scoped to a project or instance. | 
**Count** | **float32** | Number of results in this page. Can be less than &#x60;limit&#x60; on the last page. | 
**Total** | **float32** | Number of results across all pages, after any filters. | 
**Limit** | **float32** | The page size that was used (your &#x60;limit&#x60;, or the default 100). | 
**Offset** | **float32** | The offset that was used (your &#x60;offset&#x60;, or the default 0). | 
**HasMore** | **bool** | True if more results exist after this page. To read everything, keep requesting with &#x60;offset&#x60; increased by &#x60;limit&#x60; until this is false. | 

## Methods

### NewDomainSoftwareList

`func NewDomainSoftwareList(results []DomainSoftware, count float32, total float32, limit float32, offset float32, hasMore bool, ) *DomainSoftwareList`

NewDomainSoftwareList instantiates a new DomainSoftwareList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainSoftwareListWithDefaults

`func NewDomainSoftwareListWithDefaults() *DomainSoftwareList`

NewDomainSoftwareListWithDefaults instantiates a new DomainSoftwareList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *DomainSoftwareList) GetResults() []DomainSoftware`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *DomainSoftwareList) GetResultsOk() (*[]DomainSoftware, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *DomainSoftwareList) SetResults(v []DomainSoftware)`

SetResults sets Results field to given value.


### GetCount

`func (o *DomainSoftwareList) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *DomainSoftwareList) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *DomainSoftwareList) SetCount(v float32)`

SetCount sets Count field to given value.


### GetTotal

`func (o *DomainSoftwareList) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *DomainSoftwareList) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *DomainSoftwareList) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetLimit

`func (o *DomainSoftwareList) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *DomainSoftwareList) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *DomainSoftwareList) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *DomainSoftwareList) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *DomainSoftwareList) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *DomainSoftwareList) SetOffset(v float32)`

SetOffset sets Offset field to given value.


### GetHasMore

`func (o *DomainSoftwareList) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *DomainSoftwareList) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *DomainSoftwareList) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


