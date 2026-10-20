# FirmwareServiceConfigValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **interface{}** | Current setting value. | [optional] 
**Component** | Pointer to **string** | UI component hint. | [optional] 
**Title** | Pointer to **string** | Human-readable title. | [optional] 
**Description** | Pointer to **string** | Setting description. | [optional] 
**Type** | Pointer to **string** | Value type. | [optional] 

## Methods

### NewFirmwareServiceConfigValue

`func NewFirmwareServiceConfigValue() *FirmwareServiceConfigValue`

NewFirmwareServiceConfigValue instantiates a new FirmwareServiceConfigValue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareServiceConfigValueWithDefaults

`func NewFirmwareServiceConfigValueWithDefaults() *FirmwareServiceConfigValue`

NewFirmwareServiceConfigValueWithDefaults instantiates a new FirmwareServiceConfigValue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *FirmwareServiceConfigValue) GetValue() interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *FirmwareServiceConfigValue) GetValueOk() (*interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *FirmwareServiceConfigValue) SetValue(v interface{})`

SetValue sets Value field to given value.

### HasValue

`func (o *FirmwareServiceConfigValue) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *FirmwareServiceConfigValue) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *FirmwareServiceConfigValue) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil
### GetComponent

`func (o *FirmwareServiceConfigValue) GetComponent() string`

GetComponent returns the Component field if non-nil, zero value otherwise.

### GetComponentOk

`func (o *FirmwareServiceConfigValue) GetComponentOk() (*string, bool)`

GetComponentOk returns a tuple with the Component field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponent

`func (o *FirmwareServiceConfigValue) SetComponent(v string)`

SetComponent sets Component field to given value.

### HasComponent

`func (o *FirmwareServiceConfigValue) HasComponent() bool`

HasComponent returns a boolean if a field has been set.

### GetTitle

`func (o *FirmwareServiceConfigValue) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *FirmwareServiceConfigValue) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *FirmwareServiceConfigValue) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *FirmwareServiceConfigValue) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetDescription

`func (o *FirmwareServiceConfigValue) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *FirmwareServiceConfigValue) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *FirmwareServiceConfigValue) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *FirmwareServiceConfigValue) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetType

`func (o *FirmwareServiceConfigValue) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *FirmwareServiceConfigValue) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *FirmwareServiceConfigValue) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *FirmwareServiceConfigValue) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


