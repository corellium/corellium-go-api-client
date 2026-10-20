# GetStorageResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | Pointer to [**[]MediaStoreV1**](MediaStoreV1.md) | Array of storage devices | [optional] 
**Count** | Pointer to **NullableFloat32** | Number of storage devices in this response | [optional] 
**Total** | Pointer to **NullableFloat32** | Total number of storage devices | [optional] 
**Limit** | Pointer to **NullableFloat32** | Limit used for pagination | [optional] 
**Offset** | Pointer to **NullableFloat32** | Offset used for pagination | [optional] 

## Methods

### NewGetStorageResponse

`func NewGetStorageResponse() *GetStorageResponse`

NewGetStorageResponse instantiates a new GetStorageResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetStorageResponseWithDefaults

`func NewGetStorageResponseWithDefaults() *GetStorageResponse`

NewGetStorageResponseWithDefaults instantiates a new GetStorageResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *GetStorageResponse) GetResults() []MediaStoreV1`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *GetStorageResponse) GetResultsOk() (*[]MediaStoreV1, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *GetStorageResponse) SetResults(v []MediaStoreV1)`

SetResults sets Results field to given value.

### HasResults

`func (o *GetStorageResponse) HasResults() bool`

HasResults returns a boolean if a field has been set.

### SetResultsNil

`func (o *GetStorageResponse) SetResultsNil(b bool)`

 SetResultsNil sets the value for Results to be an explicit nil

### UnsetResults
`func (o *GetStorageResponse) UnsetResults()`

UnsetResults ensures that no value is present for Results, not even an explicit nil
### GetCount

`func (o *GetStorageResponse) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *GetStorageResponse) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *GetStorageResponse) SetCount(v float32)`

SetCount sets Count field to given value.

### HasCount

`func (o *GetStorageResponse) HasCount() bool`

HasCount returns a boolean if a field has been set.

### SetCountNil

`func (o *GetStorageResponse) SetCountNil(b bool)`

 SetCountNil sets the value for Count to be an explicit nil

### UnsetCount
`func (o *GetStorageResponse) UnsetCount()`

UnsetCount ensures that no value is present for Count, not even an explicit nil
### GetTotal

`func (o *GetStorageResponse) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetStorageResponse) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetStorageResponse) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GetStorageResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### SetTotalNil

`func (o *GetStorageResponse) SetTotalNil(b bool)`

 SetTotalNil sets the value for Total to be an explicit nil

### UnsetTotal
`func (o *GetStorageResponse) UnsetTotal()`

UnsetTotal ensures that no value is present for Total, not even an explicit nil
### GetLimit

`func (o *GetStorageResponse) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *GetStorageResponse) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *GetStorageResponse) SetLimit(v float32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *GetStorageResponse) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### SetLimitNil

`func (o *GetStorageResponse) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *GetStorageResponse) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetOffset

`func (o *GetStorageResponse) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *GetStorageResponse) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *GetStorageResponse) SetOffset(v float32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *GetStorageResponse) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### SetOffsetNil

`func (o *GetStorageResponse) SetOffsetNil(b bool)`

 SetOffsetNil sets the value for Offset to be an explicit nil

### UnsetOffset
`func (o *GetStorageResponse) UnsetOffset()`

UnsetOffset ensures that no value is present for Offset, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


