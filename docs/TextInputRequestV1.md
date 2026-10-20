# TextInputRequestV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Required** | **string** | text to type | 
**KeyDuration** | Pointer to **NullableFloat32** | How long to take to type each key.  150ms if not defined. | [optional] 

## Methods

### NewTextInputRequestV1

`func NewTextInputRequestV1(required string, ) *TextInputRequestV1`

NewTextInputRequestV1 instantiates a new TextInputRequestV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTextInputRequestV1WithDefaults

`func NewTextInputRequestV1WithDefaults() *TextInputRequestV1`

NewTextInputRequestV1WithDefaults instantiates a new TextInputRequestV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequired

`func (o *TextInputRequestV1) GetRequired() string`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *TextInputRequestV1) GetRequiredOk() (*string, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *TextInputRequestV1) SetRequired(v string)`

SetRequired sets Required field to given value.


### GetKeyDuration

`func (o *TextInputRequestV1) GetKeyDuration() float32`

GetKeyDuration returns the KeyDuration field if non-nil, zero value otherwise.

### GetKeyDurationOk

`func (o *TextInputRequestV1) GetKeyDurationOk() (*float32, bool)`

GetKeyDurationOk returns a tuple with the KeyDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyDuration

`func (o *TextInputRequestV1) SetKeyDuration(v float32)`

SetKeyDuration sets KeyDuration field to given value.

### HasKeyDuration

`func (o *TextInputRequestV1) HasKeyDuration() bool`

HasKeyDuration returns a boolean if a field has been set.

### SetKeyDurationNil

`func (o *TextInputRequestV1) SetKeyDurationNil(b bool)`

 SetKeyDurationNil sets the value for KeyDuration to be an explicit nil

### UnsetKeyDuration
`func (o *TextInputRequestV1) UnsetKeyDuration()`

UnsetKeyDuration ensures that no value is present for KeyDuration, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


