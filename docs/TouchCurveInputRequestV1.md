# TouchCurveInputRequestV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Start** | **map[string]interface{}** | Finger Positions | 
**End** | **map[string]interface{}** | Finger Positions | 
**BezierPoints** | Pointer to **[]map[string]interface{}** | array of per-finger intermediate touch positions, up to 10 depending on model.  Straight line if not defined. | [optional] 
**StartButtons** | **[]interface{}** | Buttons to be held during this curve. | 
**EndButtons** | Pointer to **[]interface{}** | Buttons to be left held after this curve.  Same as startButtons if not defined. | [optional] 
**Normalized** | Pointer to **NullableBool** | true if you want to use normalized x,y coordinates from 0-10000 (eg 5000,5000 is always center of screen) | [optional] 
**Wait** | Pointer to **NullableFloat32** | Duration to wait before this input is executed.  Instant if not defined. | [optional] 
**Duration** | **float32** | Duration to execute this curve over. | 

## Methods

### NewTouchCurveInputRequestV1

`func NewTouchCurveInputRequestV1(start map[string]interface{}, end map[string]interface{}, startButtons []interface{}, duration float32, ) *TouchCurveInputRequestV1`

NewTouchCurveInputRequestV1 instantiates a new TouchCurveInputRequestV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTouchCurveInputRequestV1WithDefaults

`func NewTouchCurveInputRequestV1WithDefaults() *TouchCurveInputRequestV1`

NewTouchCurveInputRequestV1WithDefaults instantiates a new TouchCurveInputRequestV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStart

`func (o *TouchCurveInputRequestV1) GetStart() map[string]interface{}`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *TouchCurveInputRequestV1) GetStartOk() (*map[string]interface{}, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *TouchCurveInputRequestV1) SetStart(v map[string]interface{})`

SetStart sets Start field to given value.


### GetEnd

`func (o *TouchCurveInputRequestV1) GetEnd() map[string]interface{}`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *TouchCurveInputRequestV1) GetEndOk() (*map[string]interface{}, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *TouchCurveInputRequestV1) SetEnd(v map[string]interface{})`

SetEnd sets End field to given value.


### GetBezierPoints

`func (o *TouchCurveInputRequestV1) GetBezierPoints() []map[string]interface{}`

GetBezierPoints returns the BezierPoints field if non-nil, zero value otherwise.

### GetBezierPointsOk

`func (o *TouchCurveInputRequestV1) GetBezierPointsOk() (*[]map[string]interface{}, bool)`

GetBezierPointsOk returns a tuple with the BezierPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBezierPoints

`func (o *TouchCurveInputRequestV1) SetBezierPoints(v []map[string]interface{})`

SetBezierPoints sets BezierPoints field to given value.

### HasBezierPoints

`func (o *TouchCurveInputRequestV1) HasBezierPoints() bool`

HasBezierPoints returns a boolean if a field has been set.

### SetBezierPointsNil

`func (o *TouchCurveInputRequestV1) SetBezierPointsNil(b bool)`

 SetBezierPointsNil sets the value for BezierPoints to be an explicit nil

### UnsetBezierPoints
`func (o *TouchCurveInputRequestV1) UnsetBezierPoints()`

UnsetBezierPoints ensures that no value is present for BezierPoints, not even an explicit nil
### GetStartButtons

`func (o *TouchCurveInputRequestV1) GetStartButtons() []interface{}`

GetStartButtons returns the StartButtons field if non-nil, zero value otherwise.

### GetStartButtonsOk

`func (o *TouchCurveInputRequestV1) GetStartButtonsOk() (*[]interface{}, bool)`

GetStartButtonsOk returns a tuple with the StartButtons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartButtons

`func (o *TouchCurveInputRequestV1) SetStartButtons(v []interface{})`

SetStartButtons sets StartButtons field to given value.


### GetEndButtons

`func (o *TouchCurveInputRequestV1) GetEndButtons() []interface{}`

GetEndButtons returns the EndButtons field if non-nil, zero value otherwise.

### GetEndButtonsOk

`func (o *TouchCurveInputRequestV1) GetEndButtonsOk() (*[]interface{}, bool)`

GetEndButtonsOk returns a tuple with the EndButtons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndButtons

`func (o *TouchCurveInputRequestV1) SetEndButtons(v []interface{})`

SetEndButtons sets EndButtons field to given value.

### HasEndButtons

`func (o *TouchCurveInputRequestV1) HasEndButtons() bool`

HasEndButtons returns a boolean if a field has been set.

### SetEndButtonsNil

`func (o *TouchCurveInputRequestV1) SetEndButtonsNil(b bool)`

 SetEndButtonsNil sets the value for EndButtons to be an explicit nil

### UnsetEndButtons
`func (o *TouchCurveInputRequestV1) UnsetEndButtons()`

UnsetEndButtons ensures that no value is present for EndButtons, not even an explicit nil
### GetNormalized

`func (o *TouchCurveInputRequestV1) GetNormalized() bool`

GetNormalized returns the Normalized field if non-nil, zero value otherwise.

### GetNormalizedOk

`func (o *TouchCurveInputRequestV1) GetNormalizedOk() (*bool, bool)`

GetNormalizedOk returns a tuple with the Normalized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalized

`func (o *TouchCurveInputRequestV1) SetNormalized(v bool)`

SetNormalized sets Normalized field to given value.

### HasNormalized

`func (o *TouchCurveInputRequestV1) HasNormalized() bool`

HasNormalized returns a boolean if a field has been set.

### SetNormalizedNil

`func (o *TouchCurveInputRequestV1) SetNormalizedNil(b bool)`

 SetNormalizedNil sets the value for Normalized to be an explicit nil

### UnsetNormalized
`func (o *TouchCurveInputRequestV1) UnsetNormalized()`

UnsetNormalized ensures that no value is present for Normalized, not even an explicit nil
### GetWait

`func (o *TouchCurveInputRequestV1) GetWait() float32`

GetWait returns the Wait field if non-nil, zero value otherwise.

### GetWaitOk

`func (o *TouchCurveInputRequestV1) GetWaitOk() (*float32, bool)`

GetWaitOk returns a tuple with the Wait field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWait

`func (o *TouchCurveInputRequestV1) SetWait(v float32)`

SetWait sets Wait field to given value.

### HasWait

`func (o *TouchCurveInputRequestV1) HasWait() bool`

HasWait returns a boolean if a field has been set.

### SetWaitNil

`func (o *TouchCurveInputRequestV1) SetWaitNil(b bool)`

 SetWaitNil sets the value for Wait to be an explicit nil

### UnsetWait
`func (o *TouchCurveInputRequestV1) UnsetWait()`

UnsetWait ensures that no value is present for Wait, not even an explicit nil
### GetDuration

`func (o *TouchCurveInputRequestV1) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TouchCurveInputRequestV1) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TouchCurveInputRequestV1) SetDuration(v float32)`

SetDuration sets Duration field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


