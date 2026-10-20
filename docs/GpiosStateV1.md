# GpiosStateV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Led** | Pointer to [**GpioStateDefinitionV1**](GpioStateDefinitionV1.md) |  | [optional] 
**Button** | Pointer to [**GpioStateDefinitionV1**](GpioStateDefinitionV1.md) |  | [optional] 
**Switch** | Pointer to [**GpioStateDefinitionV1**](GpioStateDefinitionV1.md) |  | [optional] 

## Methods

### NewGpiosStateV1

`func NewGpiosStateV1() *GpiosStateV1`

NewGpiosStateV1 instantiates a new GpiosStateV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGpiosStateV1WithDefaults

`func NewGpiosStateV1WithDefaults() *GpiosStateV1`

NewGpiosStateV1WithDefaults instantiates a new GpiosStateV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLed

`func (o *GpiosStateV1) GetLed() GpioStateDefinitionV1`

GetLed returns the Led field if non-nil, zero value otherwise.

### GetLedOk

`func (o *GpiosStateV1) GetLedOk() (*GpioStateDefinitionV1, bool)`

GetLedOk returns a tuple with the Led field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLed

`func (o *GpiosStateV1) SetLed(v GpioStateDefinitionV1)`

SetLed sets Led field to given value.

### HasLed

`func (o *GpiosStateV1) HasLed() bool`

HasLed returns a boolean if a field has been set.

### GetButton

`func (o *GpiosStateV1) GetButton() GpioStateDefinitionV1`

GetButton returns the Button field if non-nil, zero value otherwise.

### GetButtonOk

`func (o *GpiosStateV1) GetButtonOk() (*GpioStateDefinitionV1, bool)`

GetButtonOk returns a tuple with the Button field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetButton

`func (o *GpiosStateV1) SetButton(v GpioStateDefinitionV1)`

SetButton sets Button field to given value.

### HasButton

`func (o *GpiosStateV1) HasButton() bool`

HasButton returns a boolean if a field has been set.

### GetSwitch

`func (o *GpiosStateV1) GetSwitch() GpioStateDefinitionV1`

GetSwitch returns the Switch field if non-nil, zero value otherwise.

### GetSwitchOk

`func (o *GpiosStateV1) GetSwitchOk() (*GpioStateDefinitionV1, bool)`

GetSwitchOk returns a tuple with the Switch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwitch

`func (o *GpiosStateV1) SetSwitch(v GpioStateDefinitionV1)`

SetSwitch sets Switch field to given value.

### HasSwitch

`func (o *GpiosStateV1) HasSwitch() bool`

HasSwitch returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


