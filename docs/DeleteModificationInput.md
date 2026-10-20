# DeleteModificationInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CheckId** | **string** | Identifier of the check whose modification is removed. | 
**Property** | **string** | Property of the check whose modification is removed: \&quot;outcome\&quot;, \&quot;severity\&quot;, or \&quot;evidence_&lt;index&gt;\&quot;. | 

## Methods

### NewDeleteModificationInput

`func NewDeleteModificationInput(checkId string, property string, ) *DeleteModificationInput`

NewDeleteModificationInput instantiates a new DeleteModificationInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteModificationInputWithDefaults

`func NewDeleteModificationInputWithDefaults() *DeleteModificationInput`

NewDeleteModificationInputWithDefaults instantiates a new DeleteModificationInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCheckId

`func (o *DeleteModificationInput) GetCheckId() string`

GetCheckId returns the CheckId field if non-nil, zero value otherwise.

### GetCheckIdOk

`func (o *DeleteModificationInput) GetCheckIdOk() (*string, bool)`

GetCheckIdOk returns a tuple with the CheckId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckId

`func (o *DeleteModificationInput) SetCheckId(v string)`

SetCheckId sets CheckId field to given value.


### GetProperty

`func (o *DeleteModificationInput) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *DeleteModificationInput) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *DeleteModificationInput) SetProperty(v string)`

SetProperty sets Property field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


