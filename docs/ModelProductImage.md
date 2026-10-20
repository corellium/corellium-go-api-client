# ModelProductImage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Width** | **float32** | Product image width. | 
**Inner** | Pointer to [**ModelRect**](ModelRect.md) | Screen area within the product image. | [optional] 
**HasImage** | **bool** | Whether a product image is available for this model. | 

## Methods

### NewModelProductImage

`func NewModelProductImage(width float32, hasImage bool, ) *ModelProductImage`

NewModelProductImage instantiates a new ModelProductImage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelProductImageWithDefaults

`func NewModelProductImageWithDefaults() *ModelProductImage`

NewModelProductImageWithDefaults instantiates a new ModelProductImage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWidth

`func (o *ModelProductImage) GetWidth() float32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *ModelProductImage) GetWidthOk() (*float32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *ModelProductImage) SetWidth(v float32)`

SetWidth sets Width field to given value.


### GetInner

`func (o *ModelProductImage) GetInner() ModelRect`

GetInner returns the Inner field if non-nil, zero value otherwise.

### GetInnerOk

`func (o *ModelProductImage) GetInnerOk() (*ModelRect, bool)`

GetInnerOk returns a tuple with the Inner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInner

`func (o *ModelProductImage) SetInner(v ModelRect)`

SetInner sets Inner field to given value.

### HasInner

`func (o *ModelProductImage) HasInner() bool`

HasInner returns a boolean if a field has been set.

### GetHasImage

`func (o *ModelProductImage) GetHasImage() bool`

GetHasImage returns the HasImage field if non-nil, zero value otherwise.

### GetHasImageOk

`func (o *ModelProductImage) GetHasImageOk() (*bool, bool)`

GetHasImageOk returns a tuple with the HasImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasImage

`func (o *ModelProductImage) SetHasImage(v bool)`

SetHasImage sets HasImage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


