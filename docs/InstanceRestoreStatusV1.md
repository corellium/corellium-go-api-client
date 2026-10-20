# InstanceRestoreStatusV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **NullableString** | Restore type: 0&#x3D;Not Restore, 1&#x3D;Restore, 2&#x3D;CloneFromSnapshot | [optional] 
**Stage** | Pointer to **NullableString** | Restore stage: download-images, prepare, boot, start, extracting, asr, flashing, done | [optional] 
**Progress** | Pointer to **NullableFloat32** | Stage progress (0-100) | [optional] 
**TotalProgress** | Pointer to **NullableFloat32** | Total restore progress (0-100) | [optional] 
**Heading** | Pointer to **NullableString** | Current heading for progress modal | [optional] 
**Description** | Pointer to **NullableString** | Current description for progress modal | [optional] 

## Methods

### NewInstanceRestoreStatusV1

`func NewInstanceRestoreStatusV1() *InstanceRestoreStatusV1`

NewInstanceRestoreStatusV1 instantiates a new InstanceRestoreStatusV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceRestoreStatusV1WithDefaults

`func NewInstanceRestoreStatusV1WithDefaults() *InstanceRestoreStatusV1`

NewInstanceRestoreStatusV1WithDefaults instantiates a new InstanceRestoreStatusV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *InstanceRestoreStatusV1) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InstanceRestoreStatusV1) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InstanceRestoreStatusV1) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InstanceRestoreStatusV1) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *InstanceRestoreStatusV1) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *InstanceRestoreStatusV1) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetStage

`func (o *InstanceRestoreStatusV1) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *InstanceRestoreStatusV1) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *InstanceRestoreStatusV1) SetStage(v string)`

SetStage sets Stage field to given value.

### HasStage

`func (o *InstanceRestoreStatusV1) HasStage() bool`

HasStage returns a boolean if a field has been set.

### SetStageNil

`func (o *InstanceRestoreStatusV1) SetStageNil(b bool)`

 SetStageNil sets the value for Stage to be an explicit nil

### UnsetStage
`func (o *InstanceRestoreStatusV1) UnsetStage()`

UnsetStage ensures that no value is present for Stage, not even an explicit nil
### GetProgress

`func (o *InstanceRestoreStatusV1) GetProgress() float32`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *InstanceRestoreStatusV1) GetProgressOk() (*float32, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *InstanceRestoreStatusV1) SetProgress(v float32)`

SetProgress sets Progress field to given value.

### HasProgress

`func (o *InstanceRestoreStatusV1) HasProgress() bool`

HasProgress returns a boolean if a field has been set.

### SetProgressNil

`func (o *InstanceRestoreStatusV1) SetProgressNil(b bool)`

 SetProgressNil sets the value for Progress to be an explicit nil

### UnsetProgress
`func (o *InstanceRestoreStatusV1) UnsetProgress()`

UnsetProgress ensures that no value is present for Progress, not even an explicit nil
### GetTotalProgress

`func (o *InstanceRestoreStatusV1) GetTotalProgress() float32`

GetTotalProgress returns the TotalProgress field if non-nil, zero value otherwise.

### GetTotalProgressOk

`func (o *InstanceRestoreStatusV1) GetTotalProgressOk() (*float32, bool)`

GetTotalProgressOk returns a tuple with the TotalProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalProgress

`func (o *InstanceRestoreStatusV1) SetTotalProgress(v float32)`

SetTotalProgress sets TotalProgress field to given value.

### HasTotalProgress

`func (o *InstanceRestoreStatusV1) HasTotalProgress() bool`

HasTotalProgress returns a boolean if a field has been set.

### SetTotalProgressNil

`func (o *InstanceRestoreStatusV1) SetTotalProgressNil(b bool)`

 SetTotalProgressNil sets the value for TotalProgress to be an explicit nil

### UnsetTotalProgress
`func (o *InstanceRestoreStatusV1) UnsetTotalProgress()`

UnsetTotalProgress ensures that no value is present for TotalProgress, not even an explicit nil
### GetHeading

`func (o *InstanceRestoreStatusV1) GetHeading() string`

GetHeading returns the Heading field if non-nil, zero value otherwise.

### GetHeadingOk

`func (o *InstanceRestoreStatusV1) GetHeadingOk() (*string, bool)`

GetHeadingOk returns a tuple with the Heading field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeading

`func (o *InstanceRestoreStatusV1) SetHeading(v string)`

SetHeading sets Heading field to given value.

### HasHeading

`func (o *InstanceRestoreStatusV1) HasHeading() bool`

HasHeading returns a boolean if a field has been set.

### SetHeadingNil

`func (o *InstanceRestoreStatusV1) SetHeadingNil(b bool)`

 SetHeadingNil sets the value for Heading to be an explicit nil

### UnsetHeading
`func (o *InstanceRestoreStatusV1) UnsetHeading()`

UnsetHeading ensures that no value is present for Heading, not even an explicit nil
### GetDescription

`func (o *InstanceRestoreStatusV1) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *InstanceRestoreStatusV1) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *InstanceRestoreStatusV1) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *InstanceRestoreStatusV1) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *InstanceRestoreStatusV1) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *InstanceRestoreStatusV1) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


