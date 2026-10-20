# AssessmentHistoryResultsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | Month label in \&quot;MMM YYYY\&quot; format (e.g. \&quot;Jul 2025\&quot;). | 
**Complete** | **float32** | Number of successful assessments. | 
**Incomplete** | **float32** | Number of failed assessments. | 

## Methods

### NewAssessmentHistoryResultsInner

`func NewAssessmentHistoryResultsInner(date string, complete float32, incomplete float32, ) *AssessmentHistoryResultsInner`

NewAssessmentHistoryResultsInner instantiates a new AssessmentHistoryResultsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssessmentHistoryResultsInnerWithDefaults

`func NewAssessmentHistoryResultsInnerWithDefaults() *AssessmentHistoryResultsInner`

NewAssessmentHistoryResultsInnerWithDefaults instantiates a new AssessmentHistoryResultsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *AssessmentHistoryResultsInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *AssessmentHistoryResultsInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *AssessmentHistoryResultsInner) SetDate(v string)`

SetDate sets Date field to given value.


### GetComplete

`func (o *AssessmentHistoryResultsInner) GetComplete() float32`

GetComplete returns the Complete field if non-nil, zero value otherwise.

### GetCompleteOk

`func (o *AssessmentHistoryResultsInner) GetCompleteOk() (*float32, bool)`

GetCompleteOk returns a tuple with the Complete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplete

`func (o *AssessmentHistoryResultsInner) SetComplete(v float32)`

SetComplete sets Complete field to given value.


### GetIncomplete

`func (o *AssessmentHistoryResultsInner) GetIncomplete() float32`

GetIncomplete returns the Incomplete field if non-nil, zero value otherwise.

### GetIncompleteOk

`func (o *AssessmentHistoryResultsInner) GetIncompleteOk() (*float32, bool)`

GetIncompleteOk returns a tuple with the Incomplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncomplete

`func (o *AssessmentHistoryResultsInner) SetIncomplete(v float32)`

SetIncomplete sets Incomplete field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


