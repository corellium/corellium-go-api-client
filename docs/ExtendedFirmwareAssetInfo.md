# ExtendedFirmwareAssetInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Firmwares** | **[]string** | Firmware filenames using this asset. | 
**Instances** | **[]string** | Instance identifiers using one of the firmwares. | 

## Methods

### NewExtendedFirmwareAssetInfo

`func NewExtendedFirmwareAssetInfo(firmwares []string, instances []string, ) *ExtendedFirmwareAssetInfo`

NewExtendedFirmwareAssetInfo instantiates a new ExtendedFirmwareAssetInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExtendedFirmwareAssetInfoWithDefaults

`func NewExtendedFirmwareAssetInfoWithDefaults() *ExtendedFirmwareAssetInfo`

NewExtendedFirmwareAssetInfoWithDefaults instantiates a new ExtendedFirmwareAssetInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirmwares

`func (o *ExtendedFirmwareAssetInfo) GetFirmwares() []string`

GetFirmwares returns the Firmwares field if non-nil, zero value otherwise.

### GetFirmwaresOk

`func (o *ExtendedFirmwareAssetInfo) GetFirmwaresOk() (*[]string, bool)`

GetFirmwaresOk returns a tuple with the Firmwares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmwares

`func (o *ExtendedFirmwareAssetInfo) SetFirmwares(v []string)`

SetFirmwares sets Firmwares field to given value.


### GetInstances

`func (o *ExtendedFirmwareAssetInfo) GetInstances() []string`

GetInstances returns the Instances field if non-nil, zero value otherwise.

### GetInstancesOk

`func (o *ExtendedFirmwareAssetInfo) GetInstancesOk() (*[]string, bool)`

GetInstancesOk returns a tuple with the Instances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstances

`func (o *ExtendedFirmwareAssetInfo) SetInstances(v []string)`

SetInstances sets Instances field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


