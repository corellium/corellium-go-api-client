# ReportModificationResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CheckId** | **string** | Identifier of the check the modification applied to. | 
**Property** | **string** | Property of the check that was modified. | 
**Status** | **string** | Outcome of applying the modification. | 
**Error** | Pointer to **string** | Explanation when the modification was ignored or errored. | [optional] 

## Methods

### NewReportModificationResult

`func NewReportModificationResult(checkId string, property string, status string, ) *ReportModificationResult`

NewReportModificationResult instantiates a new ReportModificationResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReportModificationResultWithDefaults

`func NewReportModificationResultWithDefaults() *ReportModificationResult`

NewReportModificationResultWithDefaults instantiates a new ReportModificationResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCheckId

`func (o *ReportModificationResult) GetCheckId() string`

GetCheckId returns the CheckId field if non-nil, zero value otherwise.

### GetCheckIdOk

`func (o *ReportModificationResult) GetCheckIdOk() (*string, bool)`

GetCheckIdOk returns a tuple with the CheckId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckId

`func (o *ReportModificationResult) SetCheckId(v string)`

SetCheckId sets CheckId field to given value.


### GetProperty

`func (o *ReportModificationResult) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *ReportModificationResult) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *ReportModificationResult) SetProperty(v string)`

SetProperty sets Property field to given value.


### GetStatus

`func (o *ReportModificationResult) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ReportModificationResult) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ReportModificationResult) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetError

`func (o *ReportModificationResult) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ReportModificationResult) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ReportModificationResult) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ReportModificationResult) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


