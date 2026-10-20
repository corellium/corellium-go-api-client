# AssessmentHistoryLineItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **float32** | UNIX Date representing the month | 
**Complete** | **float32** | The number of successful assessments | 
**Incomplete** | **float32** | The number of failed assessments | 

## Methods

### NewAssessmentHistoryLineItem

`func NewAssessmentHistoryLineItem(date float32, complete float32, incomplete float32, ) *AssessmentHistoryLineItem`

NewAssessmentHistoryLineItem instantiates a new AssessmentHistoryLineItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssessmentHistoryLineItemWithDefaults

`func NewAssessmentHistoryLineItemWithDefaults() *AssessmentHistoryLineItem`

NewAssessmentHistoryLineItemWithDefaults instantiates a new AssessmentHistoryLineItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *AssessmentHistoryLineItem) GetDate() float32`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *AssessmentHistoryLineItem) GetDateOk() (*float32, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *AssessmentHistoryLineItem) SetDate(v float32)`

SetDate sets Date field to given value.


### GetComplete

`func (o *AssessmentHistoryLineItem) GetComplete() float32`

GetComplete returns the Complete field if non-nil, zero value otherwise.

### GetCompleteOk

`func (o *AssessmentHistoryLineItem) GetCompleteOk() (*float32, bool)`

GetCompleteOk returns a tuple with the Complete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplete

`func (o *AssessmentHistoryLineItem) SetComplete(v float32)`

SetComplete sets Complete field to given value.


### GetIncomplete

`func (o *AssessmentHistoryLineItem) GetIncomplete() float32`

GetIncomplete returns the Incomplete field if non-nil, zero value otherwise.

### GetIncompleteOk

`func (o *AssessmentHistoryLineItem) GetIncompleteOk() (*float32, bool)`

GetIncompleteOk returns a tuple with the Incomplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncomplete

`func (o *AssessmentHistoryLineItem) SetIncomplete(v float32)`

SetIncomplete sets Incomplete field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


