# CreateDomainWelcomeMessageBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** | The welcome message text (HTML allowed, will be sanitized) | 
**Enabled** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewCreateDomainWelcomeMessageBody

`func NewCreateDomainWelcomeMessageBody(message string, ) *CreateDomainWelcomeMessageBody`

NewCreateDomainWelcomeMessageBody instantiates a new CreateDomainWelcomeMessageBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDomainWelcomeMessageBodyWithDefaults

`func NewCreateDomainWelcomeMessageBodyWithDefaults() *CreateDomainWelcomeMessageBody`

NewCreateDomainWelcomeMessageBodyWithDefaults instantiates a new CreateDomainWelcomeMessageBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *CreateDomainWelcomeMessageBody) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateDomainWelcomeMessageBody) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateDomainWelcomeMessageBody) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetEnabled

`func (o *CreateDomainWelcomeMessageBody) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateDomainWelcomeMessageBody) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateDomainWelcomeMessageBody) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateDomainWelcomeMessageBody) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### SetEnabledNil

`func (o *CreateDomainWelcomeMessageBody) SetEnabledNil(b bool)`

 SetEnabledNil sets the value for Enabled to be an explicit nil

### UnsetEnabled
`func (o *CreateDomainWelcomeMessageBody) UnsetEnabled()`

UnsetEnabled ensures that no value is present for Enabled, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


