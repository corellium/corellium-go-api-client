# StartInstanceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Paused** | Pointer to **bool** | Start device paused. | [optional] 
**SockCap** | Pointer to **bool** | Start device with Process Network Monitoring enabled. | [optional] 

## Methods

### NewStartInstanceBody

`func NewStartInstanceBody() *StartInstanceBody`

NewStartInstanceBody instantiates a new StartInstanceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStartInstanceBodyWithDefaults

`func NewStartInstanceBodyWithDefaults() *StartInstanceBody`

NewStartInstanceBodyWithDefaults instantiates a new StartInstanceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPaused

`func (o *StartInstanceBody) GetPaused() bool`

GetPaused returns the Paused field if non-nil, zero value otherwise.

### GetPausedOk

`func (o *StartInstanceBody) GetPausedOk() (*bool, bool)`

GetPausedOk returns a tuple with the Paused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaused

`func (o *StartInstanceBody) SetPaused(v bool)`

SetPaused sets Paused field to given value.

### HasPaused

`func (o *StartInstanceBody) HasPaused() bool`

HasPaused returns a boolean if a field has been set.

### GetSockCap

`func (o *StartInstanceBody) GetSockCap() bool`

GetSockCap returns the SockCap field if non-nil, zero value otherwise.

### GetSockCapOk

`func (o *StartInstanceBody) GetSockCapOk() (*bool, bool)`

GetSockCapOk returns a tuple with the SockCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSockCap

`func (o *StartInstanceBody) SetSockCap(v bool)`

SetSockCap sets SockCap field to given value.

### HasSockCap

`func (o *StartInstanceBody) HasSockCap() bool`

HasSockCap returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


