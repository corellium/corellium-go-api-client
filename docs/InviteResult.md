# InviteResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Invite** | Pointer to [**Invitation**](Invitation.md) | The created invite, when successful. | [optional] 
**Error** | Pointer to [**InviteResultError**](InviteResultError.md) |  | [optional] 

## Methods

### NewInviteResult

`func NewInviteResult() *InviteResult`

NewInviteResult instantiates a new InviteResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteResultWithDefaults

`func NewInviteResultWithDefaults() *InviteResult`

NewInviteResultWithDefaults instantiates a new InviteResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInvite

`func (o *InviteResult) GetInvite() Invitation`

GetInvite returns the Invite field if non-nil, zero value otherwise.

### GetInviteOk

`func (o *InviteResult) GetInviteOk() (*Invitation, bool)`

GetInviteOk returns a tuple with the Invite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvite

`func (o *InviteResult) SetInvite(v Invitation)`

SetInvite sets Invite field to given value.

### HasInvite

`func (o *InviteResult) HasInvite() bool`

HasInvite returns a boolean if a field has been set.

### GetError

`func (o *InviteResult) GetError() InviteResultError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *InviteResult) GetErrorOk() (*InviteResultError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *InviteResult) SetError(v InviteResultError)`

SetError sets Error field to given value.

### HasError

`func (o *InviteResult) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


