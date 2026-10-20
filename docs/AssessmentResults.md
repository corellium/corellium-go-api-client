# AssessmentResults

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pass** | **float32** | Number of checks that passed. | 
**Fail** | **float32** | Number of checks that failed. | 
**Error** | **float32** | Number of checks that errored during execution. | 
**Info** | **float32** | Number of informational checks. | 
**Na** | **float32** | Number of checks marked not applicable. | 
**Artifact** | **float32** | Number of artifact-category outcomes. | 
**Score** | **NullableFloat32** | Computed MATRIX score, or null for assessments created before scoring was introduced. | 

## Methods

### NewAssessmentResults

`func NewAssessmentResults(pass float32, fail float32, error_ float32, info float32, na float32, artifact float32, score NullableFloat32, ) *AssessmentResults`

NewAssessmentResults instantiates a new AssessmentResults object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssessmentResultsWithDefaults

`func NewAssessmentResultsWithDefaults() *AssessmentResults`

NewAssessmentResultsWithDefaults instantiates a new AssessmentResults object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPass

`func (o *AssessmentResults) GetPass() float32`

GetPass returns the Pass field if non-nil, zero value otherwise.

### GetPassOk

`func (o *AssessmentResults) GetPassOk() (*float32, bool)`

GetPassOk returns a tuple with the Pass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPass

`func (o *AssessmentResults) SetPass(v float32)`

SetPass sets Pass field to given value.


### GetFail

`func (o *AssessmentResults) GetFail() float32`

GetFail returns the Fail field if non-nil, zero value otherwise.

### GetFailOk

`func (o *AssessmentResults) GetFailOk() (*float32, bool)`

GetFailOk returns a tuple with the Fail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFail

`func (o *AssessmentResults) SetFail(v float32)`

SetFail sets Fail field to given value.


### GetError

`func (o *AssessmentResults) GetError() float32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AssessmentResults) GetErrorOk() (*float32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AssessmentResults) SetError(v float32)`

SetError sets Error field to given value.


### GetInfo

`func (o *AssessmentResults) GetInfo() float32`

GetInfo returns the Info field if non-nil, zero value otherwise.

### GetInfoOk

`func (o *AssessmentResults) GetInfoOk() (*float32, bool)`

GetInfoOk returns a tuple with the Info field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfo

`func (o *AssessmentResults) SetInfo(v float32)`

SetInfo sets Info field to given value.


### GetNa

`func (o *AssessmentResults) GetNa() float32`

GetNa returns the Na field if non-nil, zero value otherwise.

### GetNaOk

`func (o *AssessmentResults) GetNaOk() (*float32, bool)`

GetNaOk returns a tuple with the Na field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNa

`func (o *AssessmentResults) SetNa(v float32)`

SetNa sets Na field to given value.


### GetArtifact

`func (o *AssessmentResults) GetArtifact() float32`

GetArtifact returns the Artifact field if non-nil, zero value otherwise.

### GetArtifactOk

`func (o *AssessmentResults) GetArtifactOk() (*float32, bool)`

GetArtifactOk returns a tuple with the Artifact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifact

`func (o *AssessmentResults) SetArtifact(v float32)`

SetArtifact sets Artifact field to given value.


### GetScore

`func (o *AssessmentResults) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *AssessmentResults) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *AssessmentResults) SetScore(v float32)`

SetScore sets Score field to given value.


### SetScoreNil

`func (o *AssessmentResults) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *AssessmentResults) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


