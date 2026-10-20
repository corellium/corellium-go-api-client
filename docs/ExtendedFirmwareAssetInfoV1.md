# ExtendedFirmwareAssetInfoV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Firmwares** | **[]string** | Firmware Records from FW Service | 
**Instances** | **[]string** | Instances using one of the firmwares, and thus the asset | 

## Methods

### NewExtendedFirmwareAssetInfoV1

`func NewExtendedFirmwareAssetInfoV1(firmwares []string, instances []string, ) *ExtendedFirmwareAssetInfoV1`

NewExtendedFirmwareAssetInfoV1 instantiates a new ExtendedFirmwareAssetInfoV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExtendedFirmwareAssetInfoV1WithDefaults

`func NewExtendedFirmwareAssetInfoV1WithDefaults() *ExtendedFirmwareAssetInfoV1`

NewExtendedFirmwareAssetInfoV1WithDefaults instantiates a new ExtendedFirmwareAssetInfoV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirmwares

`func (o *ExtendedFirmwareAssetInfoV1) GetFirmwares() []string`

GetFirmwares returns the Firmwares field if non-nil, zero value otherwise.

### GetFirmwaresOk

`func (o *ExtendedFirmwareAssetInfoV1) GetFirmwaresOk() (*[]string, bool)`

GetFirmwaresOk returns a tuple with the Firmwares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmwares

`func (o *ExtendedFirmwareAssetInfoV1) SetFirmwares(v []string)`

SetFirmwares sets Firmwares field to given value.


### GetInstances

`func (o *ExtendedFirmwareAssetInfoV1) GetInstances() []string`

GetInstances returns the Instances field if non-nil, zero value otherwise.

### GetInstancesOk

`func (o *ExtendedFirmwareAssetInfoV1) GetInstancesOk() (*[]string, bool)`

GetInstancesOk returns a tuple with the Instances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstances

`func (o *ExtendedFirmwareAssetInfoV1) SetInstances(v []string)`

SetInstances sets Instances field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


