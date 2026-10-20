# PatchDomainWelcomeMessageBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | The welcome message text (HTML allowed, will be sanitized). | [optional] 
**Enabled** | Pointer to **bool** | Whether the welcome message is shown to users. | [optional] 

## Methods

### NewPatchDomainWelcomeMessageBody

`func NewPatchDomainWelcomeMessageBody() *PatchDomainWelcomeMessageBody`

NewPatchDomainWelcomeMessageBody instantiates a new PatchDomainWelcomeMessageBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchDomainWelcomeMessageBodyWithDefaults

`func NewPatchDomainWelcomeMessageBodyWithDefaults() *PatchDomainWelcomeMessageBody`

NewPatchDomainWelcomeMessageBodyWithDefaults instantiates a new PatchDomainWelcomeMessageBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *PatchDomainWelcomeMessageBody) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PatchDomainWelcomeMessageBody) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PatchDomainWelcomeMessageBody) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *PatchDomainWelcomeMessageBody) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetEnabled

`func (o *PatchDomainWelcomeMessageBody) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *PatchDomainWelcomeMessageBody) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *PatchDomainWelcomeMessageBody) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *PatchDomainWelcomeMessageBody) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


