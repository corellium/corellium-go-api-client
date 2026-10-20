# InstanceInputBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Position** | Pointer to **[][]float32** | Array of per-finger [x,y] touch positions, up to 10 depending on model. | [optional] 
**Buttons** | Pointer to **[]string** | Buttons held when this position is reached. Omit to leave unchanged; use an empty array to release. VM button names: finger, homeButton, holdButton (Power/Hold), volumeUp, volumeDown, backButton, overviewButton. Also accepts single ASCII characters and keyboard key names (e.g. enter, home, power). Use finger:1 for the fingerprint sensor. | [optional] 
**Normalized** | Pointer to **bool** | Use normalized 0-10000 coordinates. | [optional] 
**Wait** | Pointer to **float32** | Duration to wait before this input is executed, in milliseconds. | [optional] 
**Start** | **[][]float32** | Array of per-finger [x,y] touch positions, up to 10 depending on model. | 
**End** | **[][]float32** | Array of per-finger [x,y] touch positions, up to 10 depending on model. | 
**BezierPoints** | Pointer to [**[][][]float32**]([][]float32.md) | Per-finger intermediate touch positions. | [optional] 
**StartButtons** | **[]string** | Buttons held during this curve. VM button names: finger, homeButton, holdButton (Power/Hold), volumeUp, volumeDown, backButton, overviewButton. Also accepts single ASCII characters and keyboard key names (e.g. enter, home, power). Use finger:1 for the fingerprint sensor. | 
**EndButtons** | Pointer to **[]string** | Buttons left held after this curve. Omit to leave unchanged; use an empty array to release. VM button names: finger, homeButton, holdButton (Power/Hold), volumeUp, volumeDown, backButton, overviewButton. Also accepts single ASCII characters and keyboard key names (e.g. enter, home, power). Use finger:1 for the fingerprint sensor. | [optional] 
**Duration** | **float32** | Duration to execute this curve over, in milliseconds. | 
**Text** | **string** | Text to type. | 
**KeyDuration** | Pointer to **float32** | How long to take to type each key, in milliseconds. Defaults to ~150ms per key downstream when omitted. | [optional] 

## Methods

### NewInstanceInputBody

`func NewInstanceInputBody(start [][]float32, end [][]float32, startButtons []string, duration float32, text string, ) *InstanceInputBody`

NewInstanceInputBody instantiates a new InstanceInputBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceInputBodyWithDefaults

`func NewInstanceInputBodyWithDefaults() *InstanceInputBody`

NewInstanceInputBodyWithDefaults instantiates a new InstanceInputBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPosition

`func (o *InstanceInputBody) GetPosition() [][]float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *InstanceInputBody) GetPositionOk() (*[][]float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *InstanceInputBody) SetPosition(v [][]float32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *InstanceInputBody) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetButtons

`func (o *InstanceInputBody) GetButtons() []string`

GetButtons returns the Buttons field if non-nil, zero value otherwise.

### GetButtonsOk

`func (o *InstanceInputBody) GetButtonsOk() (*[]string, bool)`

GetButtonsOk returns a tuple with the Buttons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetButtons

`func (o *InstanceInputBody) SetButtons(v []string)`

SetButtons sets Buttons field to given value.

### HasButtons

`func (o *InstanceInputBody) HasButtons() bool`

HasButtons returns a boolean if a field has been set.

### GetNormalized

`func (o *InstanceInputBody) GetNormalized() bool`

GetNormalized returns the Normalized field if non-nil, zero value otherwise.

### GetNormalizedOk

`func (o *InstanceInputBody) GetNormalizedOk() (*bool, bool)`

GetNormalizedOk returns a tuple with the Normalized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalized

`func (o *InstanceInputBody) SetNormalized(v bool)`

SetNormalized sets Normalized field to given value.

### HasNormalized

`func (o *InstanceInputBody) HasNormalized() bool`

HasNormalized returns a boolean if a field has been set.

### GetWait

`func (o *InstanceInputBody) GetWait() float32`

GetWait returns the Wait field if non-nil, zero value otherwise.

### GetWaitOk

`func (o *InstanceInputBody) GetWaitOk() (*float32, bool)`

GetWaitOk returns a tuple with the Wait field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWait

`func (o *InstanceInputBody) SetWait(v float32)`

SetWait sets Wait field to given value.

### HasWait

`func (o *InstanceInputBody) HasWait() bool`

HasWait returns a boolean if a field has been set.

### GetStart

`func (o *InstanceInputBody) GetStart() [][]float32`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *InstanceInputBody) GetStartOk() (*[][]float32, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *InstanceInputBody) SetStart(v [][]float32)`

SetStart sets Start field to given value.


### GetEnd

`func (o *InstanceInputBody) GetEnd() [][]float32`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *InstanceInputBody) GetEndOk() (*[][]float32, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *InstanceInputBody) SetEnd(v [][]float32)`

SetEnd sets End field to given value.


### GetBezierPoints

`func (o *InstanceInputBody) GetBezierPoints() [][][]float32`

GetBezierPoints returns the BezierPoints field if non-nil, zero value otherwise.

### GetBezierPointsOk

`func (o *InstanceInputBody) GetBezierPointsOk() (*[][][]float32, bool)`

GetBezierPointsOk returns a tuple with the BezierPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBezierPoints

`func (o *InstanceInputBody) SetBezierPoints(v [][][]float32)`

SetBezierPoints sets BezierPoints field to given value.

### HasBezierPoints

`func (o *InstanceInputBody) HasBezierPoints() bool`

HasBezierPoints returns a boolean if a field has been set.

### GetStartButtons

`func (o *InstanceInputBody) GetStartButtons() []string`

GetStartButtons returns the StartButtons field if non-nil, zero value otherwise.

### GetStartButtonsOk

`func (o *InstanceInputBody) GetStartButtonsOk() (*[]string, bool)`

GetStartButtonsOk returns a tuple with the StartButtons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartButtons

`func (o *InstanceInputBody) SetStartButtons(v []string)`

SetStartButtons sets StartButtons field to given value.


### GetEndButtons

`func (o *InstanceInputBody) GetEndButtons() []string`

GetEndButtons returns the EndButtons field if non-nil, zero value otherwise.

### GetEndButtonsOk

`func (o *InstanceInputBody) GetEndButtonsOk() (*[]string, bool)`

GetEndButtonsOk returns a tuple with the EndButtons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndButtons

`func (o *InstanceInputBody) SetEndButtons(v []string)`

SetEndButtons sets EndButtons field to given value.

### HasEndButtons

`func (o *InstanceInputBody) HasEndButtons() bool`

HasEndButtons returns a boolean if a field has been set.

### GetDuration

`func (o *InstanceInputBody) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *InstanceInputBody) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *InstanceInputBody) SetDuration(v float32)`

SetDuration sets Duration field to given value.


### GetText

`func (o *InstanceInputBody) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *InstanceInputBody) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *InstanceInputBody) SetText(v string)`

SetText sets Text field to given value.


### GetKeyDuration

`func (o *InstanceInputBody) GetKeyDuration() float32`

GetKeyDuration returns the KeyDuration field if non-nil, zero value otherwise.

### GetKeyDurationOk

`func (o *InstanceInputBody) GetKeyDurationOk() (*float32, bool)`

GetKeyDurationOk returns a tuple with the KeyDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyDuration

`func (o *InstanceInputBody) SetKeyDuration(v float32)`

SetKeyDuration sets KeyDuration field to given value.

### HasKeyDuration

`func (o *InstanceInputBody) HasKeyDuration() bool`

HasKeyDuration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


