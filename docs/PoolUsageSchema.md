# PoolUsageSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Used** | Pointer to **float32** | Used pool space. | [optional] [default to 0]
**Size** | Pointer to **float32** | Total pool size. | [optional] [default to 0]
**Free** | Pointer to **float32** | Free pool space. | [optional] [default to 0]
**LvCount** | Pointer to **float32** | Logical volume count. | [optional] [default to 0]

## Methods

### NewPoolUsageSchema

`func NewPoolUsageSchema() *PoolUsageSchema`

NewPoolUsageSchema instantiates a new PoolUsageSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPoolUsageSchemaWithDefaults

`func NewPoolUsageSchemaWithDefaults() *PoolUsageSchema`

NewPoolUsageSchemaWithDefaults instantiates a new PoolUsageSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsed

`func (o *PoolUsageSchema) GetUsed() float32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *PoolUsageSchema) GetUsedOk() (*float32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *PoolUsageSchema) SetUsed(v float32)`

SetUsed sets Used field to given value.

### HasUsed

`func (o *PoolUsageSchema) HasUsed() bool`

HasUsed returns a boolean if a field has been set.

### GetSize

`func (o *PoolUsageSchema) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *PoolUsageSchema) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *PoolUsageSchema) SetSize(v float32)`

SetSize sets Size field to given value.

### HasSize

`func (o *PoolUsageSchema) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetFree

`func (o *PoolUsageSchema) GetFree() float32`

GetFree returns the Free field if non-nil, zero value otherwise.

### GetFreeOk

`func (o *PoolUsageSchema) GetFreeOk() (*float32, bool)`

GetFreeOk returns a tuple with the Free field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFree

`func (o *PoolUsageSchema) SetFree(v float32)`

SetFree sets Free field to given value.

### HasFree

`func (o *PoolUsageSchema) HasFree() bool`

HasFree returns a boolean if a field has been set.

### GetLvCount

`func (o *PoolUsageSchema) GetLvCount() float32`

GetLvCount returns the LvCount field if non-nil, zero value otherwise.

### GetLvCountOk

`func (o *PoolUsageSchema) GetLvCountOk() (*float32, bool)`

GetLvCountOk returns a tuple with the LvCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLvCount

`func (o *PoolUsageSchema) SetLvCount(v float32)`

SetLvCount sets LvCount field to given value.

### HasLvCount

`func (o *PoolUsageSchema) HasLvCount() bool`

HasLvCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


