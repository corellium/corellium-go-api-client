# PaginatedAssessments

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | **float32** | Maximum number of assessments requested. | 
**Offset** | **float32** | Number of assessments skipped before this page. | 
**Count** | **float32** | Number of assessments returned in this page. | 
**Total** | **float32** | Total number of assessments for the instance. | 
**Results** | [**[]Assessment**](Assessment.md) | The page of assessments. | 

## Methods

### NewPaginatedAssessments

`func NewPaginatedAssessments(limit float32, offset float32, count float32, total float32, results []Assessment, ) *PaginatedAssessments`

NewPaginatedAssessments instantiates a new PaginatedAssessments object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedAssessmentsWithDefaults

`func NewPaginatedAssessmentsWithDefaults() *PaginatedAssessments`

NewPaginatedAssessmentsWithDefaults instantiates a new PaginatedAssessments object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *PaginatedAssessments) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *PaginatedAssessments) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *PaginatedAssessments) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *PaginatedAssessments) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *PaginatedAssessments) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *PaginatedAssessments) SetOffset(v float32)`

SetOffset sets Offset field to given value.


### GetCount

`func (o *PaginatedAssessments) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PaginatedAssessments) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PaginatedAssessments) SetCount(v float32)`

SetCount sets Count field to given value.


### GetTotal

`func (o *PaginatedAssessments) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PaginatedAssessments) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PaginatedAssessments) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetResults

`func (o *PaginatedAssessments) GetResults() []Assessment`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *PaginatedAssessments) GetResultsOk() (*[]Assessment, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *PaginatedAssessments) SetResults(v []Assessment)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


