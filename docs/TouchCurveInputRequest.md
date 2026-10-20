# TouchCurveInputRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Start** | **[][]float32** | Array of per-finger [x,y] touch positions, up to 10 depending on model. | 
**End** | **[][]float32** | Array of per-finger [x,y] touch positions, up to 10 depending on model. | 
**BezierPoints** | Pointer to [**[][][]float32**]([][]float32.md) | Per-finger intermediate touch positions. | [optional] 
**StartButtons** | **[]string** | Buttons held during this curve. VM button names: finger, homeButton, holdButton (Power/Hold), volumeUp, volumeDown, backButton, overviewButton. Also accepts single ASCII characters and keyboard key names (e.g. enter, home, power). Use finger:1 for the fingerprint sensor. | 
**EndButtons** | Pointer to **[]string** | Buttons left held after this curve. Omit to leave unchanged; use an empty array to release. VM button names: finger, homeButton, holdButton (Power/Hold), volumeUp, volumeDown, backButton, overviewButton. Also accepts single ASCII characters and keyboard key names (e.g. enter, home, power). Use finger:1 for the fingerprint sensor. | [optional] 
**Normalized** | Pointer to **bool** | Use normalized 0-10000 coordinates. | [optional] 
**Wait** | Pointer to **float32** | Duration to wait before this input is executed, in milliseconds. | [optional] 
**Duration** | **float32** | Duration to execute this curve over, in milliseconds. | 

## Methods

### NewTouchCurveInputRequest

`func NewTouchCurveInputRequest(start [][]float32, end [][]float32, startButtons []string, duration float32, ) *TouchCurveInputRequest`

NewTouchCurveInputRequest instantiates a new TouchCurveInputRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTouchCurveInputRequestWithDefaults

`func NewTouchCurveInputRequestWithDefaults() *TouchCurveInputRequest`

NewTouchCurveInputRequestWithDefaults instantiates a new TouchCurveInputRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStart

`func (o *TouchCurveInputRequest) GetStart() [][]float32`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *TouchCurveInputRequest) GetStartOk() (*[][]float32, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *TouchCurveInputRequest) SetStart(v [][]float32)`

SetStart sets Start field to given value.


### GetEnd

`func (o *TouchCurveInputRequest) GetEnd() [][]float32`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *TouchCurveInputRequest) GetEndOk() (*[][]float32, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *TouchCurveInputRequest) SetEnd(v [][]float32)`

SetEnd sets End field to given value.


### GetBezierPoints

`func (o *TouchCurveInputRequest) GetBezierPoints() [][][]float32`

GetBezierPoints returns the BezierPoints field if non-nil, zero value otherwise.

### GetBezierPointsOk

`func (o *TouchCurveInputRequest) GetBezierPointsOk() (*[][][]float32, bool)`

GetBezierPointsOk returns a tuple with the BezierPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBezierPoints

`func (o *TouchCurveInputRequest) SetBezierPoints(v [][][]float32)`

SetBezierPoints sets BezierPoints field to given value.

### HasBezierPoints

`func (o *TouchCurveInputRequest) HasBezierPoints() bool`

HasBezierPoints returns a boolean if a field has been set.

### GetStartButtons

`func (o *TouchCurveInputRequest) GetStartButtons() []string`

GetStartButtons returns the StartButtons field if non-nil, zero value otherwise.

### GetStartButtonsOk

`func (o *TouchCurveInputRequest) GetStartButtonsOk() (*[]string, bool)`

GetStartButtonsOk returns a tuple with the StartButtons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartButtons

`func (o *TouchCurveInputRequest) SetStartButtons(v []string)`

SetStartButtons sets StartButtons field to given value.


### GetEndButtons

`func (o *TouchCurveInputRequest) GetEndButtons() []string`

GetEndButtons returns the EndButtons field if non-nil, zero value otherwise.

### GetEndButtonsOk

`func (o *TouchCurveInputRequest) GetEndButtonsOk() (*[]string, bool)`

GetEndButtonsOk returns a tuple with the EndButtons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndButtons

`func (o *TouchCurveInputRequest) SetEndButtons(v []string)`

SetEndButtons sets EndButtons field to given value.

### HasEndButtons

`func (o *TouchCurveInputRequest) HasEndButtons() bool`

HasEndButtons returns a boolean if a field has been set.

### GetNormalized

`func (o *TouchCurveInputRequest) GetNormalized() bool`

GetNormalized returns the Normalized field if non-nil, zero value otherwise.

### GetNormalizedOk

`func (o *TouchCurveInputRequest) GetNormalizedOk() (*bool, bool)`

GetNormalizedOk returns a tuple with the Normalized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalized

`func (o *TouchCurveInputRequest) SetNormalized(v bool)`

SetNormalized sets Normalized field to given value.

### HasNormalized

`func (o *TouchCurveInputRequest) HasNormalized() bool`

HasNormalized returns a boolean if a field has been set.

### GetWait

`func (o *TouchCurveInputRequest) GetWait() float32`

GetWait returns the Wait field if non-nil, zero value otherwise.

### GetWaitOk

`func (o *TouchCurveInputRequest) GetWaitOk() (*float32, bool)`

GetWaitOk returns a tuple with the Wait field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWait

`func (o *TouchCurveInputRequest) SetWait(v float32)`

SetWait sets Wait field to given value.

### HasWait

`func (o *TouchCurveInputRequest) HasWait() bool`

HasWait returns a boolean if a field has been set.

### GetDuration

`func (o *TouchCurveInputRequest) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TouchCurveInputRequest) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TouchCurveInputRequest) SetDuration(v float32)`

SetDuration sets Duration field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


