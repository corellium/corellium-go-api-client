# SharedSnapshotsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SharedWithUser** | [**[]SharedSnapshot**](SharedSnapshot.md) | Snapshots shared with the logged-in user. | 
**SharedByUser** | [**[]SharedSnapshot**](SharedSnapshot.md) | Snapshots shared by the logged-in user. | 

## Methods

### NewSharedSnapshotsResponse

`func NewSharedSnapshotsResponse(sharedWithUser []SharedSnapshot, sharedByUser []SharedSnapshot, ) *SharedSnapshotsResponse`

NewSharedSnapshotsResponse instantiates a new SharedSnapshotsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSharedSnapshotsResponseWithDefaults

`func NewSharedSnapshotsResponseWithDefaults() *SharedSnapshotsResponse`

NewSharedSnapshotsResponseWithDefaults instantiates a new SharedSnapshotsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSharedWithUser

`func (o *SharedSnapshotsResponse) GetSharedWithUser() []SharedSnapshot`

GetSharedWithUser returns the SharedWithUser field if non-nil, zero value otherwise.

### GetSharedWithUserOk

`func (o *SharedSnapshotsResponse) GetSharedWithUserOk() (*[]SharedSnapshot, bool)`

GetSharedWithUserOk returns a tuple with the SharedWithUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedWithUser

`func (o *SharedSnapshotsResponse) SetSharedWithUser(v []SharedSnapshot)`

SetSharedWithUser sets SharedWithUser field to given value.


### GetSharedByUser

`func (o *SharedSnapshotsResponse) GetSharedByUser() []SharedSnapshot`

GetSharedByUser returns the SharedByUser field if non-nil, zero value otherwise.

### GetSharedByUserOk

`func (o *SharedSnapshotsResponse) GetSharedByUserOk() (*[]SharedSnapshot, bool)`

GetSharedByUserOk returns a tuple with the SharedByUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedByUser

`func (o *SharedSnapshotsResponse) SetSharedByUser(v []SharedSnapshot)`

SetSharedByUser sets SharedByUser field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


