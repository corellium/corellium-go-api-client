# AssessmentHistoryV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **float32** | Total number of items | 
**Count** | **float32** | Number of items in current response | 
**Limit** | **float32** | Limit used for the request | 
**Offset** | **float32** | Offset used for the request | 
**Results** | [**[]AssessmentHistoryLineItem**](AssessmentHistoryLineItem.md) | The list of assessments | 

## Methods

### NewAssessmentHistoryV1

`func NewAssessmentHistoryV1(total float32, count float32, limit float32, offset float32, results []AssessmentHistoryLineItem, ) *AssessmentHistoryV1`

NewAssessmentHistoryV1 instantiates a new AssessmentHistoryV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssessmentHistoryV1WithDefaults

`func NewAssessmentHistoryV1WithDefaults() *AssessmentHistoryV1`

NewAssessmentHistoryV1WithDefaults instantiates a new AssessmentHistoryV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *AssessmentHistoryV1) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AssessmentHistoryV1) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AssessmentHistoryV1) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetCount

`func (o *AssessmentHistoryV1) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *AssessmentHistoryV1) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *AssessmentHistoryV1) SetCount(v float32)`

SetCount sets Count field to given value.


### GetLimit

`func (o *AssessmentHistoryV1) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AssessmentHistoryV1) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AssessmentHistoryV1) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *AssessmentHistoryV1) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *AssessmentHistoryV1) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *AssessmentHistoryV1) SetOffset(v float32)`

SetOffset sets Offset field to given value.


### GetResults

`func (o *AssessmentHistoryV1) GetResults() []AssessmentHistoryLineItem`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *AssessmentHistoryV1) GetResultsOk() (*[]AssessmentHistoryLineItem, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *AssessmentHistoryV1) SetResults(v []AssessmentHistoryLineItem)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


