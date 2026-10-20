# InstanceInputRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Position** | Pointer to **map[string]interface{}** | Finger Positions | [optional] 
**Buttons** | Pointer to **[]map[string]interface{}** | Buttons to be held when this position is reached. Accepts case-insensitive VM button names, keyboard key names, or single ASCII characters. No change if not defined; an empty array releases all buttons. | [optional] 
**Normalized** | Pointer to **NullableBool** | true if you want to use normalized x,y coordinates from 0-10000 (eg 5000,5000 is always center of screen) | [optional] 
**Wait** | Pointer to **NullableFloat32** | Duration to wait before this input is executed.  Instant if not defined. | [optional] 
**Start** | **map[string]interface{}** | Finger Positions | 
**End** | **map[string]interface{}** | Finger Positions | 
**BezierPoints** | Pointer to **[]map[string]interface{}** | array of per-finger intermediate touch positions, up to 10 depending on model.  Straight line if not defined. | [optional] 
**StartButtons** | **[]map[string]interface{}** | Buttons to be held during this curve. | 
**EndButtons** | Pointer to **[]map[string]interface{}** | Buttons to be left held after this curve.  Same as startButtons if not defined. | [optional] 
**Duration** | **float32** | Duration to execute this curve over. | 
**Required** | **string** | text to type | 
**KeyDuration** | Pointer to **NullableFloat32** | How long to take to type each key.  150ms if not defined. | [optional] 

## Methods

### NewInstanceInputRequest

`func NewInstanceInputRequest(start map[string]interface{}, end map[string]interface{}, startButtons []map[string]interface{}, duration float32, required string, ) *InstanceInputRequest`

NewInstanceInputRequest instantiates a new InstanceInputRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceInputRequestWithDefaults

`func NewInstanceInputRequestWithDefaults() *InstanceInputRequest`

NewInstanceInputRequestWithDefaults instantiates a new InstanceInputRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPosition

`func (o *InstanceInputRequest) GetPosition() map[string]interface{}`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *InstanceInputRequest) GetPositionOk() (*map[string]interface{}, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *InstanceInputRequest) SetPosition(v map[string]interface{})`

SetPosition sets Position field to given value.

### HasPosition

`func (o *InstanceInputRequest) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetButtons

`func (o *InstanceInputRequest) GetButtons() []map[string]interface{}`

GetButtons returns the Buttons field if non-nil, zero value otherwise.

### GetButtonsOk

`func (o *InstanceInputRequest) GetButtonsOk() (*[]map[string]interface{}, bool)`

GetButtonsOk returns a tuple with the Buttons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetButtons

`func (o *InstanceInputRequest) SetButtons(v []map[string]interface{})`

SetButtons sets Buttons field to given value.

### HasButtons

`func (o *InstanceInputRequest) HasButtons() bool`

HasButtons returns a boolean if a field has been set.

### SetButtonsNil

`func (o *InstanceInputRequest) SetButtonsNil(b bool)`

 SetButtonsNil sets the value for Buttons to be an explicit nil

### UnsetButtons
`func (o *InstanceInputRequest) UnsetButtons()`

UnsetButtons ensures that no value is present for Buttons, not even an explicit nil
### GetNormalized

`func (o *InstanceInputRequest) GetNormalized() bool`

GetNormalized returns the Normalized field if non-nil, zero value otherwise.

### GetNormalizedOk

`func (o *InstanceInputRequest) GetNormalizedOk() (*bool, bool)`

GetNormalizedOk returns a tuple with the Normalized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalized

`func (o *InstanceInputRequest) SetNormalized(v bool)`

SetNormalized sets Normalized field to given value.

### HasNormalized

`func (o *InstanceInputRequest) HasNormalized() bool`

HasNormalized returns a boolean if a field has been set.

### SetNormalizedNil

`func (o *InstanceInputRequest) SetNormalizedNil(b bool)`

 SetNormalizedNil sets the value for Normalized to be an explicit nil

### UnsetNormalized
`func (o *InstanceInputRequest) UnsetNormalized()`

UnsetNormalized ensures that no value is present for Normalized, not even an explicit nil
### GetWait

`func (o *InstanceInputRequest) GetWait() float32`

GetWait returns the Wait field if non-nil, zero value otherwise.

### GetWaitOk

`func (o *InstanceInputRequest) GetWaitOk() (*float32, bool)`

GetWaitOk returns a tuple with the Wait field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWait

`func (o *InstanceInputRequest) SetWait(v float32)`

SetWait sets Wait field to given value.

### HasWait

`func (o *InstanceInputRequest) HasWait() bool`

HasWait returns a boolean if a field has been set.

### SetWaitNil

`func (o *InstanceInputRequest) SetWaitNil(b bool)`

 SetWaitNil sets the value for Wait to be an explicit nil

### UnsetWait
`func (o *InstanceInputRequest) UnsetWait()`

UnsetWait ensures that no value is present for Wait, not even an explicit nil
### GetStart

`func (o *InstanceInputRequest) GetStart() map[string]interface{}`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *InstanceInputRequest) GetStartOk() (*map[string]interface{}, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *InstanceInputRequest) SetStart(v map[string]interface{})`

SetStart sets Start field to given value.


### GetEnd

`func (o *InstanceInputRequest) GetEnd() map[string]interface{}`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *InstanceInputRequest) GetEndOk() (*map[string]interface{}, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *InstanceInputRequest) SetEnd(v map[string]interface{})`

SetEnd sets End field to given value.


### GetBezierPoints

`func (o *InstanceInputRequest) GetBezierPoints() []map[string]interface{}`

GetBezierPoints returns the BezierPoints field if non-nil, zero value otherwise.

### GetBezierPointsOk

`func (o *InstanceInputRequest) GetBezierPointsOk() (*[]map[string]interface{}, bool)`

GetBezierPointsOk returns a tuple with the BezierPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBezierPoints

`func (o *InstanceInputRequest) SetBezierPoints(v []map[string]interface{})`

SetBezierPoints sets BezierPoints field to given value.

### HasBezierPoints

`func (o *InstanceInputRequest) HasBezierPoints() bool`

HasBezierPoints returns a boolean if a field has been set.

### SetBezierPointsNil

`func (o *InstanceInputRequest) SetBezierPointsNil(b bool)`

 SetBezierPointsNil sets the value for BezierPoints to be an explicit nil

### UnsetBezierPoints
`func (o *InstanceInputRequest) UnsetBezierPoints()`

UnsetBezierPoints ensures that no value is present for BezierPoints, not even an explicit nil
### GetStartButtons

`func (o *InstanceInputRequest) GetStartButtons() []map[string]interface{}`

GetStartButtons returns the StartButtons field if non-nil, zero value otherwise.

### GetStartButtonsOk

`func (o *InstanceInputRequest) GetStartButtonsOk() (*[]map[string]interface{}, bool)`

GetStartButtonsOk returns a tuple with the StartButtons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartButtons

`func (o *InstanceInputRequest) SetStartButtons(v []map[string]interface{})`

SetStartButtons sets StartButtons field to given value.


### GetEndButtons

`func (o *InstanceInputRequest) GetEndButtons() []map[string]interface{}`

GetEndButtons returns the EndButtons field if non-nil, zero value otherwise.

### GetEndButtonsOk

`func (o *InstanceInputRequest) GetEndButtonsOk() (*[]map[string]interface{}, bool)`

GetEndButtonsOk returns a tuple with the EndButtons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndButtons

`func (o *InstanceInputRequest) SetEndButtons(v []map[string]interface{})`

SetEndButtons sets EndButtons field to given value.

### HasEndButtons

`func (o *InstanceInputRequest) HasEndButtons() bool`

HasEndButtons returns a boolean if a field has been set.

### SetEndButtonsNil

`func (o *InstanceInputRequest) SetEndButtonsNil(b bool)`

 SetEndButtonsNil sets the value for EndButtons to be an explicit nil

### UnsetEndButtons
`func (o *InstanceInputRequest) UnsetEndButtons()`

UnsetEndButtons ensures that no value is present for EndButtons, not even an explicit nil
### GetDuration

`func (o *InstanceInputRequest) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *InstanceInputRequest) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *InstanceInputRequest) SetDuration(v float32)`

SetDuration sets Duration field to given value.


### GetRequired

`func (o *InstanceInputRequest) GetRequired() string`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *InstanceInputRequest) GetRequiredOk() (*string, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *InstanceInputRequest) SetRequired(v string)`

SetRequired sets Required field to given value.


### GetKeyDuration

`func (o *InstanceInputRequest) GetKeyDuration() float32`

GetKeyDuration returns the KeyDuration field if non-nil, zero value otherwise.

### GetKeyDurationOk

`func (o *InstanceInputRequest) GetKeyDurationOk() (*float32, bool)`

GetKeyDurationOk returns a tuple with the KeyDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyDuration

`func (o *InstanceInputRequest) SetKeyDuration(v float32)`

SetKeyDuration sets KeyDuration field to given value.

### HasKeyDuration

`func (o *InstanceInputRequest) HasKeyDuration() bool`

HasKeyDuration returns a boolean if a field has been set.

### SetKeyDurationNil

`func (o *InstanceInputRequest) SetKeyDurationNil(b bool)`

 SetKeyDurationNil sets the value for KeyDuration to be an explicit nil

### UnsetKeyDuration
`func (o *InstanceInputRequest) UnsetKeyDuration()`

UnsetKeyDuration ensures that no value is present for KeyDuration, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


