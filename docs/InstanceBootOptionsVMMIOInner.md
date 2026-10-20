# InstanceBootOptionsVMMIOInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Start** | **string** | Start address for beginning of vMMIO range. | 
**Size** | **string** | The size of the range to use for vMMIO. | 
**Irq** | **string** | System IRQs, 1-16 ranges must be specified | 

## Methods

### NewInstanceBootOptionsVMMIOInner

`func NewInstanceBootOptionsVMMIOInner(start string, size string, irq string, ) *InstanceBootOptionsVMMIOInner`

NewInstanceBootOptionsVMMIOInner instantiates a new InstanceBootOptionsVMMIOInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceBootOptionsVMMIOInnerWithDefaults

`func NewInstanceBootOptionsVMMIOInnerWithDefaults() *InstanceBootOptionsVMMIOInner`

NewInstanceBootOptionsVMMIOInnerWithDefaults instantiates a new InstanceBootOptionsVMMIOInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStart

`func (o *InstanceBootOptionsVMMIOInner) GetStart() string`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *InstanceBootOptionsVMMIOInner) GetStartOk() (*string, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *InstanceBootOptionsVMMIOInner) SetStart(v string)`

SetStart sets Start field to given value.


### GetSize

`func (o *InstanceBootOptionsVMMIOInner) GetSize() string`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *InstanceBootOptionsVMMIOInner) GetSizeOk() (*string, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *InstanceBootOptionsVMMIOInner) SetSize(v string)`

SetSize sets Size field to given value.


### GetIrq

`func (o *InstanceBootOptionsVMMIOInner) GetIrq() string`

GetIrq returns the Irq field if non-nil, zero value otherwise.

### GetIrqOk

`func (o *InstanceBootOptionsVMMIOInner) GetIrqOk() (*string, bool)`

GetIrqOk returns a tuple with the Irq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIrq

`func (o *InstanceBootOptionsVMMIOInner) SetIrq(v string)`

SetIrq sets Irq field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


