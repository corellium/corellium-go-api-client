# ModelFrame

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Width** | **float32** | Bezel image width. | 
**Height** | **float32** | Bezel image height. | 
**Inner** | Pointer to [**ModelRect**](ModelRect.md) |  | [optional] 
**Home** | Pointer to [**ModelRect**](ModelRect.md) | Home button area within the bezel. | [optional] 
**Dimensions** | Pointer to [**ModelFrameDimensions**](ModelFrameDimensions.md) |  | [optional] 
**Scale** | Pointer to **float32** | Display scale factor. | [optional] 
**HasImage** | **bool** | Whether a bezel image is available for this model. | 

## Methods

### NewModelFrame

`func NewModelFrame(width float32, height float32, hasImage bool, ) *ModelFrame`

NewModelFrame instantiates a new ModelFrame object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelFrameWithDefaults

`func NewModelFrameWithDefaults() *ModelFrame`

NewModelFrameWithDefaults instantiates a new ModelFrame object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWidth

`func (o *ModelFrame) GetWidth() float32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *ModelFrame) GetWidthOk() (*float32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *ModelFrame) SetWidth(v float32)`

SetWidth sets Width field to given value.


### GetHeight

`func (o *ModelFrame) GetHeight() float32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *ModelFrame) GetHeightOk() (*float32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *ModelFrame) SetHeight(v float32)`

SetHeight sets Height field to given value.


### GetInner

`func (o *ModelFrame) GetInner() ModelRect`

GetInner returns the Inner field if non-nil, zero value otherwise.

### GetInnerOk

`func (o *ModelFrame) GetInnerOk() (*ModelRect, bool)`

GetInnerOk returns a tuple with the Inner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInner

`func (o *ModelFrame) SetInner(v ModelRect)`

SetInner sets Inner field to given value.

### HasInner

`func (o *ModelFrame) HasInner() bool`

HasInner returns a boolean if a field has been set.

### GetHome

`func (o *ModelFrame) GetHome() ModelRect`

GetHome returns the Home field if non-nil, zero value otherwise.

### GetHomeOk

`func (o *ModelFrame) GetHomeOk() (*ModelRect, bool)`

GetHomeOk returns a tuple with the Home field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHome

`func (o *ModelFrame) SetHome(v ModelRect)`

SetHome sets Home field to given value.

### HasHome

`func (o *ModelFrame) HasHome() bool`

HasHome returns a boolean if a field has been set.

### GetDimensions

`func (o *ModelFrame) GetDimensions() ModelFrameDimensions`

GetDimensions returns the Dimensions field if non-nil, zero value otherwise.

### GetDimensionsOk

`func (o *ModelFrame) GetDimensionsOk() (*ModelFrameDimensions, bool)`

GetDimensionsOk returns a tuple with the Dimensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensions

`func (o *ModelFrame) SetDimensions(v ModelFrameDimensions)`

SetDimensions sets Dimensions field to given value.

### HasDimensions

`func (o *ModelFrame) HasDimensions() bool`

HasDimensions returns a boolean if a field has been set.

### GetScale

`func (o *ModelFrame) GetScale() float32`

GetScale returns the Scale field if non-nil, zero value otherwise.

### GetScaleOk

`func (o *ModelFrame) GetScaleOk() (*float32, bool)`

GetScaleOk returns a tuple with the Scale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScale

`func (o *ModelFrame) SetScale(v float32)`

SetScale sets Scale field to given value.

### HasScale

`func (o *ModelFrame) HasScale() bool`

HasScale returns a boolean if a field has been set.

### GetHasImage

`func (o *ModelFrame) GetHasImage() bool`

GetHasImage returns the HasImage field if non-nil, zero value otherwise.

### GetHasImageOk

`func (o *ModelFrame) GetHasImageOk() (*bool, bool)`

GetHasImageOk returns a tuple with the HasImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasImage

`func (o *ModelFrame) SetHasImage(v bool)`

SetHasImage sets HasImage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


