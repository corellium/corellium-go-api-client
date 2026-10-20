# ActivityExportStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **NullableString** | Where the export task is. Poll until it is &#x60;complete&#x60;, then download the file. | 

## Methods

### NewActivityExportStatus

`func NewActivityExportStatus(status NullableString, ) *ActivityExportStatus`

NewActivityExportStatus instantiates a new ActivityExportStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityExportStatusWithDefaults

`func NewActivityExportStatusWithDefaults() *ActivityExportStatus`

NewActivityExportStatusWithDefaults instantiates a new ActivityExportStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ActivityExportStatus) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ActivityExportStatus) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ActivityExportStatus) SetStatus(v string)`

SetStatus sets Status field to given value.


### SetStatusNil

`func (o *ActivityExportStatus) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *ActivityExportStatus) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


