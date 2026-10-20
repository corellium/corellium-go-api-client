# InstanceBootOptionsPongo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Pongo image ID. Uploaded pongo images are keyed by UUID, like other instance images. | 
**Name** | **string** | File name. | 
**Size** | **float32** | File size. | 

## Methods

### NewInstanceBootOptionsPongo

`func NewInstanceBootOptionsPongo(id string, name string, size float32, ) *InstanceBootOptionsPongo`

NewInstanceBootOptionsPongo instantiates a new InstanceBootOptionsPongo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceBootOptionsPongoWithDefaults

`func NewInstanceBootOptionsPongoWithDefaults() *InstanceBootOptionsPongo`

NewInstanceBootOptionsPongoWithDefaults instantiates a new InstanceBootOptionsPongo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InstanceBootOptionsPongo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InstanceBootOptionsPongo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InstanceBootOptionsPongo) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *InstanceBootOptionsPongo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InstanceBootOptionsPongo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InstanceBootOptionsPongo) SetName(v string)`

SetName sets Name field to given value.


### GetSize

`func (o *InstanceBootOptionsPongo) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *InstanceBootOptionsPongo) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *InstanceBootOptionsPongo) SetSize(v float32)`

SetSize sets Size field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


