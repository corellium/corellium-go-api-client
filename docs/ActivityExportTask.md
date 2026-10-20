# ActivityExportTask

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Task identifier in the form &#x60;activity-export/&lt;UUID&gt;&#x60;. | 
**ScheduledAt** | **time.Time** | Timestamp of when the task is scheduled to execute. | 
**Status** | **NullableString** | Where the export task is. Poll until it is &#x60;complete&#x60;, then download the file. | 
**Args** | **map[string]interface{}** | Arguments passed to the task. | 
**CreatedAt** | **time.Time** | Timestamp of when the task was created. | 
**UpdatedAt** | **time.Time** | Timestamp of when the task was last updated. | 

## Methods

### NewActivityExportTask

`func NewActivityExportTask(identifier string, scheduledAt time.Time, status NullableString, args map[string]interface{}, createdAt time.Time, updatedAt time.Time, ) *ActivityExportTask`

NewActivityExportTask instantiates a new ActivityExportTask object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityExportTaskWithDefaults

`func NewActivityExportTaskWithDefaults() *ActivityExportTask`

NewActivityExportTaskWithDefaults instantiates a new ActivityExportTask object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *ActivityExportTask) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ActivityExportTask) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ActivityExportTask) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetScheduledAt

`func (o *ActivityExportTask) GetScheduledAt() time.Time`

GetScheduledAt returns the ScheduledAt field if non-nil, zero value otherwise.

### GetScheduledAtOk

`func (o *ActivityExportTask) GetScheduledAtOk() (*time.Time, bool)`

GetScheduledAtOk returns a tuple with the ScheduledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledAt

`func (o *ActivityExportTask) SetScheduledAt(v time.Time)`

SetScheduledAt sets ScheduledAt field to given value.


### GetStatus

`func (o *ActivityExportTask) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ActivityExportTask) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ActivityExportTask) SetStatus(v string)`

SetStatus sets Status field to given value.


### SetStatusNil

`func (o *ActivityExportTask) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *ActivityExportTask) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetArgs

`func (o *ActivityExportTask) GetArgs() map[string]interface{}`

GetArgs returns the Args field if non-nil, zero value otherwise.

### GetArgsOk

`func (o *ActivityExportTask) GetArgsOk() (*map[string]interface{}, bool)`

GetArgsOk returns a tuple with the Args field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArgs

`func (o *ActivityExportTask) SetArgs(v map[string]interface{})`

SetArgs sets Args field to given value.


### GetCreatedAt

`func (o *ActivityExportTask) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ActivityExportTask) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ActivityExportTask) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ActivityExportTask) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ActivityExportTask) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ActivityExportTask) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


