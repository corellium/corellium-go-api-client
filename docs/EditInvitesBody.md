# EditInvitesBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ids** | **[]string** | Invite IDs to operate on. | 
**Changes** | [**EditInvitesBodyChanges**](EditInvitesBodyChanges.md) |  | 

## Methods

### NewEditInvitesBody

`func NewEditInvitesBody(ids []string, changes EditInvitesBodyChanges, ) *EditInvitesBody`

NewEditInvitesBody instantiates a new EditInvitesBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditInvitesBodyWithDefaults

`func NewEditInvitesBodyWithDefaults() *EditInvitesBody`

NewEditInvitesBodyWithDefaults instantiates a new EditInvitesBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIds

`func (o *EditInvitesBody) GetIds() []string`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *EditInvitesBody) GetIdsOk() (*[]string, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *EditInvitesBody) SetIds(v []string)`

SetIds sets Ids field to given value.


### GetChanges

`func (o *EditInvitesBody) GetChanges() EditInvitesBodyChanges`

GetChanges returns the Changes field if non-nil, zero value otherwise.

### GetChangesOk

`func (o *EditInvitesBody) GetChangesOk() (*EditInvitesBodyChanges, bool)`

GetChangesOk returns a tuple with the Changes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChanges

`func (o *EditInvitesBody) SetChanges(v EditInvitesBodyChanges)`

SetChanges sets Changes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


