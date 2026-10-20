# TextInputRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | Text to type. | 
**KeyDuration** | Pointer to **float32** | How long to take to type each key, in milliseconds. Defaults to ~150ms per key downstream when omitted. | [optional] 

## Methods

### NewTextInputRequest

`func NewTextInputRequest(text string, ) *TextInputRequest`

NewTextInputRequest instantiates a new TextInputRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTextInputRequestWithDefaults

`func NewTextInputRequestWithDefaults() *TextInputRequest`

NewTextInputRequestWithDefaults instantiates a new TextInputRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *TextInputRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *TextInputRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *TextInputRequest) SetText(v string)`

SetText sets Text field to given value.


### GetKeyDuration

`func (o *TextInputRequest) GetKeyDuration() float32`

GetKeyDuration returns the KeyDuration field if non-nil, zero value otherwise.

### GetKeyDurationOk

`func (o *TextInputRequest) GetKeyDurationOk() (*float32, bool)`

GetKeyDurationOk returns a tuple with the KeyDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyDuration

`func (o *TextInputRequest) SetKeyDuration(v float32)`

SetKeyDuration sets KeyDuration field to given value.

### HasKeyDuration

`func (o *TextInputRequest) HasKeyDuration() bool`

HasKeyDuration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


