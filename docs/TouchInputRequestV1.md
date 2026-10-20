# TouchInputRequestV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Position** | Pointer to **map[string]interface{}** | Finger Positions | [optional] 
**Buttons** | Pointer to **[]interface{}** | Buttons to be held when this position is reached. Accepts case-insensitive VM button names, keyboard key names, or single ASCII characters. No change if not defined; an empty array releases all buttons. | [optional] 
**Normalized** | Pointer to **NullableBool** | true if you want to use normalized x,y coordinates from 0-10000 (eg 5000,5000 is always center of screen) | [optional] 
**Wait** | Pointer to **NullableFloat32** | Duration to wait before this input is executed.  Instant if not defined. | [optional] 

## Methods

### NewTouchInputRequestV1

`func NewTouchInputRequestV1() *TouchInputRequestV1`

NewTouchInputRequestV1 instantiates a new TouchInputRequestV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTouchInputRequestV1WithDefaults

`func NewTouchInputRequestV1WithDefaults() *TouchInputRequestV1`

NewTouchInputRequestV1WithDefaults instantiates a new TouchInputRequestV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPosition

`func (o *TouchInputRequestV1) GetPosition() map[string]interface{}`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *TouchInputRequestV1) GetPositionOk() (*map[string]interface{}, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *TouchInputRequestV1) SetPosition(v map[string]interface{})`

SetPosition sets Position field to given value.

### HasPosition

`func (o *TouchInputRequestV1) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetButtons

`func (o *TouchInputRequestV1) GetButtons() []interface{}`

GetButtons returns the Buttons field if non-nil, zero value otherwise.

### GetButtonsOk

`func (o *TouchInputRequestV1) GetButtonsOk() (*[]interface{}, bool)`

GetButtonsOk returns a tuple with the Buttons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetButtons

`func (o *TouchInputRequestV1) SetButtons(v []interface{})`

SetButtons sets Buttons field to given value.

### HasButtons

`func (o *TouchInputRequestV1) HasButtons() bool`

HasButtons returns a boolean if a field has been set.

### SetButtonsNil

`func (o *TouchInputRequestV1) SetButtonsNil(b bool)`

 SetButtonsNil sets the value for Buttons to be an explicit nil

### UnsetButtons
`func (o *TouchInputRequestV1) UnsetButtons()`

UnsetButtons ensures that no value is present for Buttons, not even an explicit nil
### GetNormalized

`func (o *TouchInputRequestV1) GetNormalized() bool`

GetNormalized returns the Normalized field if non-nil, zero value otherwise.

### GetNormalizedOk

`func (o *TouchInputRequestV1) GetNormalizedOk() (*bool, bool)`

GetNormalizedOk returns a tuple with the Normalized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalized

`func (o *TouchInputRequestV1) SetNormalized(v bool)`

SetNormalized sets Normalized field to given value.

### HasNormalized

`func (o *TouchInputRequestV1) HasNormalized() bool`

HasNormalized returns a boolean if a field has been set.

### SetNormalizedNil

`func (o *TouchInputRequestV1) SetNormalizedNil(b bool)`

 SetNormalizedNil sets the value for Normalized to be an explicit nil

### UnsetNormalized
`func (o *TouchInputRequestV1) UnsetNormalized()`

UnsetNormalized ensures that no value is present for Normalized, not even an explicit nil
### GetWait

`func (o *TouchInputRequestV1) GetWait() float32`

GetWait returns the Wait field if non-nil, zero value otherwise.

### GetWaitOk

`func (o *TouchInputRequestV1) GetWaitOk() (*float32, bool)`

GetWaitOk returns a tuple with the Wait field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWait

`func (o *TouchInputRequestV1) SetWait(v float32)`

SetWait sets Wait field to given value.

### HasWait

`func (o *TouchInputRequestV1) HasWait() bool`

HasWait returns a boolean if a field has been set.

### SetWaitNil

`func (o *TouchInputRequestV1) SetWaitNil(b bool)`

 SetWaitNil sets the value for Wait to be an explicit nil

### UnsetWait
`func (o *TouchInputRequestV1) UnsetWait()`

UnsetWait ensures that no value is present for Wait, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


