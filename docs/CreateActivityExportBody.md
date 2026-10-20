# CreateActivityExportBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Resource** | Pointer to **interface{}** | Resource equality or LHS prefix filter. Examples: &#x60;resource&#x3D;value&#x60;, &#x60;resource[startsWith]&#x3D;value&#x60;, and &#x60;resource[!startsWith]&#x3D;value&#x60;. | [optional] 
**Offset** | Pointer to **NullableFloat32** | Number of results to skip. | [optional] [default to 0]
**OrderBy** | Pointer to **string** | Field to sort by, for example &#x60;createdAt&#x60;. Prefix with &#x60;-&#x60; for newest or largest first. Defaults to &#x60;-createdAt&#x60; (newest first). | [optional] [default to "-createdAt"]
**InstanceId** | Pointer to **string** | Only activity about this device. | [optional] 
**ProjectId** | Pointer to **string** | Only activity in this project. | [optional] 
**Actor** | Pointer to **string** | Only activity performed by this user (user ID). | [optional] 
**Search** | Pointer to **string** | Free-text search. Applied last, as a loose match on the results that pass the other filters. | [optional] 
**To** | Pointer to **NullableTime** | Only activity at or before this time (ISO 8601). | [optional] 
**From** | Pointer to **NullableTime** | Only activity at or after this time (ISO 8601). | [optional] 

## Methods

### NewCreateActivityExportBody

`func NewCreateActivityExportBody() *CreateActivityExportBody`

NewCreateActivityExportBody instantiates a new CreateActivityExportBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateActivityExportBodyWithDefaults

`func NewCreateActivityExportBodyWithDefaults() *CreateActivityExportBody`

NewCreateActivityExportBodyWithDefaults instantiates a new CreateActivityExportBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResource

`func (o *CreateActivityExportBody) GetResource() interface{}`

GetResource returns the Resource field if non-nil, zero value otherwise.

### GetResourceOk

`func (o *CreateActivityExportBody) GetResourceOk() (*interface{}, bool)`

GetResourceOk returns a tuple with the Resource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResource

`func (o *CreateActivityExportBody) SetResource(v interface{})`

SetResource sets Resource field to given value.

### HasResource

`func (o *CreateActivityExportBody) HasResource() bool`

HasResource returns a boolean if a field has been set.

### SetResourceNil

`func (o *CreateActivityExportBody) SetResourceNil(b bool)`

 SetResourceNil sets the value for Resource to be an explicit nil

### UnsetResource
`func (o *CreateActivityExportBody) UnsetResource()`

UnsetResource ensures that no value is present for Resource, not even an explicit nil
### GetOffset

`func (o *CreateActivityExportBody) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *CreateActivityExportBody) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *CreateActivityExportBody) SetOffset(v float32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *CreateActivityExportBody) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### SetOffsetNil

`func (o *CreateActivityExportBody) SetOffsetNil(b bool)`

 SetOffsetNil sets the value for Offset to be an explicit nil

### UnsetOffset
`func (o *CreateActivityExportBody) UnsetOffset()`

UnsetOffset ensures that no value is present for Offset, not even an explicit nil
### GetOrderBy

`func (o *CreateActivityExportBody) GetOrderBy() string`

GetOrderBy returns the OrderBy field if non-nil, zero value otherwise.

### GetOrderByOk

`func (o *CreateActivityExportBody) GetOrderByOk() (*string, bool)`

GetOrderByOk returns a tuple with the OrderBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBy

`func (o *CreateActivityExportBody) SetOrderBy(v string)`

SetOrderBy sets OrderBy field to given value.

### HasOrderBy

`func (o *CreateActivityExportBody) HasOrderBy() bool`

HasOrderBy returns a boolean if a field has been set.

### GetInstanceId

`func (o *CreateActivityExportBody) GetInstanceId() string`

GetInstanceId returns the InstanceId field if non-nil, zero value otherwise.

### GetInstanceIdOk

`func (o *CreateActivityExportBody) GetInstanceIdOk() (*string, bool)`

GetInstanceIdOk returns a tuple with the InstanceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceId

`func (o *CreateActivityExportBody) SetInstanceId(v string)`

SetInstanceId sets InstanceId field to given value.

### HasInstanceId

`func (o *CreateActivityExportBody) HasInstanceId() bool`

HasInstanceId returns a boolean if a field has been set.

### GetProjectId

`func (o *CreateActivityExportBody) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateActivityExportBody) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateActivityExportBody) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateActivityExportBody) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetActor

`func (o *CreateActivityExportBody) GetActor() string`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *CreateActivityExportBody) GetActorOk() (*string, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *CreateActivityExportBody) SetActor(v string)`

SetActor sets Actor field to given value.

### HasActor

`func (o *CreateActivityExportBody) HasActor() bool`

HasActor returns a boolean if a field has been set.

### GetSearch

`func (o *CreateActivityExportBody) GetSearch() string`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *CreateActivityExportBody) GetSearchOk() (*string, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *CreateActivityExportBody) SetSearch(v string)`

SetSearch sets Search field to given value.

### HasSearch

`func (o *CreateActivityExportBody) HasSearch() bool`

HasSearch returns a boolean if a field has been set.

### GetTo

`func (o *CreateActivityExportBody) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *CreateActivityExportBody) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *CreateActivityExportBody) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *CreateActivityExportBody) HasTo() bool`

HasTo returns a boolean if a field has been set.

### SetToNil

`func (o *CreateActivityExportBody) SetToNil(b bool)`

 SetToNil sets the value for To to be an explicit nil

### UnsetTo
`func (o *CreateActivityExportBody) UnsetTo()`

UnsetTo ensures that no value is present for To, not even an explicit nil
### GetFrom

`func (o *CreateActivityExportBody) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *CreateActivityExportBody) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *CreateActivityExportBody) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *CreateActivityExportBody) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### SetFromNil

`func (o *CreateActivityExportBody) SetFromNil(b bool)`

 SetFromNil sets the value for From to be an explicit nil

### UnsetFrom
`func (o *CreateActivityExportBody) UnsetFrom()`

UnsetFrom ensures that no value is present for From, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


