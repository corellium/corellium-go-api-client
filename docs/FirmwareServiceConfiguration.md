# FirmwareServiceConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CacheFirmware** | Pointer to **NullableBool** | Cache Firmwares in /var/ipsw | [optional] 
**ClusterFirmwareAssets** | Pointer to **NullableBool** | Assets are cluster-wide | [optional] 
**FallbackOriginalUrl** | Pointer to **NullableBool** | Use original URL to fetch firmware | [optional] 
**FetchFirmwareAssets** | Pointer to **NullableBool** | Automatically fetch assets | [optional] 
**ShouldDownload** | Pointer to **NullableBool** | Download firmwares | [optional] 
**DownloadIpswFilters** | Pointer to [**[]IpswFilter**](IpswFilter.md) | Filters that control which IPSW builds are downloaded | [optional] 

## Methods

### NewFirmwareServiceConfiguration

`func NewFirmwareServiceConfiguration() *FirmwareServiceConfiguration`

NewFirmwareServiceConfiguration instantiates a new FirmwareServiceConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareServiceConfigurationWithDefaults

`func NewFirmwareServiceConfigurationWithDefaults() *FirmwareServiceConfiguration`

NewFirmwareServiceConfigurationWithDefaults instantiates a new FirmwareServiceConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCacheFirmware

`func (o *FirmwareServiceConfiguration) GetCacheFirmware() bool`

GetCacheFirmware returns the CacheFirmware field if non-nil, zero value otherwise.

### GetCacheFirmwareOk

`func (o *FirmwareServiceConfiguration) GetCacheFirmwareOk() (*bool, bool)`

GetCacheFirmwareOk returns a tuple with the CacheFirmware field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCacheFirmware

`func (o *FirmwareServiceConfiguration) SetCacheFirmware(v bool)`

SetCacheFirmware sets CacheFirmware field to given value.

### HasCacheFirmware

`func (o *FirmwareServiceConfiguration) HasCacheFirmware() bool`

HasCacheFirmware returns a boolean if a field has been set.

### SetCacheFirmwareNil

`func (o *FirmwareServiceConfiguration) SetCacheFirmwareNil(b bool)`

 SetCacheFirmwareNil sets the value for CacheFirmware to be an explicit nil

### UnsetCacheFirmware
`func (o *FirmwareServiceConfiguration) UnsetCacheFirmware()`

UnsetCacheFirmware ensures that no value is present for CacheFirmware, not even an explicit nil
### GetClusterFirmwareAssets

`func (o *FirmwareServiceConfiguration) GetClusterFirmwareAssets() bool`

GetClusterFirmwareAssets returns the ClusterFirmwareAssets field if non-nil, zero value otherwise.

### GetClusterFirmwareAssetsOk

`func (o *FirmwareServiceConfiguration) GetClusterFirmwareAssetsOk() (*bool, bool)`

GetClusterFirmwareAssetsOk returns a tuple with the ClusterFirmwareAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterFirmwareAssets

`func (o *FirmwareServiceConfiguration) SetClusterFirmwareAssets(v bool)`

SetClusterFirmwareAssets sets ClusterFirmwareAssets field to given value.

### HasClusterFirmwareAssets

`func (o *FirmwareServiceConfiguration) HasClusterFirmwareAssets() bool`

HasClusterFirmwareAssets returns a boolean if a field has been set.

### SetClusterFirmwareAssetsNil

`func (o *FirmwareServiceConfiguration) SetClusterFirmwareAssetsNil(b bool)`

 SetClusterFirmwareAssetsNil sets the value for ClusterFirmwareAssets to be an explicit nil

### UnsetClusterFirmwareAssets
`func (o *FirmwareServiceConfiguration) UnsetClusterFirmwareAssets()`

UnsetClusterFirmwareAssets ensures that no value is present for ClusterFirmwareAssets, not even an explicit nil
### GetFallbackOriginalUrl

`func (o *FirmwareServiceConfiguration) GetFallbackOriginalUrl() bool`

GetFallbackOriginalUrl returns the FallbackOriginalUrl field if non-nil, zero value otherwise.

### GetFallbackOriginalUrlOk

`func (o *FirmwareServiceConfiguration) GetFallbackOriginalUrlOk() (*bool, bool)`

GetFallbackOriginalUrlOk returns a tuple with the FallbackOriginalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFallbackOriginalUrl

`func (o *FirmwareServiceConfiguration) SetFallbackOriginalUrl(v bool)`

SetFallbackOriginalUrl sets FallbackOriginalUrl field to given value.

### HasFallbackOriginalUrl

`func (o *FirmwareServiceConfiguration) HasFallbackOriginalUrl() bool`

HasFallbackOriginalUrl returns a boolean if a field has been set.

### SetFallbackOriginalUrlNil

`func (o *FirmwareServiceConfiguration) SetFallbackOriginalUrlNil(b bool)`

 SetFallbackOriginalUrlNil sets the value for FallbackOriginalUrl to be an explicit nil

### UnsetFallbackOriginalUrl
`func (o *FirmwareServiceConfiguration) UnsetFallbackOriginalUrl()`

UnsetFallbackOriginalUrl ensures that no value is present for FallbackOriginalUrl, not even an explicit nil
### GetFetchFirmwareAssets

`func (o *FirmwareServiceConfiguration) GetFetchFirmwareAssets() bool`

GetFetchFirmwareAssets returns the FetchFirmwareAssets field if non-nil, zero value otherwise.

### GetFetchFirmwareAssetsOk

`func (o *FirmwareServiceConfiguration) GetFetchFirmwareAssetsOk() (*bool, bool)`

GetFetchFirmwareAssetsOk returns a tuple with the FetchFirmwareAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFetchFirmwareAssets

`func (o *FirmwareServiceConfiguration) SetFetchFirmwareAssets(v bool)`

SetFetchFirmwareAssets sets FetchFirmwareAssets field to given value.

### HasFetchFirmwareAssets

`func (o *FirmwareServiceConfiguration) HasFetchFirmwareAssets() bool`

HasFetchFirmwareAssets returns a boolean if a field has been set.

### SetFetchFirmwareAssetsNil

`func (o *FirmwareServiceConfiguration) SetFetchFirmwareAssetsNil(b bool)`

 SetFetchFirmwareAssetsNil sets the value for FetchFirmwareAssets to be an explicit nil

### UnsetFetchFirmwareAssets
`func (o *FirmwareServiceConfiguration) UnsetFetchFirmwareAssets()`

UnsetFetchFirmwareAssets ensures that no value is present for FetchFirmwareAssets, not even an explicit nil
### GetShouldDownload

`func (o *FirmwareServiceConfiguration) GetShouldDownload() bool`

GetShouldDownload returns the ShouldDownload field if non-nil, zero value otherwise.

### GetShouldDownloadOk

`func (o *FirmwareServiceConfiguration) GetShouldDownloadOk() (*bool, bool)`

GetShouldDownloadOk returns a tuple with the ShouldDownload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShouldDownload

`func (o *FirmwareServiceConfiguration) SetShouldDownload(v bool)`

SetShouldDownload sets ShouldDownload field to given value.

### HasShouldDownload

`func (o *FirmwareServiceConfiguration) HasShouldDownload() bool`

HasShouldDownload returns a boolean if a field has been set.

### SetShouldDownloadNil

`func (o *FirmwareServiceConfiguration) SetShouldDownloadNil(b bool)`

 SetShouldDownloadNil sets the value for ShouldDownload to be an explicit nil

### UnsetShouldDownload
`func (o *FirmwareServiceConfiguration) UnsetShouldDownload()`

UnsetShouldDownload ensures that no value is present for ShouldDownload, not even an explicit nil
### GetDownloadIpswFilters

`func (o *FirmwareServiceConfiguration) GetDownloadIpswFilters() []IpswFilter`

GetDownloadIpswFilters returns the DownloadIpswFilters field if non-nil, zero value otherwise.

### GetDownloadIpswFiltersOk

`func (o *FirmwareServiceConfiguration) GetDownloadIpswFiltersOk() (*[]IpswFilter, bool)`

GetDownloadIpswFiltersOk returns a tuple with the DownloadIpswFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadIpswFilters

`func (o *FirmwareServiceConfiguration) SetDownloadIpswFilters(v []IpswFilter)`

SetDownloadIpswFilters sets DownloadIpswFilters field to given value.

### HasDownloadIpswFilters

`func (o *FirmwareServiceConfiguration) HasDownloadIpswFilters() bool`

HasDownloadIpswFilters returns a boolean if a field has been set.

### SetDownloadIpswFiltersNil

`func (o *FirmwareServiceConfiguration) SetDownloadIpswFiltersNil(b bool)`

 SetDownloadIpswFiltersNil sets the value for DownloadIpswFilters to be an explicit nil

### UnsetDownloadIpswFilters
`func (o *FirmwareServiceConfiguration) UnsetDownloadIpswFilters()`

UnsetDownloadIpswFilters ensures that no value is present for DownloadIpswFilters, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


