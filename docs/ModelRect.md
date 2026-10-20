# ModelRect

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Top** | **float32** | Offset from the top edge. | 
**Left** | **float32** | Offset from the left edge. | 
**Width** | **float32** | Width. | 
**Height** | **float32** | Height. | 
**Radius** | Pointer to **float32** | Corner radius, as a fraction of the width. | [optional] 

## Methods

### NewModelRect

`func NewModelRect(top float32, left float32, width float32, height float32, ) *ModelRect`

NewModelRect instantiates a new ModelRect object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelRectWithDefaults

`func NewModelRectWithDefaults() *ModelRect`

NewModelRectWithDefaults instantiates a new ModelRect object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTop

`func (o *ModelRect) GetTop() float32`

GetTop returns the Top field if non-nil, zero value otherwise.

### GetTopOk

`func (o *ModelRect) GetTopOk() (*float32, bool)`

GetTopOk returns a tuple with the Top field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTop

`func (o *ModelRect) SetTop(v float32)`

SetTop sets Top field to given value.


### GetLeft

`func (o *ModelRect) GetLeft() float32`

GetLeft returns the Left field if non-nil, zero value otherwise.

### GetLeftOk

`func (o *ModelRect) GetLeftOk() (*float32, bool)`

GetLeftOk returns a tuple with the Left field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeft

`func (o *ModelRect) SetLeft(v float32)`

SetLeft sets Left field to given value.


### GetWidth

`func (o *ModelRect) GetWidth() float32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *ModelRect) GetWidthOk() (*float32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *ModelRect) SetWidth(v float32)`

SetWidth sets Width field to given value.


### GetHeight

`func (o *ModelRect) GetHeight() float32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *ModelRect) GetHeightOk() (*float32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *ModelRect) SetHeight(v float32)`

SetHeight sets Height field to given value.


### GetRadius

`func (o *ModelRect) GetRadius() float32`

GetRadius returns the Radius field if non-nil, zero value otherwise.

### GetRadiusOk

`func (o *ModelRect) GetRadiusOk() (*float32, bool)`

GetRadiusOk returns a tuple with the Radius field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadius

`func (o *ModelRect) SetRadius(v float32)`

SetRadius sets Radius field to given value.

### HasRadius

`func (o *ModelRect) HasRadius() bool`

HasRadius returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


