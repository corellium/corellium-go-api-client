# LoadExtensionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImageId** | **string** | ID of the extension file you uploaded with &#x60;POST /v3/images&#x60; using &#x60;type: \&quot;extension\&quot;&#x60;. | 

## Methods

### NewLoadExtensionBody

`func NewLoadExtensionBody(imageId string, ) *LoadExtensionBody`

NewLoadExtensionBody instantiates a new LoadExtensionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoadExtensionBodyWithDefaults

`func NewLoadExtensionBodyWithDefaults() *LoadExtensionBody`

NewLoadExtensionBodyWithDefaults instantiates a new LoadExtensionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImageId

`func (o *LoadExtensionBody) GetImageId() string`

GetImageId returns the ImageId field if non-nil, zero value otherwise.

### GetImageIdOk

`func (o *LoadExtensionBody) GetImageIdOk() (*string, bool)`

GetImageIdOk returns a tuple with the ImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageId

`func (o *LoadExtensionBody) SetImageId(v string)`

SetImageId sets ImageId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


