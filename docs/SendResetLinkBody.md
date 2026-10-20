# SendResetLinkBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | Pointer to **string** | Email address to send the reset link to. | [optional] 

## Methods

### NewSendResetLinkBody

`func NewSendResetLinkBody() *SendResetLinkBody`

NewSendResetLinkBody instantiates a new SendResetLinkBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendResetLinkBodyWithDefaults

`func NewSendResetLinkBodyWithDefaults() *SendResetLinkBody`

NewSendResetLinkBodyWithDefaults instantiates a new SendResetLinkBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *SendResetLinkBody) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SendResetLinkBody) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SendResetLinkBody) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *SendResetLinkBody) HasEmail() bool`

HasEmail returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


