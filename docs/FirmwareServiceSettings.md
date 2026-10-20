# FirmwareServiceSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CacheFirmware** | **bool** | Cache firmwares in /var/ipsw. | 
**ClusterFirmwareAssets** | **bool** | Assets are cluster-wide. | 
**FallbackOriginalUrl** | **bool** | Use original URL to fetch firmware. | 
**FetchFirmwareAssets** | **bool** | Automatically fetch assets. | 
**ShouldDownload** | **bool** | Download firmwares. | 
**DownloadIpswFilters** | [**[]IpswFilterV3**](IpswFilterV3.md) | Filters controlling which IPSW builds are downloaded. | 

## Methods

### NewFirmwareServiceSettings

`func NewFirmwareServiceSettings(cacheFirmware bool, clusterFirmwareAssets bool, fallbackOriginalUrl bool, fetchFirmwareAssets bool, shouldDownload bool, downloadIpswFilters []IpswFilterV3, ) *FirmwareServiceSettings`

NewFirmwareServiceSettings instantiates a new FirmwareServiceSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareServiceSettingsWithDefaults

`func NewFirmwareServiceSettingsWithDefaults() *FirmwareServiceSettings`

NewFirmwareServiceSettingsWithDefaults instantiates a new FirmwareServiceSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCacheFirmware

`func (o *FirmwareServiceSettings) GetCacheFirmware() bool`

GetCacheFirmware returns the CacheFirmware field if non-nil, zero value otherwise.

### GetCacheFirmwareOk

`func (o *FirmwareServiceSettings) GetCacheFirmwareOk() (*bool, bool)`

GetCacheFirmwareOk returns a tuple with the CacheFirmware field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCacheFirmware

`func (o *FirmwareServiceSettings) SetCacheFirmware(v bool)`

SetCacheFirmware sets CacheFirmware field to given value.


### GetClusterFirmwareAssets

`func (o *FirmwareServiceSettings) GetClusterFirmwareAssets() bool`

GetClusterFirmwareAssets returns the ClusterFirmwareAssets field if non-nil, zero value otherwise.

### GetClusterFirmwareAssetsOk

`func (o *FirmwareServiceSettings) GetClusterFirmwareAssetsOk() (*bool, bool)`

GetClusterFirmwareAssetsOk returns a tuple with the ClusterFirmwareAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterFirmwareAssets

`func (o *FirmwareServiceSettings) SetClusterFirmwareAssets(v bool)`

SetClusterFirmwareAssets sets ClusterFirmwareAssets field to given value.


### GetFallbackOriginalUrl

`func (o *FirmwareServiceSettings) GetFallbackOriginalUrl() bool`

GetFallbackOriginalUrl returns the FallbackOriginalUrl field if non-nil, zero value otherwise.

### GetFallbackOriginalUrlOk

`func (o *FirmwareServiceSettings) GetFallbackOriginalUrlOk() (*bool, bool)`

GetFallbackOriginalUrlOk returns a tuple with the FallbackOriginalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFallbackOriginalUrl

`func (o *FirmwareServiceSettings) SetFallbackOriginalUrl(v bool)`

SetFallbackOriginalUrl sets FallbackOriginalUrl field to given value.


### GetFetchFirmwareAssets

`func (o *FirmwareServiceSettings) GetFetchFirmwareAssets() bool`

GetFetchFirmwareAssets returns the FetchFirmwareAssets field if non-nil, zero value otherwise.

### GetFetchFirmwareAssetsOk

`func (o *FirmwareServiceSettings) GetFetchFirmwareAssetsOk() (*bool, bool)`

GetFetchFirmwareAssetsOk returns a tuple with the FetchFirmwareAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFetchFirmwareAssets

`func (o *FirmwareServiceSettings) SetFetchFirmwareAssets(v bool)`

SetFetchFirmwareAssets sets FetchFirmwareAssets field to given value.


### GetShouldDownload

`func (o *FirmwareServiceSettings) GetShouldDownload() bool`

GetShouldDownload returns the ShouldDownload field if non-nil, zero value otherwise.

### GetShouldDownloadOk

`func (o *FirmwareServiceSettings) GetShouldDownloadOk() (*bool, bool)`

GetShouldDownloadOk returns a tuple with the ShouldDownload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShouldDownload

`func (o *FirmwareServiceSettings) SetShouldDownload(v bool)`

SetShouldDownload sets ShouldDownload field to given value.


### GetDownloadIpswFilters

`func (o *FirmwareServiceSettings) GetDownloadIpswFilters() []IpswFilterV3`

GetDownloadIpswFilters returns the DownloadIpswFilters field if non-nil, zero value otherwise.

### GetDownloadIpswFiltersOk

`func (o *FirmwareServiceSettings) GetDownloadIpswFiltersOk() (*[]IpswFilterV3, bool)`

GetDownloadIpswFiltersOk returns a tuple with the DownloadIpswFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadIpswFilters

`func (o *FirmwareServiceSettings) SetDownloadIpswFilters(v []IpswFilterV3)`

SetDownloadIpswFilters sets DownloadIpswFilters field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


