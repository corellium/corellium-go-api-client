# ReportModificationInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CheckId** | **string** | Identifier of the check to modify. | 
**Property** | **string** | Property of the check to modify: \&quot;outcome\&quot;, \&quot;severity\&quot;, or \&quot;evidence_&lt;index&gt;\&quot;. | 
**Suppressed** | Pointer to **bool** | For an \&quot;evidence_&lt;index&gt;\&quot; property, whether the evidence entry is suppressed. Required for evidence modifications. | [optional] 
**Value** | Pointer to **string** | New value for the property. Required for \&quot;outcome\&quot; and \&quot;severity\&quot;; must be omitted for \&quot;evidence_&lt;index&gt;\&quot;. | [optional] 

## Methods

### NewReportModificationInput

`func NewReportModificationInput(checkId string, property string, ) *ReportModificationInput`

NewReportModificationInput instantiates a new ReportModificationInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReportModificationInputWithDefaults

`func NewReportModificationInputWithDefaults() *ReportModificationInput`

NewReportModificationInputWithDefaults instantiates a new ReportModificationInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCheckId

`func (o *ReportModificationInput) GetCheckId() string`

GetCheckId returns the CheckId field if non-nil, zero value otherwise.

### GetCheckIdOk

`func (o *ReportModificationInput) GetCheckIdOk() (*string, bool)`

GetCheckIdOk returns a tuple with the CheckId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckId

`func (o *ReportModificationInput) SetCheckId(v string)`

SetCheckId sets CheckId field to given value.


### GetProperty

`func (o *ReportModificationInput) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *ReportModificationInput) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *ReportModificationInput) SetProperty(v string)`

SetProperty sets Property field to given value.


### GetSuppressed

`func (o *ReportModificationInput) GetSuppressed() bool`

GetSuppressed returns the Suppressed field if non-nil, zero value otherwise.

### GetSuppressedOk

`func (o *ReportModificationInput) GetSuppressedOk() (*bool, bool)`

GetSuppressedOk returns a tuple with the Suppressed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppressed

`func (o *ReportModificationInput) SetSuppressed(v bool)`

SetSuppressed sets Suppressed field to given value.

### HasSuppressed

`func (o *ReportModificationInput) HasSuppressed() bool`

HasSuppressed returns a boolean if a field has been set.

### GetValue

`func (o *ReportModificationInput) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ReportModificationInput) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ReportModificationInput) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *ReportModificationInput) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


