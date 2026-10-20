# FetchFirmwareAssetsBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetUrls** | **[]string** | Firmware asset URLs to fetch server-side (1–100 per request). | 

## Methods

### NewFetchFirmwareAssetsBody

`func NewFetchFirmwareAssetsBody(assetUrls []string, ) *FetchFirmwareAssetsBody`

NewFetchFirmwareAssetsBody instantiates a new FetchFirmwareAssetsBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchFirmwareAssetsBodyWithDefaults

`func NewFetchFirmwareAssetsBodyWithDefaults() *FetchFirmwareAssetsBody`

NewFetchFirmwareAssetsBodyWithDefaults instantiates a new FetchFirmwareAssetsBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetUrls

`func (o *FetchFirmwareAssetsBody) GetAssetUrls() []string`

GetAssetUrls returns the AssetUrls field if non-nil, zero value otherwise.

### GetAssetUrlsOk

`func (o *FetchFirmwareAssetsBody) GetAssetUrlsOk() (*[]string, bool)`

GetAssetUrlsOk returns a tuple with the AssetUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetUrls

`func (o *FetchFirmwareAssetsBody) SetAssetUrls(v []string)`

SetAssetUrls sets AssetUrls field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


