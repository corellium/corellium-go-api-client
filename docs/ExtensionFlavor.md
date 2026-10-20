# ExtensionFlavor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Device type. | [optional] 
**Flavor** | Pointer to **string** | Human-readable flavor name. | [optional] 
**FlavorId** | Pointer to **string** | Flavor identifier. | [optional] 
**Product** | Pointer to **string** | Product identifier. | [optional] 
**Cores** | Pointer to **float32** | Number of cores. | [optional] 
**Ram** | Pointer to **float32** | RAM in MiB. | [optional] 
**SupportsGdb** | Pointer to **bool** | Whether GDB is supported. | [optional] 
**SupportsSerialConsole** | Pointer to **bool** | Whether a serial console is supported. | [optional] 
**SupportsPresetBootOptions** | Pointer to **bool** | Whether preset boot options are supported. | [optional] 

## Methods

### NewExtensionFlavor

`func NewExtensionFlavor() *ExtensionFlavor`

NewExtensionFlavor instantiates a new ExtensionFlavor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExtensionFlavorWithDefaults

`func NewExtensionFlavorWithDefaults() *ExtensionFlavor`

NewExtensionFlavorWithDefaults instantiates a new ExtensionFlavor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ExtensionFlavor) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ExtensionFlavor) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ExtensionFlavor) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ExtensionFlavor) HasType() bool`

HasType returns a boolean if a field has been set.

### GetFlavor

`func (o *ExtensionFlavor) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *ExtensionFlavor) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *ExtensionFlavor) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.

### HasFlavor

`func (o *ExtensionFlavor) HasFlavor() bool`

HasFlavor returns a boolean if a field has been set.

### GetFlavorId

`func (o *ExtensionFlavor) GetFlavorId() string`

GetFlavorId returns the FlavorId field if non-nil, zero value otherwise.

### GetFlavorIdOk

`func (o *ExtensionFlavor) GetFlavorIdOk() (*string, bool)`

GetFlavorIdOk returns a tuple with the FlavorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavorId

`func (o *ExtensionFlavor) SetFlavorId(v string)`

SetFlavorId sets FlavorId field to given value.

### HasFlavorId

`func (o *ExtensionFlavor) HasFlavorId() bool`

HasFlavorId returns a boolean if a field has been set.

### GetProduct

`func (o *ExtensionFlavor) GetProduct() string`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *ExtensionFlavor) GetProductOk() (*string, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *ExtensionFlavor) SetProduct(v string)`

SetProduct sets Product field to given value.

### HasProduct

`func (o *ExtensionFlavor) HasProduct() bool`

HasProduct returns a boolean if a field has been set.

### GetCores

`func (o *ExtensionFlavor) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *ExtensionFlavor) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *ExtensionFlavor) SetCores(v float32)`

SetCores sets Cores field to given value.

### HasCores

`func (o *ExtensionFlavor) HasCores() bool`

HasCores returns a boolean if a field has been set.

### GetRam

`func (o *ExtensionFlavor) GetRam() float32`

GetRam returns the Ram field if non-nil, zero value otherwise.

### GetRamOk

`func (o *ExtensionFlavor) GetRamOk() (*float32, bool)`

GetRamOk returns a tuple with the Ram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRam

`func (o *ExtensionFlavor) SetRam(v float32)`

SetRam sets Ram field to given value.

### HasRam

`func (o *ExtensionFlavor) HasRam() bool`

HasRam returns a boolean if a field has been set.

### GetSupportsGdb

`func (o *ExtensionFlavor) GetSupportsGdb() bool`

GetSupportsGdb returns the SupportsGdb field if non-nil, zero value otherwise.

### GetSupportsGdbOk

`func (o *ExtensionFlavor) GetSupportsGdbOk() (*bool, bool)`

GetSupportsGdbOk returns a tuple with the SupportsGdb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsGdb

`func (o *ExtensionFlavor) SetSupportsGdb(v bool)`

SetSupportsGdb sets SupportsGdb field to given value.

### HasSupportsGdb

`func (o *ExtensionFlavor) HasSupportsGdb() bool`

HasSupportsGdb returns a boolean if a field has been set.

### GetSupportsSerialConsole

`func (o *ExtensionFlavor) GetSupportsSerialConsole() bool`

GetSupportsSerialConsole returns the SupportsSerialConsole field if non-nil, zero value otherwise.

### GetSupportsSerialConsoleOk

`func (o *ExtensionFlavor) GetSupportsSerialConsoleOk() (*bool, bool)`

GetSupportsSerialConsoleOk returns a tuple with the SupportsSerialConsole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsSerialConsole

`func (o *ExtensionFlavor) SetSupportsSerialConsole(v bool)`

SetSupportsSerialConsole sets SupportsSerialConsole field to given value.

### HasSupportsSerialConsole

`func (o *ExtensionFlavor) HasSupportsSerialConsole() bool`

HasSupportsSerialConsole returns a boolean if a field has been set.

### GetSupportsPresetBootOptions

`func (o *ExtensionFlavor) GetSupportsPresetBootOptions() bool`

GetSupportsPresetBootOptions returns the SupportsPresetBootOptions field if non-nil, zero value otherwise.

### GetSupportsPresetBootOptionsOk

`func (o *ExtensionFlavor) GetSupportsPresetBootOptionsOk() (*bool, bool)`

GetSupportsPresetBootOptionsOk returns a tuple with the SupportsPresetBootOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsPresetBootOptions

`func (o *ExtensionFlavor) SetSupportsPresetBootOptions(v bool)`

SetSupportsPresetBootOptions sets SupportsPresetBootOptions field to given value.

### HasSupportsPresetBootOptions

`func (o *ExtensionFlavor) HasSupportsPresetBootOptions() bool`

HasSupportsPresetBootOptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


