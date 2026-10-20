# AssessmentSeverityCounts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**High** | **float32** | Number of high-severity checks available at assessment creation time. | 
**Medium** | **float32** | Number of medium-severity checks available at assessment creation time. | 
**Low** | **float32** | Number of low-severity checks available at assessment creation time. | 
**Info** | **float32** | Number of informational checks available at assessment creation time. | 

## Methods

### NewAssessmentSeverityCounts

`func NewAssessmentSeverityCounts(high float32, medium float32, low float32, info float32, ) *AssessmentSeverityCounts`

NewAssessmentSeverityCounts instantiates a new AssessmentSeverityCounts object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssessmentSeverityCountsWithDefaults

`func NewAssessmentSeverityCountsWithDefaults() *AssessmentSeverityCounts`

NewAssessmentSeverityCountsWithDefaults instantiates a new AssessmentSeverityCounts object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHigh

`func (o *AssessmentSeverityCounts) GetHigh() float32`

GetHigh returns the High field if non-nil, zero value otherwise.

### GetHighOk

`func (o *AssessmentSeverityCounts) GetHighOk() (*float32, bool)`

GetHighOk returns a tuple with the High field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHigh

`func (o *AssessmentSeverityCounts) SetHigh(v float32)`

SetHigh sets High field to given value.


### GetMedium

`func (o *AssessmentSeverityCounts) GetMedium() float32`

GetMedium returns the Medium field if non-nil, zero value otherwise.

### GetMediumOk

`func (o *AssessmentSeverityCounts) GetMediumOk() (*float32, bool)`

GetMediumOk returns a tuple with the Medium field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedium

`func (o *AssessmentSeverityCounts) SetMedium(v float32)`

SetMedium sets Medium field to given value.


### GetLow

`func (o *AssessmentSeverityCounts) GetLow() float32`

GetLow returns the Low field if non-nil, zero value otherwise.

### GetLowOk

`func (o *AssessmentSeverityCounts) GetLowOk() (*float32, bool)`

GetLowOk returns a tuple with the Low field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLow

`func (o *AssessmentSeverityCounts) SetLow(v float32)`

SetLow sets Low field to given value.


### GetInfo

`func (o *AssessmentSeverityCounts) GetInfo() float32`

GetInfo returns the Info field if non-nil, zero value otherwise.

### GetInfoOk

`func (o *AssessmentSeverityCounts) GetInfoOk() (*float32, bool)`

GetInfoOk returns a tuple with the Info field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfo

`func (o *AssessmentSeverityCounts) SetInfo(v float32)`

SetInfo sets Info field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


