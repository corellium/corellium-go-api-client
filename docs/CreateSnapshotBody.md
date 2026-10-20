# CreateSnapshotBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | A name to recognise the snapshot by later, for example what state the device was in. | 

## Methods

### NewCreateSnapshotBody

`func NewCreateSnapshotBody(name string, ) *CreateSnapshotBody`

NewCreateSnapshotBody instantiates a new CreateSnapshotBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateSnapshotBodyWithDefaults

`func NewCreateSnapshotBodyWithDefaults() *CreateSnapshotBody`

NewCreateSnapshotBodyWithDefaults instantiates a new CreateSnapshotBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateSnapshotBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateSnapshotBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateSnapshotBody) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


