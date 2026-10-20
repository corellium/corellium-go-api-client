# Assessment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Identifier of the assessment. | 
**Status** | [**AssessmentStatus**](AssessmentStatus.md) |  | 
**InstanceId** | **string** | Identifier of the instance under assessment. | 
**Bundle** | [**AssessmentBundle**](AssessmentBundle.md) |  | 
**Wordlist** | [**NullableAssessmentWordlist**](AssessmentWordlist.md) |  | 
**FridaScript** | [**NullableAssessmentFridaScript**](AssessmentFridaScript.md) |  | 
**ReportId** | **NullableString** | Identifier of the generated report, or null if not yet available. | 
**Results** | [**NullableAssessmentResults**](AssessmentResults.md) |  | 
**Metadata** | [**NullableAssessmentMetadata**](AssessmentMetadata.md) |  | 
**SeverityCounts** | [**NullableAssessmentSeverityCounts**](AssessmentSeverityCounts.md) |  | 
**Error** | **NullableString** | Why the assessment failed, or null. Set only when monitoring fails, to one of: \&quot;Insufficient memory; increase device&#39;s RAM.\&quot;, \&quot;App closed too soon; keep open until report has generated.\&quot;, \&quot;App unable to launch; check compatibility.\&quot;, or \&quot;Unknown error.\&quot;. An assessment that fails while tests run has status &#x60;failed&#x60; with &#x60;error&#x60; null. | 
**CreatedBy** | **NullableString** | Identifier of the user that created the assessment, or null. | 
**CreatedAt** | **NullableTime** | Creation timestamp. | 
**UpdatedAt** | **NullableTime** | Last-update timestamp. | 

## Methods

### NewAssessment

`func NewAssessment(id string, status AssessmentStatus, instanceId string, bundle AssessmentBundle, wordlist NullableAssessmentWordlist, fridaScript NullableAssessmentFridaScript, reportId NullableString, results NullableAssessmentResults, metadata NullableAssessmentMetadata, severityCounts NullableAssessmentSeverityCounts, error_ NullableString, createdBy NullableString, createdAt NullableTime, updatedAt NullableTime, ) *Assessment`

NewAssessment instantiates a new Assessment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssessmentWithDefaults

`func NewAssessmentWithDefaults() *Assessment`

NewAssessmentWithDefaults instantiates a new Assessment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Assessment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Assessment) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Assessment) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *Assessment) GetStatus() AssessmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Assessment) GetStatusOk() (*AssessmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Assessment) SetStatus(v AssessmentStatus)`

SetStatus sets Status field to given value.


### GetInstanceId

`func (o *Assessment) GetInstanceId() string`

GetInstanceId returns the InstanceId field if non-nil, zero value otherwise.

### GetInstanceIdOk

`func (o *Assessment) GetInstanceIdOk() (*string, bool)`

GetInstanceIdOk returns a tuple with the InstanceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceId

`func (o *Assessment) SetInstanceId(v string)`

SetInstanceId sets InstanceId field to given value.


### GetBundle

`func (o *Assessment) GetBundle() AssessmentBundle`

GetBundle returns the Bundle field if non-nil, zero value otherwise.

### GetBundleOk

`func (o *Assessment) GetBundleOk() (*AssessmentBundle, bool)`

GetBundleOk returns a tuple with the Bundle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundle

`func (o *Assessment) SetBundle(v AssessmentBundle)`

SetBundle sets Bundle field to given value.


### GetWordlist

`func (o *Assessment) GetWordlist() AssessmentWordlist`

GetWordlist returns the Wordlist field if non-nil, zero value otherwise.

### GetWordlistOk

`func (o *Assessment) GetWordlistOk() (*AssessmentWordlist, bool)`

GetWordlistOk returns a tuple with the Wordlist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWordlist

`func (o *Assessment) SetWordlist(v AssessmentWordlist)`

SetWordlist sets Wordlist field to given value.


### SetWordlistNil

`func (o *Assessment) SetWordlistNil(b bool)`

 SetWordlistNil sets the value for Wordlist to be an explicit nil

### UnsetWordlist
`func (o *Assessment) UnsetWordlist()`

UnsetWordlist ensures that no value is present for Wordlist, not even an explicit nil
### GetFridaScript

`func (o *Assessment) GetFridaScript() AssessmentFridaScript`

GetFridaScript returns the FridaScript field if non-nil, zero value otherwise.

### GetFridaScriptOk

`func (o *Assessment) GetFridaScriptOk() (*AssessmentFridaScript, bool)`

GetFridaScriptOk returns a tuple with the FridaScript field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFridaScript

`func (o *Assessment) SetFridaScript(v AssessmentFridaScript)`

SetFridaScript sets FridaScript field to given value.


### SetFridaScriptNil

`func (o *Assessment) SetFridaScriptNil(b bool)`

 SetFridaScriptNil sets the value for FridaScript to be an explicit nil

### UnsetFridaScript
`func (o *Assessment) UnsetFridaScript()`

UnsetFridaScript ensures that no value is present for FridaScript, not even an explicit nil
### GetReportId

`func (o *Assessment) GetReportId() string`

GetReportId returns the ReportId field if non-nil, zero value otherwise.

### GetReportIdOk

`func (o *Assessment) GetReportIdOk() (*string, bool)`

GetReportIdOk returns a tuple with the ReportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportId

`func (o *Assessment) SetReportId(v string)`

SetReportId sets ReportId field to given value.


### SetReportIdNil

`func (o *Assessment) SetReportIdNil(b bool)`

 SetReportIdNil sets the value for ReportId to be an explicit nil

### UnsetReportId
`func (o *Assessment) UnsetReportId()`

UnsetReportId ensures that no value is present for ReportId, not even an explicit nil
### GetResults

`func (o *Assessment) GetResults() AssessmentResults`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *Assessment) GetResultsOk() (*AssessmentResults, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *Assessment) SetResults(v AssessmentResults)`

SetResults sets Results field to given value.


### SetResultsNil

`func (o *Assessment) SetResultsNil(b bool)`

 SetResultsNil sets the value for Results to be an explicit nil

### UnsetResults
`func (o *Assessment) UnsetResults()`

UnsetResults ensures that no value is present for Results, not even an explicit nil
### GetMetadata

`func (o *Assessment) GetMetadata() AssessmentMetadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Assessment) GetMetadataOk() (*AssessmentMetadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Assessment) SetMetadata(v AssessmentMetadata)`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *Assessment) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *Assessment) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetSeverityCounts

`func (o *Assessment) GetSeverityCounts() AssessmentSeverityCounts`

GetSeverityCounts returns the SeverityCounts field if non-nil, zero value otherwise.

### GetSeverityCountsOk

`func (o *Assessment) GetSeverityCountsOk() (*AssessmentSeverityCounts, bool)`

GetSeverityCountsOk returns a tuple with the SeverityCounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverityCounts

`func (o *Assessment) SetSeverityCounts(v AssessmentSeverityCounts)`

SetSeverityCounts sets SeverityCounts field to given value.


### SetSeverityCountsNil

`func (o *Assessment) SetSeverityCountsNil(b bool)`

 SetSeverityCountsNil sets the value for SeverityCounts to be an explicit nil

### UnsetSeverityCounts
`func (o *Assessment) UnsetSeverityCounts()`

UnsetSeverityCounts ensures that no value is present for SeverityCounts, not even an explicit nil
### GetError

`func (o *Assessment) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *Assessment) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *Assessment) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *Assessment) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *Assessment) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetCreatedBy

`func (o *Assessment) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *Assessment) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *Assessment) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### SetCreatedByNil

`func (o *Assessment) SetCreatedByNil(b bool)`

 SetCreatedByNil sets the value for CreatedBy to be an explicit nil

### UnsetCreatedBy
`func (o *Assessment) UnsetCreatedBy()`

UnsetCreatedBy ensures that no value is present for CreatedBy, not even an explicit nil
### GetCreatedAt

`func (o *Assessment) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Assessment) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Assessment) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *Assessment) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *Assessment) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *Assessment) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Assessment) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Assessment) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### SetUpdatedAtNil

`func (o *Assessment) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Assessment) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


