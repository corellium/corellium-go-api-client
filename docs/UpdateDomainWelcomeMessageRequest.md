# UpdateDomainWelcomeMessageRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **NullableString** | The welcome message text (HTML allowed, will be sanitized) | [optional] 
**Enabled** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewUpdateDomainWelcomeMessageRequest

`func NewUpdateDomainWelcomeMessageRequest() *UpdateDomainWelcomeMessageRequest`

NewUpdateDomainWelcomeMessageRequest instantiates a new UpdateDomainWelcomeMessageRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDomainWelcomeMessageRequestWithDefaults

`func NewUpdateDomainWelcomeMessageRequestWithDefaults() *UpdateDomainWelcomeMessageRequest`

NewUpdateDomainWelcomeMessageRequestWithDefaults instantiates a new UpdateDomainWelcomeMessageRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *UpdateDomainWelcomeMessageRequest) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *UpdateDomainWelcomeMessageRequest) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *UpdateDomainWelcomeMessageRequest) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *UpdateDomainWelcomeMessageRequest) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *UpdateDomainWelcomeMessageRequest) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *UpdateDomainWelcomeMessageRequest) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetEnabled

`func (o *UpdateDomainWelcomeMessageRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateDomainWelcomeMessageRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateDomainWelcomeMessageRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdateDomainWelcomeMessageRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### SetEnabledNil

`func (o *UpdateDomainWelcomeMessageRequest) SetEnabledNil(b bool)`

 SetEnabledNil sets the value for Enabled to be an explicit nil

### UnsetEnabled
`func (o *UpdateDomainWelcomeMessageRequest) UnsetEnabled()`

UnsetEnabled ensures that no value is present for Enabled, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


