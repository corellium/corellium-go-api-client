# PatchFirmwareServiceConfigBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CacheFirmware** | Pointer to **bool** | Cache firmwares in /var/ipsw. | [optional] 
**ClusterFirmwareAssets** | Pointer to **bool** | Assets are cluster-wide. | [optional] 
**FallbackOriginalUrl** | Pointer to **bool** | Use original URL to fetch firmware. | [optional] 
**FetchFirmwareAssets** | Pointer to **bool** | Automatically fetch assets. | [optional] 
**ShouldDownload** | Pointer to **bool** | Download firmwares. | [optional] 
**DownloadIpswFilters** | Pointer to [**[]IpswFilterV3**](IpswFilterV3.md) | Filters controlling which IPSW builds are downloaded. | [optional] 

## Methods

### NewPatchFirmwareServiceConfigBody

`func NewPatchFirmwareServiceConfigBody() *PatchFirmwareServiceConfigBody`

NewPatchFirmwareServiceConfigBody instantiates a new PatchFirmwareServiceConfigBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchFirmwareServiceConfigBodyWithDefaults

`func NewPatchFirmwareServiceConfigBodyWithDefaults() *PatchFirmwareServiceConfigBody`

NewPatchFirmwareServiceConfigBodyWithDefaults instantiates a new PatchFirmwareServiceConfigBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCacheFirmware

`func (o *PatchFirmwareServiceConfigBody) GetCacheFirmware() bool`

GetCacheFirmware returns the CacheFirmware field if non-nil, zero value otherwise.

### GetCacheFirmwareOk

`func (o *PatchFirmwareServiceConfigBody) GetCacheFirmwareOk() (*bool, bool)`

GetCacheFirmwareOk returns a tuple with the CacheFirmware field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCacheFirmware

`func (o *PatchFirmwareServiceConfigBody) SetCacheFirmware(v bool)`

SetCacheFirmware sets CacheFirmware field to given value.

### HasCacheFirmware

`func (o *PatchFirmwareServiceConfigBody) HasCacheFirmware() bool`

HasCacheFirmware returns a boolean if a field has been set.

### GetClusterFirmwareAssets

`func (o *PatchFirmwareServiceConfigBody) GetClusterFirmwareAssets() bool`

GetClusterFirmwareAssets returns the ClusterFirmwareAssets field if non-nil, zero value otherwise.

### GetClusterFirmwareAssetsOk

`func (o *PatchFirmwareServiceConfigBody) GetClusterFirmwareAssetsOk() (*bool, bool)`

GetClusterFirmwareAssetsOk returns a tuple with the ClusterFirmwareAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterFirmwareAssets

`func (o *PatchFirmwareServiceConfigBody) SetClusterFirmwareAssets(v bool)`

SetClusterFirmwareAssets sets ClusterFirmwareAssets field to given value.

### HasClusterFirmwareAssets

`func (o *PatchFirmwareServiceConfigBody) HasClusterFirmwareAssets() bool`

HasClusterFirmwareAssets returns a boolean if a field has been set.

### GetFallbackOriginalUrl

`func (o *PatchFirmwareServiceConfigBody) GetFallbackOriginalUrl() bool`

GetFallbackOriginalUrl returns the FallbackOriginalUrl field if non-nil, zero value otherwise.

### GetFallbackOriginalUrlOk

`func (o *PatchFirmwareServiceConfigBody) GetFallbackOriginalUrlOk() (*bool, bool)`

GetFallbackOriginalUrlOk returns a tuple with the FallbackOriginalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFallbackOriginalUrl

`func (o *PatchFirmwareServiceConfigBody) SetFallbackOriginalUrl(v bool)`

SetFallbackOriginalUrl sets FallbackOriginalUrl field to given value.

### HasFallbackOriginalUrl

`func (o *PatchFirmwareServiceConfigBody) HasFallbackOriginalUrl() bool`

HasFallbackOriginalUrl returns a boolean if a field has been set.

### GetFetchFirmwareAssets

`func (o *PatchFirmwareServiceConfigBody) GetFetchFirmwareAssets() bool`

GetFetchFirmwareAssets returns the FetchFirmwareAssets field if non-nil, zero value otherwise.

### GetFetchFirmwareAssetsOk

`func (o *PatchFirmwareServiceConfigBody) GetFetchFirmwareAssetsOk() (*bool, bool)`

GetFetchFirmwareAssetsOk returns a tuple with the FetchFirmwareAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFetchFirmwareAssets

`func (o *PatchFirmwareServiceConfigBody) SetFetchFirmwareAssets(v bool)`

SetFetchFirmwareAssets sets FetchFirmwareAssets field to given value.

### HasFetchFirmwareAssets

`func (o *PatchFirmwareServiceConfigBody) HasFetchFirmwareAssets() bool`

HasFetchFirmwareAssets returns a boolean if a field has been set.

### GetShouldDownload

`func (o *PatchFirmwareServiceConfigBody) GetShouldDownload() bool`

GetShouldDownload returns the ShouldDownload field if non-nil, zero value otherwise.

### GetShouldDownloadOk

`func (o *PatchFirmwareServiceConfigBody) GetShouldDownloadOk() (*bool, bool)`

GetShouldDownloadOk returns a tuple with the ShouldDownload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShouldDownload

`func (o *PatchFirmwareServiceConfigBody) SetShouldDownload(v bool)`

SetShouldDownload sets ShouldDownload field to given value.

### HasShouldDownload

`func (o *PatchFirmwareServiceConfigBody) HasShouldDownload() bool`

HasShouldDownload returns a boolean if a field has been set.

### GetDownloadIpswFilters

`func (o *PatchFirmwareServiceConfigBody) GetDownloadIpswFilters() []IpswFilterV3`

GetDownloadIpswFilters returns the DownloadIpswFilters field if non-nil, zero value otherwise.

### GetDownloadIpswFiltersOk

`func (o *PatchFirmwareServiceConfigBody) GetDownloadIpswFiltersOk() (*[]IpswFilterV3, bool)`

GetDownloadIpswFiltersOk returns a tuple with the DownloadIpswFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadIpswFilters

`func (o *PatchFirmwareServiceConfigBody) SetDownloadIpswFilters(v []IpswFilterV3)`

SetDownloadIpswFilters sets DownloadIpswFilters field to given value.

### HasDownloadIpswFilters

`func (o *PatchFirmwareServiceConfigBody) HasDownloadIpswFilters() bool`

HasDownloadIpswFilters returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


