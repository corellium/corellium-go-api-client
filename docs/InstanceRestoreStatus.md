# InstanceRestoreStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Restore type: 0&#x3D;Not Restore, 1&#x3D;Restore, 2&#x3D;CloneFromSnapshot. | [optional] 
**Stage** | Pointer to **string** | Restore stage. | [optional] 
**Progress** | Pointer to **interface{}** | Stage progress (0-100). Serialized as a string when non-zero; emitted as the number 0 at the start of a restore, and absent when no restore is in progress. | [optional] 
**TotalProgress** | Pointer to **interface{}** | Total restore progress (0-100). Serialized as a string when non-zero; emitted as the number 0 at the start of a restore, and absent when no restore is in progress. | [optional] 
**Heading** | Pointer to **string** | Current heading for progress modal. | [optional] 
**Description** | Pointer to **string** | Current description for progress modal. | [optional] 

## Methods

### NewInstanceRestoreStatus

`func NewInstanceRestoreStatus() *InstanceRestoreStatus`

NewInstanceRestoreStatus instantiates a new InstanceRestoreStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceRestoreStatusWithDefaults

`func NewInstanceRestoreStatusWithDefaults() *InstanceRestoreStatus`

NewInstanceRestoreStatusWithDefaults instantiates a new InstanceRestoreStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *InstanceRestoreStatus) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InstanceRestoreStatus) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InstanceRestoreStatus) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InstanceRestoreStatus) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStage

`func (o *InstanceRestoreStatus) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *InstanceRestoreStatus) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *InstanceRestoreStatus) SetStage(v string)`

SetStage sets Stage field to given value.

### HasStage

`func (o *InstanceRestoreStatus) HasStage() bool`

HasStage returns a boolean if a field has been set.

### GetProgress

`func (o *InstanceRestoreStatus) GetProgress() interface{}`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *InstanceRestoreStatus) GetProgressOk() (*interface{}, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *InstanceRestoreStatus) SetProgress(v interface{})`

SetProgress sets Progress field to given value.

### HasProgress

`func (o *InstanceRestoreStatus) HasProgress() bool`

HasProgress returns a boolean if a field has been set.

### SetProgressNil

`func (o *InstanceRestoreStatus) SetProgressNil(b bool)`

 SetProgressNil sets the value for Progress to be an explicit nil

### UnsetProgress
`func (o *InstanceRestoreStatus) UnsetProgress()`

UnsetProgress ensures that no value is present for Progress, not even an explicit nil
### GetTotalProgress

`func (o *InstanceRestoreStatus) GetTotalProgress() interface{}`

GetTotalProgress returns the TotalProgress field if non-nil, zero value otherwise.

### GetTotalProgressOk

`func (o *InstanceRestoreStatus) GetTotalProgressOk() (*interface{}, bool)`

GetTotalProgressOk returns a tuple with the TotalProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalProgress

`func (o *InstanceRestoreStatus) SetTotalProgress(v interface{})`

SetTotalProgress sets TotalProgress field to given value.

### HasTotalProgress

`func (o *InstanceRestoreStatus) HasTotalProgress() bool`

HasTotalProgress returns a boolean if a field has been set.

### SetTotalProgressNil

`func (o *InstanceRestoreStatus) SetTotalProgressNil(b bool)`

 SetTotalProgressNil sets the value for TotalProgress to be an explicit nil

### UnsetTotalProgress
`func (o *InstanceRestoreStatus) UnsetTotalProgress()`

UnsetTotalProgress ensures that no value is present for TotalProgress, not even an explicit nil
### GetHeading

`func (o *InstanceRestoreStatus) GetHeading() string`

GetHeading returns the Heading field if non-nil, zero value otherwise.

### GetHeadingOk

`func (o *InstanceRestoreStatus) GetHeadingOk() (*string, bool)`

GetHeadingOk returns a tuple with the Heading field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeading

`func (o *InstanceRestoreStatus) SetHeading(v string)`

SetHeading sets Heading field to given value.

### HasHeading

`func (o *InstanceRestoreStatus) HasHeading() bool`

HasHeading returns a boolean if a field has been set.

### GetDescription

`func (o *InstanceRestoreStatus) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *InstanceRestoreStatus) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *InstanceRestoreStatus) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *InstanceRestoreStatus) HasDescription() bool`

HasDescription returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


