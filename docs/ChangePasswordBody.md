# ChangePasswordBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**User** | **string** | User identifier. | 
**OldPassword** | **string** | Current password. | 
**NewPassword** | **string** | New password. | 

## Methods

### NewChangePasswordBody

`func NewChangePasswordBody(user string, oldPassword string, newPassword string, ) *ChangePasswordBody`

NewChangePasswordBody instantiates a new ChangePasswordBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangePasswordBodyWithDefaults

`func NewChangePasswordBodyWithDefaults() *ChangePasswordBody`

NewChangePasswordBodyWithDefaults instantiates a new ChangePasswordBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUser

`func (o *ChangePasswordBody) GetUser() string`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *ChangePasswordBody) GetUserOk() (*string, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *ChangePasswordBody) SetUser(v string)`

SetUser sets User field to given value.


### GetOldPassword

`func (o *ChangePasswordBody) GetOldPassword() string`

GetOldPassword returns the OldPassword field if non-nil, zero value otherwise.

### GetOldPasswordOk

`func (o *ChangePasswordBody) GetOldPasswordOk() (*string, bool)`

GetOldPasswordOk returns a tuple with the OldPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldPassword

`func (o *ChangePasswordBody) SetOldPassword(v string)`

SetOldPassword sets OldPassword field to given value.


### GetNewPassword

`func (o *ChangePasswordBody) GetNewPassword() string`

GetNewPassword returns the NewPassword field if non-nil, zero value otherwise.

### GetNewPasswordOk

`func (o *ChangePasswordBody) GetNewPasswordOk() (*string, bool)`

GetNewPasswordOk returns a tuple with the NewPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPassword

`func (o *ChangePasswordBody) SetNewPassword(v string)`

SetNewPassword sets NewPassword field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


