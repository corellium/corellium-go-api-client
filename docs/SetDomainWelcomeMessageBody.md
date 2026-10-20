# SetDomainWelcomeMessageBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** | The welcome message text (HTML allowed, will be sanitized). | 
**Enabled** | **bool** | Whether the welcome message is shown to users. | 

## Methods

### NewSetDomainWelcomeMessageBody

`func NewSetDomainWelcomeMessageBody(message string, enabled bool, ) *SetDomainWelcomeMessageBody`

NewSetDomainWelcomeMessageBody instantiates a new SetDomainWelcomeMessageBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetDomainWelcomeMessageBodyWithDefaults

`func NewSetDomainWelcomeMessageBodyWithDefaults() *SetDomainWelcomeMessageBody`

NewSetDomainWelcomeMessageBodyWithDefaults instantiates a new SetDomainWelcomeMessageBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *SetDomainWelcomeMessageBody) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *SetDomainWelcomeMessageBody) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *SetDomainWelcomeMessageBody) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetEnabled

`func (o *SetDomainWelcomeMessageBody) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SetDomainWelcomeMessageBody) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SetDomainWelcomeMessageBody) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


