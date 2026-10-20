# SnapshotRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **NullableFloat32** | Number of entries to return, defaults to 100 | [optional] 
**Offset** | Pointer to **NullableFloat32** | Number of rows to skip, defaults to 0 | [optional] 
**Springboard** | Pointer to **NullableBool** | Denotes whether snapshot was a springboard snapshot | [optional] 
**Live** | Pointer to **NullableBool** | Denotes whether snapshot was a live snapshot | [optional] 
**Fresh** | Pointer to **NullableBool** | Denotes whether snapshot was created immediately after the device was restored | [optional] 
**DeviceName** | Pointer to **NullableString** | Name of device | [optional] 
**Task** | Pointer to **NullableString** | Task being executed on snapshot | [optional] 
**To** | Pointer to **NullableString** | Date to filter to, keyed off of createdAt | [optional] 
**From** | Pointer to **NullableString** | Date to filter from, keyed off of createdAt | [optional] 
**OrderBy** | Pointer to **NullableString** | Sorting order (&#39;-createdAt&#39; or &#39;createdAt&#39;), defaults to -createdAt | [optional] 
**Search** | Pointer to **NullableString** | Last filter applied and searches on snapshot / associated instance name and snapshot / instance id | [optional] 

## Methods

### NewSnapshotRequest

`func NewSnapshotRequest() *SnapshotRequest`

NewSnapshotRequest instantiates a new SnapshotRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnapshotRequestWithDefaults

`func NewSnapshotRequestWithDefaults() *SnapshotRequest`

NewSnapshotRequestWithDefaults instantiates a new SnapshotRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *SnapshotRequest) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *SnapshotRequest) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *SnapshotRequest) SetLimit(v float32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *SnapshotRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### SetLimitNil

`func (o *SnapshotRequest) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *SnapshotRequest) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetOffset

`func (o *SnapshotRequest) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *SnapshotRequest) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *SnapshotRequest) SetOffset(v float32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *SnapshotRequest) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### SetOffsetNil

`func (o *SnapshotRequest) SetOffsetNil(b bool)`

 SetOffsetNil sets the value for Offset to be an explicit nil

### UnsetOffset
`func (o *SnapshotRequest) UnsetOffset()`

UnsetOffset ensures that no value is present for Offset, not even an explicit nil
### GetSpringboard

`func (o *SnapshotRequest) GetSpringboard() bool`

GetSpringboard returns the Springboard field if non-nil, zero value otherwise.

### GetSpringboardOk

`func (o *SnapshotRequest) GetSpringboardOk() (*bool, bool)`

GetSpringboardOk returns a tuple with the Springboard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpringboard

`func (o *SnapshotRequest) SetSpringboard(v bool)`

SetSpringboard sets Springboard field to given value.

### HasSpringboard

`func (o *SnapshotRequest) HasSpringboard() bool`

HasSpringboard returns a boolean if a field has been set.

### SetSpringboardNil

`func (o *SnapshotRequest) SetSpringboardNil(b bool)`

 SetSpringboardNil sets the value for Springboard to be an explicit nil

### UnsetSpringboard
`func (o *SnapshotRequest) UnsetSpringboard()`

UnsetSpringboard ensures that no value is present for Springboard, not even an explicit nil
### GetLive

`func (o *SnapshotRequest) GetLive() bool`

GetLive returns the Live field if non-nil, zero value otherwise.

### GetLiveOk

`func (o *SnapshotRequest) GetLiveOk() (*bool, bool)`

GetLiveOk returns a tuple with the Live field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLive

`func (o *SnapshotRequest) SetLive(v bool)`

SetLive sets Live field to given value.

### HasLive

`func (o *SnapshotRequest) HasLive() bool`

HasLive returns a boolean if a field has been set.

### SetLiveNil

`func (o *SnapshotRequest) SetLiveNil(b bool)`

 SetLiveNil sets the value for Live to be an explicit nil

### UnsetLive
`func (o *SnapshotRequest) UnsetLive()`

UnsetLive ensures that no value is present for Live, not even an explicit nil
### GetFresh

`func (o *SnapshotRequest) GetFresh() bool`

GetFresh returns the Fresh field if non-nil, zero value otherwise.

### GetFreshOk

`func (o *SnapshotRequest) GetFreshOk() (*bool, bool)`

GetFreshOk returns a tuple with the Fresh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFresh

`func (o *SnapshotRequest) SetFresh(v bool)`

SetFresh sets Fresh field to given value.

### HasFresh

`func (o *SnapshotRequest) HasFresh() bool`

HasFresh returns a boolean if a field has been set.

### SetFreshNil

`func (o *SnapshotRequest) SetFreshNil(b bool)`

 SetFreshNil sets the value for Fresh to be an explicit nil

### UnsetFresh
`func (o *SnapshotRequest) UnsetFresh()`

UnsetFresh ensures that no value is present for Fresh, not even an explicit nil
### GetDeviceName

`func (o *SnapshotRequest) GetDeviceName() string`

GetDeviceName returns the DeviceName field if non-nil, zero value otherwise.

### GetDeviceNameOk

`func (o *SnapshotRequest) GetDeviceNameOk() (*string, bool)`

GetDeviceNameOk returns a tuple with the DeviceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceName

`func (o *SnapshotRequest) SetDeviceName(v string)`

SetDeviceName sets DeviceName field to given value.

### HasDeviceName

`func (o *SnapshotRequest) HasDeviceName() bool`

HasDeviceName returns a boolean if a field has been set.

### SetDeviceNameNil

`func (o *SnapshotRequest) SetDeviceNameNil(b bool)`

 SetDeviceNameNil sets the value for DeviceName to be an explicit nil

### UnsetDeviceName
`func (o *SnapshotRequest) UnsetDeviceName()`

UnsetDeviceName ensures that no value is present for DeviceName, not even an explicit nil
### GetTask

`func (o *SnapshotRequest) GetTask() string`

GetTask returns the Task field if non-nil, zero value otherwise.

### GetTaskOk

`func (o *SnapshotRequest) GetTaskOk() (*string, bool)`

GetTaskOk returns a tuple with the Task field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTask

`func (o *SnapshotRequest) SetTask(v string)`

SetTask sets Task field to given value.

### HasTask

`func (o *SnapshotRequest) HasTask() bool`

HasTask returns a boolean if a field has been set.

### SetTaskNil

`func (o *SnapshotRequest) SetTaskNil(b bool)`

 SetTaskNil sets the value for Task to be an explicit nil

### UnsetTask
`func (o *SnapshotRequest) UnsetTask()`

UnsetTask ensures that no value is present for Task, not even an explicit nil
### GetTo

`func (o *SnapshotRequest) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SnapshotRequest) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SnapshotRequest) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SnapshotRequest) HasTo() bool`

HasTo returns a boolean if a field has been set.

### SetToNil

`func (o *SnapshotRequest) SetToNil(b bool)`

 SetToNil sets the value for To to be an explicit nil

### UnsetTo
`func (o *SnapshotRequest) UnsetTo()`

UnsetTo ensures that no value is present for To, not even an explicit nil
### GetFrom

`func (o *SnapshotRequest) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SnapshotRequest) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SnapshotRequest) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SnapshotRequest) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### SetFromNil

`func (o *SnapshotRequest) SetFromNil(b bool)`

 SetFromNil sets the value for From to be an explicit nil

### UnsetFrom
`func (o *SnapshotRequest) UnsetFrom()`

UnsetFrom ensures that no value is present for From, not even an explicit nil
### GetOrderBy

`func (o *SnapshotRequest) GetOrderBy() string`

GetOrderBy returns the OrderBy field if non-nil, zero value otherwise.

### GetOrderByOk

`func (o *SnapshotRequest) GetOrderByOk() (*string, bool)`

GetOrderByOk returns a tuple with the OrderBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBy

`func (o *SnapshotRequest) SetOrderBy(v string)`

SetOrderBy sets OrderBy field to given value.

### HasOrderBy

`func (o *SnapshotRequest) HasOrderBy() bool`

HasOrderBy returns a boolean if a field has been set.

### SetOrderByNil

`func (o *SnapshotRequest) SetOrderByNil(b bool)`

 SetOrderByNil sets the value for OrderBy to be an explicit nil

### UnsetOrderBy
`func (o *SnapshotRequest) UnsetOrderBy()`

UnsetOrderBy ensures that no value is present for OrderBy, not even an explicit nil
### GetSearch

`func (o *SnapshotRequest) GetSearch() string`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *SnapshotRequest) GetSearchOk() (*string, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *SnapshotRequest) SetSearch(v string)`

SetSearch sets Search field to given value.

### HasSearch

`func (o *SnapshotRequest) HasSearch() bool`

HasSearch returns a boolean if a field has been set.

### SetSearchNil

`func (o *SnapshotRequest) SetSearchNil(b bool)`

 SetSearchNil sets the value for Search to be an explicit nil

### UnsetSearch
`func (o *SnapshotRequest) UnsetSearch()`

UnsetSearch ensures that no value is present for Search, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


