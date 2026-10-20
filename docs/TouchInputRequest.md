# TouchInputRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Position** | Pointer to **[][]float32** | Array of per-finger [x,y] touch positions, up to 10 depending on model. | [optional] 
**Buttons** | Pointer to **[]string** | Buttons held when this position is reached. Omit to leave unchanged; use an empty array to release. VM button names: finger, homeButton, holdButton (Power/Hold), volumeUp, volumeDown, backButton, overviewButton. Also accepts single ASCII characters and keyboard key names (e.g. enter, home, power). Use finger:1 for the fingerprint sensor. | [optional] 
**Normalized** | Pointer to **bool** | Use normalized 0-10000 coordinates. | [optional] 
**Wait** | Pointer to **float32** | Duration to wait before this input is executed, in milliseconds. | [optional] 

## Methods

### NewTouchInputRequest

`func NewTouchInputRequest() *TouchInputRequest`

NewTouchInputRequest instantiates a new TouchInputRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTouchInputRequestWithDefaults

`func NewTouchInputRequestWithDefaults() *TouchInputRequest`

NewTouchInputRequestWithDefaults instantiates a new TouchInputRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPosition

`func (o *TouchInputRequest) GetPosition() [][]float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *TouchInputRequest) GetPositionOk() (*[][]float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *TouchInputRequest) SetPosition(v [][]float32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *TouchInputRequest) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetButtons

`func (o *TouchInputRequest) GetButtons() []string`

GetButtons returns the Buttons field if non-nil, zero value otherwise.

### GetButtonsOk

`func (o *TouchInputRequest) GetButtonsOk() (*[]string, bool)`

GetButtonsOk returns a tuple with the Buttons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetButtons

`func (o *TouchInputRequest) SetButtons(v []string)`

SetButtons sets Buttons field to given value.

### HasButtons

`func (o *TouchInputRequest) HasButtons() bool`

HasButtons returns a boolean if a field has been set.

### GetNormalized

`func (o *TouchInputRequest) GetNormalized() bool`

GetNormalized returns the Normalized field if non-nil, zero value otherwise.

### GetNormalizedOk

`func (o *TouchInputRequest) GetNormalizedOk() (*bool, bool)`

GetNormalizedOk returns a tuple with the Normalized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalized

`func (o *TouchInputRequest) SetNormalized(v bool)`

SetNormalized sets Normalized field to given value.

### HasNormalized

`func (o *TouchInputRequest) HasNormalized() bool`

HasNormalized returns a boolean if a field has been set.

### GetWait

`func (o *TouchInputRequest) GetWait() float32`

GetWait returns the Wait field if non-nil, zero value otherwise.

### GetWaitOk

`func (o *TouchInputRequest) GetWaitOk() (*float32, bool)`

GetWaitOk returns a tuple with the Wait field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWait

`func (o *TouchInputRequest) SetWait(v float32)`

SetWait sets Wait field to given value.

### HasWait

`func (o *TouchInputRequest) HasWait() bool`

HasWait returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


