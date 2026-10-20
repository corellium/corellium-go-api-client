# ActivityV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **NullableString** | Unique identifier for the activity entry | [optional] 
**Domain** | Pointer to **NullableString** | Unique identifier for the domain | [optional] 
**Actor** | Pointer to **NullableString** | Unique identifier for the user | [optional] 
**Event** | Pointer to **NullableString** | Resource associated with the activity | [optional] 
**Outcome** | Pointer to **NullableString** | The outcome of the activity | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Related information that pertains to the activity | [optional] 
**CorelliumVersion** | Pointer to **NullableString** | The Corellium version this activity occurred in | [optional] 
**ProjectId** | Pointer to **NullableString** | Unique identifier for project if applicable | [optional] 
**InstanceId** | Pointer to **NullableString** | Unique identifier for instance if applicable | [optional] 
**CreatedAt** | Pointer to **NullableString** | Timestamp of when the activity was created | [optional] 
**UpdatedAt** | Pointer to **NullableString** | Timestamp of when the activity was last updated | [optional] 

## Methods

### NewActivityV1

`func NewActivityV1() *ActivityV1`

NewActivityV1 instantiates a new ActivityV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityV1WithDefaults

`func NewActivityV1WithDefaults() *ActivityV1`

NewActivityV1WithDefaults instantiates a new ActivityV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *ActivityV1) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ActivityV1) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ActivityV1) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *ActivityV1) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### SetIdentifierNil

`func (o *ActivityV1) SetIdentifierNil(b bool)`

 SetIdentifierNil sets the value for Identifier to be an explicit nil

### UnsetIdentifier
`func (o *ActivityV1) UnsetIdentifier()`

UnsetIdentifier ensures that no value is present for Identifier, not even an explicit nil
### GetDomain

`func (o *ActivityV1) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *ActivityV1) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *ActivityV1) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *ActivityV1) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *ActivityV1) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *ActivityV1) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetActor

`func (o *ActivityV1) GetActor() string`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *ActivityV1) GetActorOk() (*string, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *ActivityV1) SetActor(v string)`

SetActor sets Actor field to given value.

### HasActor

`func (o *ActivityV1) HasActor() bool`

HasActor returns a boolean if a field has been set.

### SetActorNil

`func (o *ActivityV1) SetActorNil(b bool)`

 SetActorNil sets the value for Actor to be an explicit nil

### UnsetActor
`func (o *ActivityV1) UnsetActor()`

UnsetActor ensures that no value is present for Actor, not even an explicit nil
### GetEvent

`func (o *ActivityV1) GetEvent() string`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *ActivityV1) GetEventOk() (*string, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *ActivityV1) SetEvent(v string)`

SetEvent sets Event field to given value.

### HasEvent

`func (o *ActivityV1) HasEvent() bool`

HasEvent returns a boolean if a field has been set.

### SetEventNil

`func (o *ActivityV1) SetEventNil(b bool)`

 SetEventNil sets the value for Event to be an explicit nil

### UnsetEvent
`func (o *ActivityV1) UnsetEvent()`

UnsetEvent ensures that no value is present for Event, not even an explicit nil
### GetOutcome

`func (o *ActivityV1) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *ActivityV1) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *ActivityV1) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.

### HasOutcome

`func (o *ActivityV1) HasOutcome() bool`

HasOutcome returns a boolean if a field has been set.

### SetOutcomeNil

`func (o *ActivityV1) SetOutcomeNil(b bool)`

 SetOutcomeNil sets the value for Outcome to be an explicit nil

### UnsetOutcome
`func (o *ActivityV1) UnsetOutcome()`

UnsetOutcome ensures that no value is present for Outcome, not even an explicit nil
### GetMetadata

`func (o *ActivityV1) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ActivityV1) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ActivityV1) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ActivityV1) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *ActivityV1) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *ActivityV1) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCorelliumVersion

`func (o *ActivityV1) GetCorelliumVersion() string`

GetCorelliumVersion returns the CorelliumVersion field if non-nil, zero value otherwise.

### GetCorelliumVersionOk

`func (o *ActivityV1) GetCorelliumVersionOk() (*string, bool)`

GetCorelliumVersionOk returns a tuple with the CorelliumVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorelliumVersion

`func (o *ActivityV1) SetCorelliumVersion(v string)`

SetCorelliumVersion sets CorelliumVersion field to given value.

### HasCorelliumVersion

`func (o *ActivityV1) HasCorelliumVersion() bool`

HasCorelliumVersion returns a boolean if a field has been set.

### SetCorelliumVersionNil

`func (o *ActivityV1) SetCorelliumVersionNil(b bool)`

 SetCorelliumVersionNil sets the value for CorelliumVersion to be an explicit nil

### UnsetCorelliumVersion
`func (o *ActivityV1) UnsetCorelliumVersion()`

UnsetCorelliumVersion ensures that no value is present for CorelliumVersion, not even an explicit nil
### GetProjectId

`func (o *ActivityV1) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ActivityV1) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ActivityV1) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *ActivityV1) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### SetProjectIdNil

`func (o *ActivityV1) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *ActivityV1) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetInstanceId

`func (o *ActivityV1) GetInstanceId() string`

GetInstanceId returns the InstanceId field if non-nil, zero value otherwise.

### GetInstanceIdOk

`func (o *ActivityV1) GetInstanceIdOk() (*string, bool)`

GetInstanceIdOk returns a tuple with the InstanceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceId

`func (o *ActivityV1) SetInstanceId(v string)`

SetInstanceId sets InstanceId field to given value.

### HasInstanceId

`func (o *ActivityV1) HasInstanceId() bool`

HasInstanceId returns a boolean if a field has been set.

### SetInstanceIdNil

`func (o *ActivityV1) SetInstanceIdNil(b bool)`

 SetInstanceIdNil sets the value for InstanceId to be an explicit nil

### UnsetInstanceId
`func (o *ActivityV1) UnsetInstanceId()`

UnsetInstanceId ensures that no value is present for InstanceId, not even an explicit nil
### GetCreatedAt

`func (o *ActivityV1) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ActivityV1) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ActivityV1) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ActivityV1) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *ActivityV1) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ActivityV1) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *ActivityV1) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ActivityV1) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ActivityV1) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ActivityV1) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *ActivityV1) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *ActivityV1) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


