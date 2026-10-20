# ProjectInstanceSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Instance identifier. | 
**Name** | **string** | Instance name. | 
**Project** | **string** | Identifier of the project the instance belongs to. | 
**State** | **string** | Current instance state. | 

## Methods

### NewProjectInstanceSummary

`func NewProjectInstanceSummary(id string, name string, project string, state string, ) *ProjectInstanceSummary`

NewProjectInstanceSummary instantiates a new ProjectInstanceSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectInstanceSummaryWithDefaults

`func NewProjectInstanceSummaryWithDefaults() *ProjectInstanceSummary`

NewProjectInstanceSummaryWithDefaults instantiates a new ProjectInstanceSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectInstanceSummary) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectInstanceSummary) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectInstanceSummary) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ProjectInstanceSummary) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectInstanceSummary) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectInstanceSummary) SetName(v string)`

SetName sets Name field to given value.


### GetProject

`func (o *ProjectInstanceSummary) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ProjectInstanceSummary) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ProjectInstanceSummary) SetProject(v string)`

SetProject sets Project field to given value.


### GetState

`func (o *ProjectInstanceSummary) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ProjectInstanceSummary) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ProjectInstanceSummary) SetState(v string)`

SetState sets State field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


