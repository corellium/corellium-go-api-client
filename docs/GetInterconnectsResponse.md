# GetInterconnectsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | Pointer to [**[]InterconnectResponse**](InterconnectResponse.md) | Array of interconnects | [optional] 
**Count** | Pointer to **NullableFloat32** | Number of interconnects in this response | [optional] 
**Total** | Pointer to **NullableFloat32** | Total number of interconnects | [optional] 
**Limit** | Pointer to **NullableFloat32** | Limit used for pagination | [optional] 
**Offset** | Pointer to **NullableFloat32** | Offset used for pagination | [optional] 

## Methods

### NewGetInterconnectsResponse

`func NewGetInterconnectsResponse() *GetInterconnectsResponse`

NewGetInterconnectsResponse instantiates a new GetInterconnectsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetInterconnectsResponseWithDefaults

`func NewGetInterconnectsResponseWithDefaults() *GetInterconnectsResponse`

NewGetInterconnectsResponseWithDefaults instantiates a new GetInterconnectsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *GetInterconnectsResponse) GetResults() []InterconnectResponse`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *GetInterconnectsResponse) GetResultsOk() (*[]InterconnectResponse, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *GetInterconnectsResponse) SetResults(v []InterconnectResponse)`

SetResults sets Results field to given value.

### HasResults

`func (o *GetInterconnectsResponse) HasResults() bool`

HasResults returns a boolean if a field has been set.

### SetResultsNil

`func (o *GetInterconnectsResponse) SetResultsNil(b bool)`

 SetResultsNil sets the value for Results to be an explicit nil

### UnsetResults
`func (o *GetInterconnectsResponse) UnsetResults()`

UnsetResults ensures that no value is present for Results, not even an explicit nil
### GetCount

`func (o *GetInterconnectsResponse) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *GetInterconnectsResponse) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *GetInterconnectsResponse) SetCount(v float32)`

SetCount sets Count field to given value.

### HasCount

`func (o *GetInterconnectsResponse) HasCount() bool`

HasCount returns a boolean if a field has been set.

### SetCountNil

`func (o *GetInterconnectsResponse) SetCountNil(b bool)`

 SetCountNil sets the value for Count to be an explicit nil

### UnsetCount
`func (o *GetInterconnectsResponse) UnsetCount()`

UnsetCount ensures that no value is present for Count, not even an explicit nil
### GetTotal

`func (o *GetInterconnectsResponse) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetInterconnectsResponse) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetInterconnectsResponse) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GetInterconnectsResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### SetTotalNil

`func (o *GetInterconnectsResponse) SetTotalNil(b bool)`

 SetTotalNil sets the value for Total to be an explicit nil

### UnsetTotal
`func (o *GetInterconnectsResponse) UnsetTotal()`

UnsetTotal ensures that no value is present for Total, not even an explicit nil
### GetLimit

`func (o *GetInterconnectsResponse) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *GetInterconnectsResponse) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *GetInterconnectsResponse) SetLimit(v float32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *GetInterconnectsResponse) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### SetLimitNil

`func (o *GetInterconnectsResponse) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *GetInterconnectsResponse) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetOffset

`func (o *GetInterconnectsResponse) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *GetInterconnectsResponse) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *GetInterconnectsResponse) SetOffset(v float32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *GetInterconnectsResponse) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### SetOffsetNil

`func (o *GetInterconnectsResponse) SetOffsetNil(b bool)`

 SetOffsetNil sets the value for Offset to be an explicit nil

### UnsetOffset
`func (o *GetInterconnectsResponse) UnsetOffset()`

UnsetOffset ensures that no value is present for Offset, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


