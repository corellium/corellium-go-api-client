# EnableBtraceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ranges** | Pointer to **[][]string** | Kernel address ranges to trace, each a &#x60;[start, end]&#x60; pair of hexadecimal addresses. To trace one kernel extension, use its &#x60;range&#x60; from &#x60;v3GetInstanceKcrange&#x60;. | [optional] 

## Methods

### NewEnableBtraceBody

`func NewEnableBtraceBody() *EnableBtraceBody`

NewEnableBtraceBody instantiates a new EnableBtraceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnableBtraceBodyWithDefaults

`func NewEnableBtraceBodyWithDefaults() *EnableBtraceBody`

NewEnableBtraceBodyWithDefaults instantiates a new EnableBtraceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRanges

`func (o *EnableBtraceBody) GetRanges() [][]string`

GetRanges returns the Ranges field if non-nil, zero value otherwise.

### GetRangesOk

`func (o *EnableBtraceBody) GetRangesOk() (*[][]string, bool)`

GetRangesOk returns a tuple with the Ranges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRanges

`func (o *EnableBtraceBody) SetRanges(v [][]string)`

SetRanges sets Ranges field to given value.

### HasRanges

`func (o *EnableBtraceBody) HasRanges() bool`

HasRanges returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


