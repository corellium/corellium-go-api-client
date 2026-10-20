# Activity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Unique identifier for the activity entry. | 
**Domain** | **string** | Unique identifier for the domain. | 
**Actor** | **string** | Unique identifier for the user. | 
**Event** | **string** | Resource associated with the activity. | 
**Outcome** | **string** | The outcome of the activity. | 
**Metadata** | **map[string]interface{}** | Related information that pertains to the activity. | 
**CorelliumVersion** | **NullableString** | The Corellium version this activity occurred in. | 
**ProjectId** | **NullableString** | Unique identifier for project if applicable. | 
**InstanceId** | **NullableString** | Unique identifier for instance if applicable. | 
**CreatedAt** | **time.Time** | Timestamp of when the activity was created. | 
**UpdatedAt** | **time.Time** | Timestamp of when the activity was last updated. | 

## Methods

### NewActivity

`func NewActivity(identifier string, domain string, actor string, event string, outcome string, metadata map[string]interface{}, corelliumVersion NullableString, projectId NullableString, instanceId NullableString, createdAt time.Time, updatedAt time.Time, ) *Activity`

NewActivity instantiates a new Activity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityWithDefaults

`func NewActivityWithDefaults() *Activity`

NewActivityWithDefaults instantiates a new Activity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *Activity) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *Activity) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *Activity) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetDomain

`func (o *Activity) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *Activity) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *Activity) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetActor

`func (o *Activity) GetActor() string`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *Activity) GetActorOk() (*string, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *Activity) SetActor(v string)`

SetActor sets Actor field to given value.


### GetEvent

`func (o *Activity) GetEvent() string`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *Activity) GetEventOk() (*string, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *Activity) SetEvent(v string)`

SetEvent sets Event field to given value.


### GetOutcome

`func (o *Activity) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *Activity) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *Activity) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.


### GetMetadata

`func (o *Activity) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Activity) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Activity) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *Activity) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *Activity) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCorelliumVersion

`func (o *Activity) GetCorelliumVersion() string`

GetCorelliumVersion returns the CorelliumVersion field if non-nil, zero value otherwise.

### GetCorelliumVersionOk

`func (o *Activity) GetCorelliumVersionOk() (*string, bool)`

GetCorelliumVersionOk returns a tuple with the CorelliumVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorelliumVersion

`func (o *Activity) SetCorelliumVersion(v string)`

SetCorelliumVersion sets CorelliumVersion field to given value.


### SetCorelliumVersionNil

`func (o *Activity) SetCorelliumVersionNil(b bool)`

 SetCorelliumVersionNil sets the value for CorelliumVersion to be an explicit nil

### UnsetCorelliumVersion
`func (o *Activity) UnsetCorelliumVersion()`

UnsetCorelliumVersion ensures that no value is present for CorelliumVersion, not even an explicit nil
### GetProjectId

`func (o *Activity) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Activity) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Activity) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *Activity) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *Activity) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetInstanceId

`func (o *Activity) GetInstanceId() string`

GetInstanceId returns the InstanceId field if non-nil, zero value otherwise.

### GetInstanceIdOk

`func (o *Activity) GetInstanceIdOk() (*string, bool)`

GetInstanceIdOk returns a tuple with the InstanceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceId

`func (o *Activity) SetInstanceId(v string)`

SetInstanceId sets InstanceId field to given value.


### SetInstanceIdNil

`func (o *Activity) SetInstanceIdNil(b bool)`

 SetInstanceIdNil sets the value for InstanceId to be an explicit nil

### UnsetInstanceId
`func (o *Activity) UnsetInstanceId()`

UnsetInstanceId ensures that no value is present for InstanceId, not even an explicit nil
### GetCreatedAt

`func (o *Activity) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Activity) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Activity) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Activity) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Activity) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Activity) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


