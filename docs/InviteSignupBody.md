# InviteSignupBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InviteToken** | **string** | Invite token from the invitation email. | 
**Params** | [**InviteSignupBodyParams**](InviteSignupBodyParams.md) |  | 

## Methods

### NewInviteSignupBody

`func NewInviteSignupBody(inviteToken string, params InviteSignupBodyParams, ) *InviteSignupBody`

NewInviteSignupBody instantiates a new InviteSignupBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteSignupBodyWithDefaults

`func NewInviteSignupBodyWithDefaults() *InviteSignupBody`

NewInviteSignupBodyWithDefaults instantiates a new InviteSignupBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInviteToken

`func (o *InviteSignupBody) GetInviteToken() string`

GetInviteToken returns the InviteToken field if non-nil, zero value otherwise.

### GetInviteTokenOk

`func (o *InviteSignupBody) GetInviteTokenOk() (*string, bool)`

GetInviteTokenOk returns a tuple with the InviteToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInviteToken

`func (o *InviteSignupBody) SetInviteToken(v string)`

SetInviteToken sets InviteToken field to given value.


### GetParams

`func (o *InviteSignupBody) GetParams() InviteSignupBodyParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *InviteSignupBody) GetParamsOk() (*InviteSignupBodyParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *InviteSignupBody) SetParams(v InviteSignupBodyParams)`

SetParams sets Params field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


