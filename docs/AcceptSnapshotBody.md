# AcceptSnapshotBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessCode** | **string** | The access code the snapshot&#39;s owner gave you (shown in &#x60;sharing.accessCode&#x60; on their snapshot). | 
**Password** | Pointer to **NullableString** | Password of the shared snapshot, as set when it was shared. Required when the snapshot was shared with sharing type passwordPublicLink. | [optional] 

## Methods

### NewAcceptSnapshotBody

`func NewAcceptSnapshotBody(accessCode string, ) *AcceptSnapshotBody`

NewAcceptSnapshotBody instantiates a new AcceptSnapshotBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAcceptSnapshotBodyWithDefaults

`func NewAcceptSnapshotBodyWithDefaults() *AcceptSnapshotBody`

NewAcceptSnapshotBodyWithDefaults instantiates a new AcceptSnapshotBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessCode

`func (o *AcceptSnapshotBody) GetAccessCode() string`

GetAccessCode returns the AccessCode field if non-nil, zero value otherwise.

### GetAccessCodeOk

`func (o *AcceptSnapshotBody) GetAccessCodeOk() (*string, bool)`

GetAccessCodeOk returns a tuple with the AccessCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessCode

`func (o *AcceptSnapshotBody) SetAccessCode(v string)`

SetAccessCode sets AccessCode field to given value.


### GetPassword

`func (o *AcceptSnapshotBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *AcceptSnapshotBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *AcceptSnapshotBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *AcceptSnapshotBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### SetPasswordNil

`func (o *AcceptSnapshotBody) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *AcceptSnapshotBody) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


