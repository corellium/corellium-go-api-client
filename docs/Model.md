# Model

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Device type, e.g. iOS, Android or IoT. | 
**Flavor** | **string** | The model&#39;s identifier, for example \&quot;iphone17a\&quot;. Pass this value as &#x60;flavor&#x60; when you create an instance, and as &#x60;{model}&#x60; when you list its software. | 
**Description** | **NullableString** | Human-readable model name, e.g. \&quot;iPhone Air\&quot;. | 
**Model** | **string** | Marketing model identifier, e.g. \&quot;iPhone18,4\&quot;. | 
**HardwareModel** | **NullableString** | Hardware board model, e.g. \&quot;d23ap\&quot;. | 
**BoardConfig** | **NullableString** | Board configuration identifier. | 
**Platform** | **NullableString** | Device platform. | 
**Cpid** | **NullableFloat32** | Chip ID. | 
**Bdid** | **NullableFloat32** | Board ID. | 
**Vendor** | **NullableString** | Vendor gating this model, when it is vendor-restricted. | 
**Hidden** | **bool** | Whether this model is hidden from device pickers. | 
**IsBeta** | **bool** | Whether this model is a beta device. | 
**Peripherals** | **bool** | Whether the device supports peripherals. | 
**HasSoftware** | **bool** | Whether any software build is available for this model. | 
**SupportsRapidStart** | **bool** | Whether at least one software build for this model can start from a snapshot. | 
**DefaultFirmware** | **NullableString** | Filename pattern that selects the default build. It ignores case. Null if the model has no default. | 
**Cores** | **float32** | Number of CPU cores a new instance of this model gets if you do not choose one. | 
**CoresMin** | **float32** | Fewest CPU cores you can give an instance of this model. | 
**CoresMax** | **float32** | Most CPU cores you can give an instance of this model. | 
**CoresStep** | Pointer to **float32** | If present, core counts must go up in steps of this size between &#x60;coresMin&#x60; and &#x60;coresMax&#x60;. | [optional] 
**CoresAllowed** | Pointer to **[]float32** | If present, the exact core counts you may choose, smallest first. When set, use one of these values. | [optional] 
**Ram** | **float32** | Memory, in MiB (1024 &#x3D; 1 GiB), that a new instance gets if you do not choose an amount. | 
**RamMin** | **float32** | Smallest memory amount, in MiB, you can give an instance of this model. | 
**RamMax** | **float32** | Largest memory amount, in MiB, you can give an instance of this model. | 
**DynamicHardwareChanges** | **bool** | Whether cores and memory can be changed while the instance is running. | 
**Partitions** | [**[]ModelPartition**](ModelPartition.md) | Storage partitions of this model. | 
**Frame** | [**NullableModelFrame**](ModelFrame.md) |  | 
**ProductImage** | [**NullableModelProductImage**](ModelProductImage.md) |  | 
**HasFrameVariant** | **bool** | Whether this model is the bezel-framed variant of its device type. | 
**ShowOptions** | **[]string** | Preset boot options this model offers. | 
**StringUdid** | **bool** | Whether this model takes its UDID as a free-form string. | 
**CharmBootArgs** | Pointer to **[]map[string]interface{}** | Model-specific boot argument field definitions. | [optional] 
**RequiresPresetBootOptions** | **bool** | Whether a preset boot option must be chosen when creating an instance. | 
**SupportsPresetBootOptions** | **bool** | Whether preset boot options are supported. | 
**SupportsCustomFirmware** | **bool** | Whether custom firmware is supported. | 
**SupportsCustomFirmwareImage** | **bool** | Whether a user-supplied firmware image can be uploaded for this model. | 
**SupportsCustomKernel** | **bool** | Whether a custom kernel is supported. | 
**SupportsCustomDevicetree** | **bool** | Whether a custom device tree is supported. | 
**SupportsCustomMmio** | **bool** | Whether custom MMIO configuration is supported. | 
**SupportsFvp** | **bool** | Whether this model is an Arm Fixed Virtual Platform. | 
**Mast** | **bool** | Whether MATRIX security assessments can run on instances of this model. | 

## Methods

### NewModel

`func NewModel(type_ string, flavor string, description NullableString, model string, hardwareModel NullableString, boardConfig NullableString, platform NullableString, cpid NullableFloat32, bdid NullableFloat32, vendor NullableString, hidden bool, isBeta bool, peripherals bool, hasSoftware bool, supportsRapidStart bool, defaultFirmware NullableString, cores float32, coresMin float32, coresMax float32, ram float32, ramMin float32, ramMax float32, dynamicHardwareChanges bool, partitions []ModelPartition, frame NullableModelFrame, productImage NullableModelProductImage, hasFrameVariant bool, showOptions []string, stringUdid bool, requiresPresetBootOptions bool, supportsPresetBootOptions bool, supportsCustomFirmware bool, supportsCustomFirmwareImage bool, supportsCustomKernel bool, supportsCustomDevicetree bool, supportsCustomMmio bool, supportsFvp bool, mast bool, ) *Model`

NewModel instantiates a new Model object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelWithDefaults

`func NewModelWithDefaults() *Model`

NewModelWithDefaults instantiates a new Model object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Model) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Model) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Model) SetType(v string)`

SetType sets Type field to given value.


### GetFlavor

`func (o *Model) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *Model) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *Model) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.


### GetDescription

`func (o *Model) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Model) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Model) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *Model) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Model) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetModel

`func (o *Model) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *Model) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *Model) SetModel(v string)`

SetModel sets Model field to given value.


### GetHardwareModel

`func (o *Model) GetHardwareModel() string`

GetHardwareModel returns the HardwareModel field if non-nil, zero value otherwise.

### GetHardwareModelOk

`func (o *Model) GetHardwareModelOk() (*string, bool)`

GetHardwareModelOk returns a tuple with the HardwareModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHardwareModel

`func (o *Model) SetHardwareModel(v string)`

SetHardwareModel sets HardwareModel field to given value.


### SetHardwareModelNil

`func (o *Model) SetHardwareModelNil(b bool)`

 SetHardwareModelNil sets the value for HardwareModel to be an explicit nil

### UnsetHardwareModel
`func (o *Model) UnsetHardwareModel()`

UnsetHardwareModel ensures that no value is present for HardwareModel, not even an explicit nil
### GetBoardConfig

`func (o *Model) GetBoardConfig() string`

GetBoardConfig returns the BoardConfig field if non-nil, zero value otherwise.

### GetBoardConfigOk

`func (o *Model) GetBoardConfigOk() (*string, bool)`

GetBoardConfigOk returns a tuple with the BoardConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoardConfig

`func (o *Model) SetBoardConfig(v string)`

SetBoardConfig sets BoardConfig field to given value.


### SetBoardConfigNil

`func (o *Model) SetBoardConfigNil(b bool)`

 SetBoardConfigNil sets the value for BoardConfig to be an explicit nil

### UnsetBoardConfig
`func (o *Model) UnsetBoardConfig()`

UnsetBoardConfig ensures that no value is present for BoardConfig, not even an explicit nil
### GetPlatform

`func (o *Model) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *Model) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *Model) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### SetPlatformNil

`func (o *Model) SetPlatformNil(b bool)`

 SetPlatformNil sets the value for Platform to be an explicit nil

### UnsetPlatform
`func (o *Model) UnsetPlatform()`

UnsetPlatform ensures that no value is present for Platform, not even an explicit nil
### GetCpid

`func (o *Model) GetCpid() float32`

GetCpid returns the Cpid field if non-nil, zero value otherwise.

### GetCpidOk

`func (o *Model) GetCpidOk() (*float32, bool)`

GetCpidOk returns a tuple with the Cpid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpid

`func (o *Model) SetCpid(v float32)`

SetCpid sets Cpid field to given value.


### SetCpidNil

`func (o *Model) SetCpidNil(b bool)`

 SetCpidNil sets the value for Cpid to be an explicit nil

### UnsetCpid
`func (o *Model) UnsetCpid()`

UnsetCpid ensures that no value is present for Cpid, not even an explicit nil
### GetBdid

`func (o *Model) GetBdid() float32`

GetBdid returns the Bdid field if non-nil, zero value otherwise.

### GetBdidOk

`func (o *Model) GetBdidOk() (*float32, bool)`

GetBdidOk returns a tuple with the Bdid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBdid

`func (o *Model) SetBdid(v float32)`

SetBdid sets Bdid field to given value.


### SetBdidNil

`func (o *Model) SetBdidNil(b bool)`

 SetBdidNil sets the value for Bdid to be an explicit nil

### UnsetBdid
`func (o *Model) UnsetBdid()`

UnsetBdid ensures that no value is present for Bdid, not even an explicit nil
### GetVendor

`func (o *Model) GetVendor() string`

GetVendor returns the Vendor field if non-nil, zero value otherwise.

### GetVendorOk

`func (o *Model) GetVendorOk() (*string, bool)`

GetVendorOk returns a tuple with the Vendor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendor

`func (o *Model) SetVendor(v string)`

SetVendor sets Vendor field to given value.


### SetVendorNil

`func (o *Model) SetVendorNil(b bool)`

 SetVendorNil sets the value for Vendor to be an explicit nil

### UnsetVendor
`func (o *Model) UnsetVendor()`

UnsetVendor ensures that no value is present for Vendor, not even an explicit nil
### GetHidden

`func (o *Model) GetHidden() bool`

GetHidden returns the Hidden field if non-nil, zero value otherwise.

### GetHiddenOk

`func (o *Model) GetHiddenOk() (*bool, bool)`

GetHiddenOk returns a tuple with the Hidden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHidden

`func (o *Model) SetHidden(v bool)`

SetHidden sets Hidden field to given value.


### GetIsBeta

`func (o *Model) GetIsBeta() bool`

GetIsBeta returns the IsBeta field if non-nil, zero value otherwise.

### GetIsBetaOk

`func (o *Model) GetIsBetaOk() (*bool, bool)`

GetIsBetaOk returns a tuple with the IsBeta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsBeta

`func (o *Model) SetIsBeta(v bool)`

SetIsBeta sets IsBeta field to given value.


### GetPeripherals

`func (o *Model) GetPeripherals() bool`

GetPeripherals returns the Peripherals field if non-nil, zero value otherwise.

### GetPeripheralsOk

`func (o *Model) GetPeripheralsOk() (*bool, bool)`

GetPeripheralsOk returns a tuple with the Peripherals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeripherals

`func (o *Model) SetPeripherals(v bool)`

SetPeripherals sets Peripherals field to given value.


### GetHasSoftware

`func (o *Model) GetHasSoftware() bool`

GetHasSoftware returns the HasSoftware field if non-nil, zero value otherwise.

### GetHasSoftwareOk

`func (o *Model) GetHasSoftwareOk() (*bool, bool)`

GetHasSoftwareOk returns a tuple with the HasSoftware field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasSoftware

`func (o *Model) SetHasSoftware(v bool)`

SetHasSoftware sets HasSoftware field to given value.


### GetSupportsRapidStart

`func (o *Model) GetSupportsRapidStart() bool`

GetSupportsRapidStart returns the SupportsRapidStart field if non-nil, zero value otherwise.

### GetSupportsRapidStartOk

`func (o *Model) GetSupportsRapidStartOk() (*bool, bool)`

GetSupportsRapidStartOk returns a tuple with the SupportsRapidStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsRapidStart

`func (o *Model) SetSupportsRapidStart(v bool)`

SetSupportsRapidStart sets SupportsRapidStart field to given value.


### GetDefaultFirmware

`func (o *Model) GetDefaultFirmware() string`

GetDefaultFirmware returns the DefaultFirmware field if non-nil, zero value otherwise.

### GetDefaultFirmwareOk

`func (o *Model) GetDefaultFirmwareOk() (*string, bool)`

GetDefaultFirmwareOk returns a tuple with the DefaultFirmware field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultFirmware

`func (o *Model) SetDefaultFirmware(v string)`

SetDefaultFirmware sets DefaultFirmware field to given value.


### SetDefaultFirmwareNil

`func (o *Model) SetDefaultFirmwareNil(b bool)`

 SetDefaultFirmwareNil sets the value for DefaultFirmware to be an explicit nil

### UnsetDefaultFirmware
`func (o *Model) UnsetDefaultFirmware()`

UnsetDefaultFirmware ensures that no value is present for DefaultFirmware, not even an explicit nil
### GetCores

`func (o *Model) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *Model) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *Model) SetCores(v float32)`

SetCores sets Cores field to given value.


### GetCoresMin

`func (o *Model) GetCoresMin() float32`

GetCoresMin returns the CoresMin field if non-nil, zero value otherwise.

### GetCoresMinOk

`func (o *Model) GetCoresMinOk() (*float32, bool)`

GetCoresMinOk returns a tuple with the CoresMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoresMin

`func (o *Model) SetCoresMin(v float32)`

SetCoresMin sets CoresMin field to given value.


### GetCoresMax

`func (o *Model) GetCoresMax() float32`

GetCoresMax returns the CoresMax field if non-nil, zero value otherwise.

### GetCoresMaxOk

`func (o *Model) GetCoresMaxOk() (*float32, bool)`

GetCoresMaxOk returns a tuple with the CoresMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoresMax

`func (o *Model) SetCoresMax(v float32)`

SetCoresMax sets CoresMax field to given value.


### GetCoresStep

`func (o *Model) GetCoresStep() float32`

GetCoresStep returns the CoresStep field if non-nil, zero value otherwise.

### GetCoresStepOk

`func (o *Model) GetCoresStepOk() (*float32, bool)`

GetCoresStepOk returns a tuple with the CoresStep field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoresStep

`func (o *Model) SetCoresStep(v float32)`

SetCoresStep sets CoresStep field to given value.

### HasCoresStep

`func (o *Model) HasCoresStep() bool`

HasCoresStep returns a boolean if a field has been set.

### GetCoresAllowed

`func (o *Model) GetCoresAllowed() []float32`

GetCoresAllowed returns the CoresAllowed field if non-nil, zero value otherwise.

### GetCoresAllowedOk

`func (o *Model) GetCoresAllowedOk() (*[]float32, bool)`

GetCoresAllowedOk returns a tuple with the CoresAllowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoresAllowed

`func (o *Model) SetCoresAllowed(v []float32)`

SetCoresAllowed sets CoresAllowed field to given value.

### HasCoresAllowed

`func (o *Model) HasCoresAllowed() bool`

HasCoresAllowed returns a boolean if a field has been set.

### GetRam

`func (o *Model) GetRam() float32`

GetRam returns the Ram field if non-nil, zero value otherwise.

### GetRamOk

`func (o *Model) GetRamOk() (*float32, bool)`

GetRamOk returns a tuple with the Ram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRam

`func (o *Model) SetRam(v float32)`

SetRam sets Ram field to given value.


### GetRamMin

`func (o *Model) GetRamMin() float32`

GetRamMin returns the RamMin field if non-nil, zero value otherwise.

### GetRamMinOk

`func (o *Model) GetRamMinOk() (*float32, bool)`

GetRamMinOk returns a tuple with the RamMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRamMin

`func (o *Model) SetRamMin(v float32)`

SetRamMin sets RamMin field to given value.


### GetRamMax

`func (o *Model) GetRamMax() float32`

GetRamMax returns the RamMax field if non-nil, zero value otherwise.

### GetRamMaxOk

`func (o *Model) GetRamMaxOk() (*float32, bool)`

GetRamMaxOk returns a tuple with the RamMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRamMax

`func (o *Model) SetRamMax(v float32)`

SetRamMax sets RamMax field to given value.


### GetDynamicHardwareChanges

`func (o *Model) GetDynamicHardwareChanges() bool`

GetDynamicHardwareChanges returns the DynamicHardwareChanges field if non-nil, zero value otherwise.

### GetDynamicHardwareChangesOk

`func (o *Model) GetDynamicHardwareChangesOk() (*bool, bool)`

GetDynamicHardwareChangesOk returns a tuple with the DynamicHardwareChanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDynamicHardwareChanges

`func (o *Model) SetDynamicHardwareChanges(v bool)`

SetDynamicHardwareChanges sets DynamicHardwareChanges field to given value.


### GetPartitions

`func (o *Model) GetPartitions() []ModelPartition`

GetPartitions returns the Partitions field if non-nil, zero value otherwise.

### GetPartitionsOk

`func (o *Model) GetPartitionsOk() (*[]ModelPartition, bool)`

GetPartitionsOk returns a tuple with the Partitions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartitions

`func (o *Model) SetPartitions(v []ModelPartition)`

SetPartitions sets Partitions field to given value.


### GetFrame

`func (o *Model) GetFrame() ModelFrame`

GetFrame returns the Frame field if non-nil, zero value otherwise.

### GetFrameOk

`func (o *Model) GetFrameOk() (*ModelFrame, bool)`

GetFrameOk returns a tuple with the Frame field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrame

`func (o *Model) SetFrame(v ModelFrame)`

SetFrame sets Frame field to given value.


### SetFrameNil

`func (o *Model) SetFrameNil(b bool)`

 SetFrameNil sets the value for Frame to be an explicit nil

### UnsetFrame
`func (o *Model) UnsetFrame()`

UnsetFrame ensures that no value is present for Frame, not even an explicit nil
### GetProductImage

`func (o *Model) GetProductImage() ModelProductImage`

GetProductImage returns the ProductImage field if non-nil, zero value otherwise.

### GetProductImageOk

`func (o *Model) GetProductImageOk() (*ModelProductImage, bool)`

GetProductImageOk returns a tuple with the ProductImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductImage

`func (o *Model) SetProductImage(v ModelProductImage)`

SetProductImage sets ProductImage field to given value.


### SetProductImageNil

`func (o *Model) SetProductImageNil(b bool)`

 SetProductImageNil sets the value for ProductImage to be an explicit nil

### UnsetProductImage
`func (o *Model) UnsetProductImage()`

UnsetProductImage ensures that no value is present for ProductImage, not even an explicit nil
### GetHasFrameVariant

`func (o *Model) GetHasFrameVariant() bool`

GetHasFrameVariant returns the HasFrameVariant field if non-nil, zero value otherwise.

### GetHasFrameVariantOk

`func (o *Model) GetHasFrameVariantOk() (*bool, bool)`

GetHasFrameVariantOk returns a tuple with the HasFrameVariant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasFrameVariant

`func (o *Model) SetHasFrameVariant(v bool)`

SetHasFrameVariant sets HasFrameVariant field to given value.


### GetShowOptions

`func (o *Model) GetShowOptions() []string`

GetShowOptions returns the ShowOptions field if non-nil, zero value otherwise.

### GetShowOptionsOk

`func (o *Model) GetShowOptionsOk() (*[]string, bool)`

GetShowOptionsOk returns a tuple with the ShowOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowOptions

`func (o *Model) SetShowOptions(v []string)`

SetShowOptions sets ShowOptions field to given value.


### GetStringUdid

`func (o *Model) GetStringUdid() bool`

GetStringUdid returns the StringUdid field if non-nil, zero value otherwise.

### GetStringUdidOk

`func (o *Model) GetStringUdidOk() (*bool, bool)`

GetStringUdidOk returns a tuple with the StringUdid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringUdid

`func (o *Model) SetStringUdid(v bool)`

SetStringUdid sets StringUdid field to given value.


### GetCharmBootArgs

`func (o *Model) GetCharmBootArgs() []map[string]interface{}`

GetCharmBootArgs returns the CharmBootArgs field if non-nil, zero value otherwise.

### GetCharmBootArgsOk

`func (o *Model) GetCharmBootArgsOk() (*[]map[string]interface{}, bool)`

GetCharmBootArgsOk returns a tuple with the CharmBootArgs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharmBootArgs

`func (o *Model) SetCharmBootArgs(v []map[string]interface{})`

SetCharmBootArgs sets CharmBootArgs field to given value.

### HasCharmBootArgs

`func (o *Model) HasCharmBootArgs() bool`

HasCharmBootArgs returns a boolean if a field has been set.

### GetRequiresPresetBootOptions

`func (o *Model) GetRequiresPresetBootOptions() bool`

GetRequiresPresetBootOptions returns the RequiresPresetBootOptions field if non-nil, zero value otherwise.

### GetRequiresPresetBootOptionsOk

`func (o *Model) GetRequiresPresetBootOptionsOk() (*bool, bool)`

GetRequiresPresetBootOptionsOk returns a tuple with the RequiresPresetBootOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiresPresetBootOptions

`func (o *Model) SetRequiresPresetBootOptions(v bool)`

SetRequiresPresetBootOptions sets RequiresPresetBootOptions field to given value.


### GetSupportsPresetBootOptions

`func (o *Model) GetSupportsPresetBootOptions() bool`

GetSupportsPresetBootOptions returns the SupportsPresetBootOptions field if non-nil, zero value otherwise.

### GetSupportsPresetBootOptionsOk

`func (o *Model) GetSupportsPresetBootOptionsOk() (*bool, bool)`

GetSupportsPresetBootOptionsOk returns a tuple with the SupportsPresetBootOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsPresetBootOptions

`func (o *Model) SetSupportsPresetBootOptions(v bool)`

SetSupportsPresetBootOptions sets SupportsPresetBootOptions field to given value.


### GetSupportsCustomFirmware

`func (o *Model) GetSupportsCustomFirmware() bool`

GetSupportsCustomFirmware returns the SupportsCustomFirmware field if non-nil, zero value otherwise.

### GetSupportsCustomFirmwareOk

`func (o *Model) GetSupportsCustomFirmwareOk() (*bool, bool)`

GetSupportsCustomFirmwareOk returns a tuple with the SupportsCustomFirmware field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsCustomFirmware

`func (o *Model) SetSupportsCustomFirmware(v bool)`

SetSupportsCustomFirmware sets SupportsCustomFirmware field to given value.


### GetSupportsCustomFirmwareImage

`func (o *Model) GetSupportsCustomFirmwareImage() bool`

GetSupportsCustomFirmwareImage returns the SupportsCustomFirmwareImage field if non-nil, zero value otherwise.

### GetSupportsCustomFirmwareImageOk

`func (o *Model) GetSupportsCustomFirmwareImageOk() (*bool, bool)`

GetSupportsCustomFirmwareImageOk returns a tuple with the SupportsCustomFirmwareImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsCustomFirmwareImage

`func (o *Model) SetSupportsCustomFirmwareImage(v bool)`

SetSupportsCustomFirmwareImage sets SupportsCustomFirmwareImage field to given value.


### GetSupportsCustomKernel

`func (o *Model) GetSupportsCustomKernel() bool`

GetSupportsCustomKernel returns the SupportsCustomKernel field if non-nil, zero value otherwise.

### GetSupportsCustomKernelOk

`func (o *Model) GetSupportsCustomKernelOk() (*bool, bool)`

GetSupportsCustomKernelOk returns a tuple with the SupportsCustomKernel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsCustomKernel

`func (o *Model) SetSupportsCustomKernel(v bool)`

SetSupportsCustomKernel sets SupportsCustomKernel field to given value.


### GetSupportsCustomDevicetree

`func (o *Model) GetSupportsCustomDevicetree() bool`

GetSupportsCustomDevicetree returns the SupportsCustomDevicetree field if non-nil, zero value otherwise.

### GetSupportsCustomDevicetreeOk

`func (o *Model) GetSupportsCustomDevicetreeOk() (*bool, bool)`

GetSupportsCustomDevicetreeOk returns a tuple with the SupportsCustomDevicetree field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsCustomDevicetree

`func (o *Model) SetSupportsCustomDevicetree(v bool)`

SetSupportsCustomDevicetree sets SupportsCustomDevicetree field to given value.


### GetSupportsCustomMmio

`func (o *Model) GetSupportsCustomMmio() bool`

GetSupportsCustomMmio returns the SupportsCustomMmio field if non-nil, zero value otherwise.

### GetSupportsCustomMmioOk

`func (o *Model) GetSupportsCustomMmioOk() (*bool, bool)`

GetSupportsCustomMmioOk returns a tuple with the SupportsCustomMmio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsCustomMmio

`func (o *Model) SetSupportsCustomMmio(v bool)`

SetSupportsCustomMmio sets SupportsCustomMmio field to given value.


### GetSupportsFvp

`func (o *Model) GetSupportsFvp() bool`

GetSupportsFvp returns the SupportsFvp field if non-nil, zero value otherwise.

### GetSupportsFvpOk

`func (o *Model) GetSupportsFvpOk() (*bool, bool)`

GetSupportsFvpOk returns a tuple with the SupportsFvp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsFvp

`func (o *Model) SetSupportsFvp(v bool)`

SetSupportsFvp sets SupportsFvp field to given value.


### GetMast

`func (o *Model) GetMast() bool`

GetMast returns the Mast field if non-nil, zero value otherwise.

### GetMastOk

`func (o *Model) GetMastOk() (*bool, bool)`

GetMastOk returns a tuple with the Mast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMast

`func (o *Model) SetMast(v bool)`

SetMast sets Mast field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


