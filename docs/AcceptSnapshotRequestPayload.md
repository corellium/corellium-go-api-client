# AcceptSnapshotRequestPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessCode** | **string** | Access code of the shared snapshot. | 
**Password** | Pointer to **NullableString** | Password of the shared snapshot. Required when it was shared with sharing type passwordPublicLink. | [optional] 

## Methods

### NewAcceptSnapshotRequestPayload

`func NewAcceptSnapshotRequestPayload(accessCode string, ) *AcceptSnapshotRequestPayload`

NewAcceptSnapshotRequestPayload instantiates a new AcceptSnapshotRequestPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAcceptSnapshotRequestPayloadWithDefaults

`func NewAcceptSnapshotRequestPayloadWithDefaults() *AcceptSnapshotRequestPayload`

NewAcceptSnapshotRequestPayloadWithDefaults instantiates a new AcceptSnapshotRequestPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessCode

`func (o *AcceptSnapshotRequestPayload) GetAccessCode() string`

GetAccessCode returns the AccessCode field if non-nil, zero value otherwise.

### GetAccessCodeOk

`func (o *AcceptSnapshotRequestPayload) GetAccessCodeOk() (*string, bool)`

GetAccessCodeOk returns a tuple with the AccessCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessCode

`func (o *AcceptSnapshotRequestPayload) SetAccessCode(v string)`

SetAccessCode sets AccessCode field to given value.


### GetPassword

`func (o *AcceptSnapshotRequestPayload) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *AcceptSnapshotRequestPayload) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *AcceptSnapshotRequestPayload) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *AcceptSnapshotRequestPayload) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### SetPasswordNil

`func (o *AcceptSnapshotRequestPayload) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *AcceptSnapshotRequestPayload) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


