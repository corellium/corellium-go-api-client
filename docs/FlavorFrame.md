# FlavorFrame

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | Relative URL to the frame image asset. | 
**Width** | **float32** | Frame image width in points. | 
**Height** | **float32** | Frame image height in points. | 
**Inner** | [**FlavorFrameInner**](FlavorFrameInner.md) |  | 
**Home** | [**FlavorFrameHome**](FlavorFrameHome.md) |  | 
**Dimensions** | [**FlavorFrameDimensions**](FlavorFrameDimensions.md) |  | 
**Scale** | **float32** | Display scale factor. | 

## Methods

### NewFlavorFrame

`func NewFlavorFrame(url string, width float32, height float32, inner FlavorFrameInner, home FlavorFrameHome, dimensions FlavorFrameDimensions, scale float32, ) *FlavorFrame`

NewFlavorFrame instantiates a new FlavorFrame object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFlavorFrameWithDefaults

`func NewFlavorFrameWithDefaults() *FlavorFrame`

NewFlavorFrameWithDefaults instantiates a new FlavorFrame object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *FlavorFrame) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FlavorFrame) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FlavorFrame) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetWidth

`func (o *FlavorFrame) GetWidth() float32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *FlavorFrame) GetWidthOk() (*float32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *FlavorFrame) SetWidth(v float32)`

SetWidth sets Width field to given value.


### GetHeight

`func (o *FlavorFrame) GetHeight() float32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *FlavorFrame) GetHeightOk() (*float32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *FlavorFrame) SetHeight(v float32)`

SetHeight sets Height field to given value.


### GetInner

`func (o *FlavorFrame) GetInner() FlavorFrameInner`

GetInner returns the Inner field if non-nil, zero value otherwise.

### GetInnerOk

`func (o *FlavorFrame) GetInnerOk() (*FlavorFrameInner, bool)`

GetInnerOk returns a tuple with the Inner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInner

`func (o *FlavorFrame) SetInner(v FlavorFrameInner)`

SetInner sets Inner field to given value.


### GetHome

`func (o *FlavorFrame) GetHome() FlavorFrameHome`

GetHome returns the Home field if non-nil, zero value otherwise.

### GetHomeOk

`func (o *FlavorFrame) GetHomeOk() (*FlavorFrameHome, bool)`

GetHomeOk returns a tuple with the Home field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHome

`func (o *FlavorFrame) SetHome(v FlavorFrameHome)`

SetHome sets Home field to given value.


### GetDimensions

`func (o *FlavorFrame) GetDimensions() FlavorFrameDimensions`

GetDimensions returns the Dimensions field if non-nil, zero value otherwise.

### GetDimensionsOk

`func (o *FlavorFrame) GetDimensionsOk() (*FlavorFrameDimensions, bool)`

GetDimensionsOk returns a tuple with the Dimensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensions

`func (o *FlavorFrame) SetDimensions(v FlavorFrameDimensions)`

SetDimensions sets Dimensions field to given value.


### GetScale

`func (o *FlavorFrame) GetScale() float32`

GetScale returns the Scale field if non-nil, zero value otherwise.

### GetScaleOk

`func (o *FlavorFrame) GetScaleOk() (*float32, bool)`

GetScaleOk returns a tuple with the Scale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScale

`func (o *FlavorFrame) SetScale(v float32)`

SetScale sets Scale field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


