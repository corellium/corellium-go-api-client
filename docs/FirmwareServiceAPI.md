# \FirmwareServiceAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateFirmwareAssets**](FirmwareServiceAPI.md#V3CreateFirmwareAssets) | **Post** /v3/cluster/firmware-service/firmware-assets | Add firmware assets
[**V3DeleteFirmware**](FirmwareServiceAPI.md#V3DeleteFirmware) | **Delete** /v3/cluster/firmware-service/firmwares/{filename} | Delete a firmware
[**V3DeleteFirmwareAsset**](FirmwareServiceAPI.md#V3DeleteFirmwareAsset) | **Delete** /v3/cluster/firmware-service/firmware-assets/{assetUrl} | Delete a firmware asset
[**V3GetFirmwareAssetExtended**](FirmwareServiceAPI.md#V3GetFirmwareAssetExtended) | **Get** /v3/cluster/firmware-service/firmware-assets/{assetUrl}/extended | Get extended firmware asset info
[**V3GetFirmwareServiceConfig**](FirmwareServiceAPI.md#V3GetFirmwareServiceConfig) | **Get** /v3/cluster/firmware-service/config | Get firmware service configuration
[**V3ListFirmwareAssets**](FirmwareServiceAPI.md#V3ListFirmwareAssets) | **Get** /v3/cluster/firmware-service/firmware-assets | List firmware assets
[**V3ListFirmwareDevices**](FirmwareServiceAPI.md#V3ListFirmwareDevices) | **Get** /v3/cluster/firmware-service/devices | List firmware service devices
[**V3ListFirmwares**](FirmwareServiceAPI.md#V3ListFirmwares) | **Get** /v3/cluster/firmware-service/firmwares | List firmwares
[**V3PatchFirmwareServiceConfig**](FirmwareServiceAPI.md#V3PatchFirmwareServiceConfig) | **Patch** /v3/cluster/firmware-service/config | Update firmware service configuration



## V3CreateFirmwareAssets

> string V3CreateFirmwareAssets(ctx).RequestBody(requestBody).Execute()

Add firmware assets



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	requestBody := map[string]string{"key": "Inner_example"} // map[string]string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FirmwareServiceAPI.V3CreateFirmwareAssets(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FirmwareServiceAPI.V3CreateFirmwareAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateFirmwareAssets`: string
	fmt.Fprintf(os.Stdout, "Response from `FirmwareServiceAPI.V3CreateFirmwareAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateFirmwareAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]string** |  | 

### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteFirmware

> V3DeleteFirmware(ctx, filename).Execute()

Delete a firmware



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	filename := "firmware.ipsw" // string | Firmware filename.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FirmwareServiceAPI.V3DeleteFirmware(context.Background(), filename).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FirmwareServiceAPI.V3DeleteFirmware``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**filename** | **string** | Firmware filename. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteFirmwareRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteFirmwareAsset

> V3DeleteFirmwareAsset(ctx, assetUrl).Execute()

Delete a firmware asset



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	assetUrl := "https://example.com/firmware-assets/asset.bin" // string | Firmware asset URL, passed as the raw (un-encoded) value. Generated SDK clients percent-encode it into the request path automatically; only when composing the HTTP request path by hand (e.g. curl) does the caller percent-encode it, once, like any path segment.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FirmwareServiceAPI.V3DeleteFirmwareAsset(context.Background(), assetUrl).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FirmwareServiceAPI.V3DeleteFirmwareAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetUrl** | **string** | Firmware asset URL, passed as the raw (un-encoded) value. Generated SDK clients percent-encode it into the request path automatically; only when composing the HTTP request path by hand (e.g. curl) does the caller percent-encode it, once, like any path segment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteFirmwareAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetFirmwareAssetExtended

> ExtendedFirmwareAssetInfo V3GetFirmwareAssetExtended(ctx, assetUrl).Execute()

Get extended firmware asset info



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	assetUrl := "https://example.com/firmware-assets/asset.bin" // string | Firmware asset URL, passed as the raw (un-encoded) value. Generated SDK clients percent-encode it into the request path automatically; only when composing the HTTP request path by hand (e.g. curl) does the caller percent-encode it, once, like any path segment.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FirmwareServiceAPI.V3GetFirmwareAssetExtended(context.Background(), assetUrl).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FirmwareServiceAPI.V3GetFirmwareAssetExtended``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetFirmwareAssetExtended`: ExtendedFirmwareAssetInfo
	fmt.Fprintf(os.Stdout, "Response from `FirmwareServiceAPI.V3GetFirmwareAssetExtended`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetUrl** | **string** | Firmware asset URL, passed as the raw (un-encoded) value. Generated SDK clients percent-encode it into the request path automatically; only when composing the HTTP request path by hand (e.g. curl) does the caller percent-encode it, once, like any path segment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetFirmwareAssetExtendedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ExtendedFirmwareAssetInfo**](ExtendedFirmwareAssetInfo.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetFirmwareServiceConfig

> FirmwareServiceConfig V3GetFirmwareServiceConfig(ctx).Execute()

Get firmware service configuration



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FirmwareServiceAPI.V3GetFirmwareServiceConfig(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FirmwareServiceAPI.V3GetFirmwareServiceConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetFirmwareServiceConfig`: FirmwareServiceConfig
	fmt.Fprintf(os.Stdout, "Response from `FirmwareServiceAPI.V3GetFirmwareServiceConfig`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetFirmwareServiceConfigRequest struct via the builder pattern


### Return type

[**FirmwareServiceConfig**](FirmwareServiceConfig.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListFirmwareAssets

> FirmwareAssetList V3ListFirmwareAssets(ctx).Limit(limit).Offset(offset).Search(search).Order(order).Filter(filter).Execute()

List firmware assets



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	limit := float32(56) // float32 | Number of results to return. (optional) (default to 100)
	offset := float32(56) // float32 | Index of the first row to return. (optional) (default to 0)
	search := "iPhone13" // string | Case-insensitive partial match across key fields. (optional)
	order := "-createdAt" // string | Comma-separated sort fields; prefix with \"-\" for descending order. (optional)
	filter := *openapiclient.NewFirmwareAssetFilter() // FirmwareAssetFilter | Exact-match filters (filter[url], filter[domain]). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FirmwareServiceAPI.V3ListFirmwareAssets(context.Background()).Limit(limit).Offset(offset).Search(search).Order(order).Filter(filter).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FirmwareServiceAPI.V3ListFirmwareAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListFirmwareAssets`: FirmwareAssetList
	fmt.Fprintf(os.Stdout, "Response from `FirmwareServiceAPI.V3ListFirmwareAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListFirmwareAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Number of results to return. | [default to 100]
 **offset** | **float32** | Index of the first row to return. | [default to 0]
 **search** | **string** | Case-insensitive partial match across key fields. | 
 **order** | **string** | Comma-separated sort fields; prefix with \&quot;-\&quot; for descending order. | 
 **filter** | [**FirmwareAssetFilter**](FirmwareAssetFilter.md) | Exact-match filters (filter[url], filter[domain]). | 

### Return type

[**FirmwareAssetList**](FirmwareAssetList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListFirmwareDevices

> FirmwareDeviceList V3ListFirmwareDevices(ctx).Limit(limit).Offset(offset).Search(search).Order(order).Type_(type_).Model(model).Name(name).Platform(platform).HwModel(hwModel).Execute()

List firmware service devices



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	limit := float32(56) // float32 | Number of results to return. (optional) (default to 100)
	offset := float32(56) // float32 | Index of the first row to return. (optional) (default to 0)
	search := "iPhone13" // string | Case-insensitive partial match across key fields. (optional)
	order := "-createdAt" // string | Comma-separated sort fields; prefix with \"-\" for descending order. (optional)
	type_ := "ios" // string | Filter by exact type. (optional)
	model := "iPhone13,2" // string | Filter by exact model. (optional)
	name := "iPhone 12" // string | Filter by exact name. (optional)
	platform := "t8101" // string | Filter by exact platform. (optional)
	hwModel := "d53gap" // string | Filter by exact hardware model. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FirmwareServiceAPI.V3ListFirmwareDevices(context.Background()).Limit(limit).Offset(offset).Search(search).Order(order).Type_(type_).Model(model).Name(name).Platform(platform).HwModel(hwModel).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FirmwareServiceAPI.V3ListFirmwareDevices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListFirmwareDevices`: FirmwareDeviceList
	fmt.Fprintf(os.Stdout, "Response from `FirmwareServiceAPI.V3ListFirmwareDevices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListFirmwareDevicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Number of results to return. | [default to 100]
 **offset** | **float32** | Index of the first row to return. | [default to 0]
 **search** | **string** | Case-insensitive partial match across key fields. | 
 **order** | **string** | Comma-separated sort fields; prefix with \&quot;-\&quot; for descending order. | 
 **type_** | **string** | Filter by exact type. | 
 **model** | **string** | Filter by exact model. | 
 **name** | **string** | Filter by exact name. | 
 **platform** | **string** | Filter by exact platform. | 
 **hwModel** | **string** | Filter by exact hardware model. | 

### Return type

[**FirmwareDeviceList**](FirmwareDeviceList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListFirmwares

> FirmwareList V3ListFirmwares(ctx).Limit(limit).Offset(offset).Search(search).Order(order).Filename(filename).Model(model).Type_(type_).Version(version).BuildId(buildId).FirmwareAssets(firmwareAssets).CorelliumChecksum(corelliumChecksum).Installed(installed).Execute()

List firmwares



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	limit := float32(56) // float32 | Number of results to return. (optional) (default to 100)
	offset := float32(56) // float32 | Index of the first row to return. (optional) (default to 0)
	search := "iPhone13" // string | Case-insensitive partial match across key fields. (optional)
	order := "-createdAt" // string | Comma-separated sort fields; prefix with \"-\" for descending order. (optional)
	filename := "firmware.ipsw" // string | Filter by exact filename. (optional)
	model := "iPhone13,2" // string | Filter by exact model. (optional)
	type_ := "ios" // string | Filter by exact type. (optional)
	version := "17.5" // string | Filter by exact version. (optional)
	buildId := "21F79" // string | Filter by exact build ID. (optional)
	firmwareAssets := "https://example.com/firmware-assets/asset.bin" // string | Filter by exact asset URL/ID. (optional)
	corelliumChecksum := "sha256$1048576$2cf24dba5fb0a30e26e83b2ac5b9e29e1b161e5c1fa7425e73043362938b9824" // string | Filter by exact Corellium checksum (upload preflight). (optional)
	installed := true // bool | Filter by installed status. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FirmwareServiceAPI.V3ListFirmwares(context.Background()).Limit(limit).Offset(offset).Search(search).Order(order).Filename(filename).Model(model).Type_(type_).Version(version).BuildId(buildId).FirmwareAssets(firmwareAssets).CorelliumChecksum(corelliumChecksum).Installed(installed).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FirmwareServiceAPI.V3ListFirmwares``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListFirmwares`: FirmwareList
	fmt.Fprintf(os.Stdout, "Response from `FirmwareServiceAPI.V3ListFirmwares`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListFirmwaresRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Number of results to return. | [default to 100]
 **offset** | **float32** | Index of the first row to return. | [default to 0]
 **search** | **string** | Case-insensitive partial match across key fields. | 
 **order** | **string** | Comma-separated sort fields; prefix with \&quot;-\&quot; for descending order. | 
 **filename** | **string** | Filter by exact filename. | 
 **model** | **string** | Filter by exact model. | 
 **type_** | **string** | Filter by exact type. | 
 **version** | **string** | Filter by exact version. | 
 **buildId** | **string** | Filter by exact build ID. | 
 **firmwareAssets** | **string** | Filter by exact asset URL/ID. | 
 **corelliumChecksum** | **string** | Filter by exact Corellium checksum (upload preflight). | 
 **installed** | **bool** | Filter by installed status. | 

### Return type

[**FirmwareList**](FirmwareList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchFirmwareServiceConfig

> FirmwareServiceSettings V3PatchFirmwareServiceConfig(ctx).PatchFirmwareServiceConfigBody(patchFirmwareServiceConfigBody).Execute()

Update firmware service configuration



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	patchFirmwareServiceConfigBody := *openapiclient.NewPatchFirmwareServiceConfigBody() // PatchFirmwareServiceConfigBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FirmwareServiceAPI.V3PatchFirmwareServiceConfig(context.Background()).PatchFirmwareServiceConfigBody(patchFirmwareServiceConfigBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FirmwareServiceAPI.V3PatchFirmwareServiceConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PatchFirmwareServiceConfig`: FirmwareServiceSettings
	fmt.Fprintf(os.Stdout, "Response from `FirmwareServiceAPI.V3PatchFirmwareServiceConfig`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchFirmwareServiceConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **patchFirmwareServiceConfigBody** | [**PatchFirmwareServiceConfigBody**](PatchFirmwareServiceConfigBody.md) |  | 

### Return type

[**FirmwareServiceSettings**](FirmwareServiceSettings.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

