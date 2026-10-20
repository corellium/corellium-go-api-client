# AssessmentIdStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Identifier of the assessment. | 
**Status** | [**AssessmentStatus**](AssessmentStatus.md) |  | 

## Methods

### NewAssessmentIdStatus

`func NewAssessmentIdStatus(id string, status AssessmentStatus, ) *AssessmentIdStatus`

NewAssessmentIdStatus instantiates a new AssessmentIdStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssessmentIdStatusWithDefaults

`func NewAssessmentIdStatusWithDefaults() *AssessmentIdStatus`

NewAssessmentIdStatusWithDefaults instantiates a new AssessmentIdStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AssessmentIdStatus) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssessmentIdStatus) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssessmentIdStatus) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *AssessmentIdStatus) GetStatus() AssessmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AssessmentIdStatus) GetStatusOk() (*AssessmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AssessmentIdStatus) SetStatus(v AssessmentStatus)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


