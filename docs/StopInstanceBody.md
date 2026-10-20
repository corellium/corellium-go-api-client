# StopInstanceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Soft** | Pointer to **bool** | Controls how the VM is stopped. When true (the default), performs a graceful shutdown. When false, performs a forced, immediate stop. | [optional] [default to true]

## Methods

### NewStopInstanceBody

`func NewStopInstanceBody() *StopInstanceBody`

NewStopInstanceBody instantiates a new StopInstanceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStopInstanceBodyWithDefaults

`func NewStopInstanceBodyWithDefaults() *StopInstanceBody`

NewStopInstanceBodyWithDefaults instantiates a new StopInstanceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSoft

`func (o *StopInstanceBody) GetSoft() bool`

GetSoft returns the Soft field if non-nil, zero value otherwise.

### GetSoftOk

`func (o *StopInstanceBody) GetSoftOk() (*bool, bool)`

GetSoftOk returns a tuple with the Soft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSoft

`func (o *StopInstanceBody) SetSoft(v bool)`

SetSoft sets Soft field to given value.

### HasSoft

`func (o *StopInstanceBody) HasSoft() bool`

HasSoft returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


