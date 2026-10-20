# \ClusterAdministrationFirmwareServiceAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1CreateAssetsFirmwareService**](ClusterAdministrationFirmwareServiceAPI.md#V1CreateAssetsFirmwareService) | **Post** /v1/cluster/firmware-service/firmware-assets | Add firmware assets via the firmware service
[**V1CreateImage**](ClusterAdministrationFirmwareServiceAPI.md#V1CreateImage) | **Post** /v1/images | Create a new Image
[**V1DeleteAssetFirmwareService**](ClusterAdministrationFirmwareServiceAPI.md#V1DeleteAssetFirmwareService) | **Delete** /v1/cluster/firmware-service/firmware-assets/{assetURL} | Delete a firmware asset by its URL
[**V1DeleteFirmwareFirmwareService**](ClusterAdministrationFirmwareServiceAPI.md#V1DeleteFirmwareFirmwareService) | **Delete** /v1/cluster/firmware-service/firmwares/{filename} | Delete a firmware by filename from the firmware service
[**V1GetAssetExtendedFirmwareService**](ClusterAdministrationFirmwareServiceAPI.md#V1GetAssetExtendedFirmwareService) | **Get** /v1/cluster/firmware-service/firmware-assets/{assetURL}/extended | Fetch extended firmware-asset details including instances and associated IPSWs
[**V1GetConfigFirmwareService**](ClusterAdministrationFirmwareServiceAPI.md#V1GetConfigFirmwareService) | **Get** /v1/cluster/firmware-service/config | Fetch firmware service configuration
[**V1GetInstallFirmwareStatus**](ClusterAdministrationFirmwareServiceAPI.md#V1GetInstallFirmwareStatus) | **Get** /v1/images/install-firmware/{taskId} | Query install firmware request status.
[**V1InstallFirmware**](ClusterAdministrationFirmwareServiceAPI.md#V1InstallFirmware) | **Post** /v1/images/install-firmware | Installs a firmware for cluster-wide use
[**V1InstallFirmwareAssets**](ClusterAdministrationFirmwareServiceAPI.md#V1InstallFirmwareAssets) | **Post** /v1/images/install-firmware-assets | Installs firmware assets for cluster-wide use
[**V1ListAssetsFirmwareService**](ClusterAdministrationFirmwareServiceAPI.md#V1ListAssetsFirmwareService) | **Get** /v1/cluster/firmware-service/firmware-assets | Fetch firmware assets from the firmware service
[**V1ListDevicesFirmwareService**](ClusterAdministrationFirmwareServiceAPI.md#V1ListDevicesFirmwareService) | **Get** /v1/cluster/firmware-service/devices | Fetch devices from the firmware service
[**V1ListFirmwaresFirmwareService**](ClusterAdministrationFirmwareServiceAPI.md#V1ListFirmwaresFirmwareService) | **Get** /v1/cluster/firmware-service/firmwares | Fetch firmwares from the firmware service
[**V1PatchConfigFirmwareService**](ClusterAdministrationFirmwareServiceAPI.md#V1PatchConfigFirmwareService) | **Patch** /v1/cluster/firmware-service/config | Update firmware service configuration
[**V1UploadImageData**](ClusterAdministrationFirmwareServiceAPI.md#V1UploadImageData) | **Post** /v1/images/{imageId} | Upload Image Data



## V1CreateAssetsFirmwareService

> string V1CreateAssetsFirmwareService(ctx).Body(body).Execute()

Add firmware assets via the firmware service



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
	body := map[string]interface{}{ ... } // map[string]interface{} | Firmware assets payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1CreateAssetsFirmwareService(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1CreateAssetsFirmwareService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateAssetsFirmwareService`: string
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1CreateAssetsFirmwareService`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateAssetsFirmwareServiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **map[string]interface{}** | Firmware assets payload | 

### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: text/html, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1CreateImage

> ImageV1 V1CreateImage(ctx).ImageCreationOptions(imageCreationOptions).Execute()

Create a new Image



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
	imageCreationOptions := *openapiclient.NewImageCreationOptions("Type_example", "Encoding_example") // ImageCreationOptions | Image data

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1CreateImage(context.Background()).ImageCreationOptions(imageCreationOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1CreateImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateImage`: ImageV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1CreateImage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **imageCreationOptions** | [**ImageCreationOptions**](ImageCreationOptions.md) | Image data | 

### Return type

[**ImageV1**](ImageV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteAssetFirmwareService

> V1DeleteAssetFirmwareService(ctx, assetURL).Execute()

Delete a firmware asset by its URL



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
	assetURL := "assetURL_example" // string | The raw firmware asset URL. Percent-encode it once when composing the request path by hand.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1DeleteAssetFirmwareService(context.Background(), assetURL).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1DeleteAssetFirmwareService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetURL** | **string** | The raw firmware asset URL. Percent-encode it once when composing the request path by hand. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteAssetFirmwareServiceRequest struct via the builder pattern


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


## V1DeleteFirmwareFirmwareService

> V1DeleteFirmwareFirmwareService(ctx, filename).Execute()

Delete a firmware by filename from the firmware service



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
	filename := "filename_example" // string | The filename of the firmware to delete

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1DeleteFirmwareFirmwareService(context.Background(), filename).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1DeleteFirmwareFirmwareService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**filename** | **string** | The filename of the firmware to delete | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteFirmwareFirmwareServiceRequest struct via the builder pattern


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


## V1GetAssetExtendedFirmwareService

> ExtendedFirmwareAssetInfoV1 V1GetAssetExtendedFirmwareService(ctx, assetURL).Execute()

Fetch extended firmware-asset details including instances and associated IPSWs



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
	assetURL := "assetURL_example" // string | The raw firmware asset URL. Percent-encode it once when composing the request path by hand.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1GetAssetExtendedFirmwareService(context.Background(), assetURL).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1GetAssetExtendedFirmwareService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetAssetExtendedFirmwareService`: ExtendedFirmwareAssetInfoV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1GetAssetExtendedFirmwareService`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetURL** | **string** | The raw firmware asset URL. Percent-encode it once when composing the request path by hand. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetAssetExtendedFirmwareServiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ExtendedFirmwareAssetInfoV1**](ExtendedFirmwareAssetInfoV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetConfigFirmwareService

> V1GetConfigFirmwareService(ctx).Execute()

Fetch firmware service configuration



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
	r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1GetConfigFirmwareService(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1GetConfigFirmwareService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetConfigFirmwareServiceRequest struct via the builder pattern


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


## V1GetInstallFirmwareStatus

> InstallFirmwareResponseV1 V1GetInstallFirmwareStatus(ctx, taskId).Execute()

Query install firmware request status.



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
	taskId := "taskId_example" // string | Task ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1GetInstallFirmwareStatus(context.Background(), taskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1GetInstallFirmwareStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstallFirmwareStatus`: InstallFirmwareResponseV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1GetInstallFirmwareStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**taskId** | **string** | Task ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstallFirmwareStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InstallFirmwareResponseV1**](InstallFirmwareResponseV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1InstallFirmware

> InstallFirmwareResponseV1 V1InstallFirmware(ctx).InstallFirmwareBodyV1(installFirmwareBodyV1).Execute()

Installs a firmware for cluster-wide use



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
	installFirmwareBodyV1 := *openapiclient.NewInstallFirmwareBodyV1("ImageId_example") // InstallFirmwareBodyV1 | User data

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1InstallFirmware(context.Background()).InstallFirmwareBodyV1(installFirmwareBodyV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1InstallFirmware``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1InstallFirmware`: InstallFirmwareResponseV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1InstallFirmware`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1InstallFirmwareRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **installFirmwareBodyV1** | [**InstallFirmwareBodyV1**](InstallFirmwareBodyV1.md) | User data | 

### Return type

[**InstallFirmwareResponseV1**](InstallFirmwareResponseV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1InstallFirmwareAssets

> InstallFirmwareAssetsResponseV1 V1InstallFirmwareAssets(ctx).InstallFirmwareAssetsBodyV1(installFirmwareAssetsBodyV1).Execute()

Installs firmware assets for cluster-wide use



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
	installFirmwareAssetsBodyV1 := *openapiclient.NewInstallFirmwareAssetsBodyV1("ImageId_example") // InstallFirmwareAssetsBodyV1 | User data

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1InstallFirmwareAssets(context.Background()).InstallFirmwareAssetsBodyV1(installFirmwareAssetsBodyV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1InstallFirmwareAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1InstallFirmwareAssets`: InstallFirmwareAssetsResponseV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1InstallFirmwareAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1InstallFirmwareAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **installFirmwareAssetsBodyV1** | [**InstallFirmwareAssetsBodyV1**](InstallFirmwareAssetsBodyV1.md) | User data | 

### Return type

[**InstallFirmwareAssetsResponseV1**](InstallFirmwareAssetsResponseV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListAssetsFirmwareService

> []FirmwareAssetV1 V1ListAssetsFirmwareService(ctx).Limit(limit).Offset(offset).Order(order).Search(search).Execute()

Fetch firmware assets from the firmware service



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
	limit := float32(8.14) // float32 | Number of results to return (min: 1, max: 10000, default: 100) (optional)
	offset := float32(8.14) // float32 | Index of the first row to return (default: 0) (optional)
	order := "order_example" // string | Comma-separated field names for sorting. Prefix with '-' for descending order (e.g., 'url,-domain'). (optional)
	search := "search_example" // string | Case-insensitive partial match across url, domain (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1ListAssetsFirmwareService(context.Background()).Limit(limit).Offset(offset).Order(order).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1ListAssetsFirmwareService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListAssetsFirmwareService`: []FirmwareAssetV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1ListAssetsFirmwareService`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ListAssetsFirmwareServiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Number of results to return (min: 1, max: 10000, default: 100) | 
 **offset** | **float32** | Index of the first row to return (default: 0) | 
 **order** | **string** | Comma-separated field names for sorting. Prefix with &#39;-&#39; for descending order (e.g., &#39;url,-domain&#39;). | 
 **search** | **string** | Case-insensitive partial match across url, domain | 

### Return type

[**[]FirmwareAssetV1**](FirmwareAssetV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListDevicesFirmwareService

> []Device V1ListDevicesFirmwareService(ctx).Limit(limit).Offset(offset).Search(search).Order(order).Type_(type_).Model(model).Name(name).Platform(platform).Execute()

Fetch devices from the firmware service



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
	limit := float32(8.14) // float32 | Number of results to return (min: 1, max: 10000, default: 100) (optional)
	offset := float32(8.14) // float32 | Index of the first row to return (default: 0) (optional)
	search := "search_example" // string | Case-insensitive partial match across name, model, platform, and hwmodel fields (optional)
	order := "order_example" // string | Comma-separated field names for sorting. Prefix with '-' for descending order (e.g., 'name,-platform'). Allowed fields: name, model, type, platform, hwmodel  Filtering options: (optional)
	type_ := "type__example" // string | Filter by exact type. Example: coreimg (optional)
	model := "model_example" // string | Filter by exact model. Example: Example: iPhone8,1 (optional)
	name := "name_example" // string | Filter by exact name. Example: iPhone6s (optional)
	platform := "platform_example" // string | Filter by exact platform. Example: s5l8960x (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1ListDevicesFirmwareService(context.Background()).Limit(limit).Offset(offset).Search(search).Order(order).Type_(type_).Model(model).Name(name).Platform(platform).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1ListDevicesFirmwareService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListDevicesFirmwareService`: []Device
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1ListDevicesFirmwareService`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ListDevicesFirmwareServiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Number of results to return (min: 1, max: 10000, default: 100) | 
 **offset** | **float32** | Index of the first row to return (default: 0) | 
 **search** | **string** | Case-insensitive partial match across name, model, platform, and hwmodel fields | 
 **order** | **string** | Comma-separated field names for sorting. Prefix with &#39;-&#39; for descending order (e.g., &#39;name,-platform&#39;). Allowed fields: name, model, type, platform, hwmodel  Filtering options: | 
 **type_** | **string** | Filter by exact type. Example: coreimg | 
 **model** | **string** | Filter by exact model. Example: Example: iPhone8,1 | 
 **name** | **string** | Filter by exact name. Example: iPhone6s | 
 **platform** | **string** | Filter by exact platform. Example: s5l8960x | 

### Return type

[**[]Device**](Device.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListFirmwaresFirmwareService

> []FirmwareV1 V1ListFirmwaresFirmwareService(ctx).Limit(limit).Offset(offset).Search(search).Order(order).Filename(filename).Model(model).Type_(type_).Version(version).Buildid(buildid).FirmwareAssets(firmwareAssets).Installed(installed).Execute()

Fetch firmwares from the firmware service



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
	limit := float32(8.14) // float32 | Number of results to return (min: 1, max: 10000, default: 100) (optional)
	offset := float32(8.14) // float32 | Index of the first row to return (default: 0) (optional)
	search := "search_example" // string | Case-insensitive partial match across filename, model, type, version and buildid fields (optional)
	order := "order_example" // string | Comma-separated field names for sorting. Prefix with '-' for descending order (e.g., 'name,-platform'). Allowed fields: filename, model, type, version, buildid  Filtering options: (optional)
	filename := "filename_example" // string | Filter by exact filename. Example: iPhone_4.7_P3_12.1.4_16D57_Restore.ipsw (optional)
	model := "model_example" // string | Filter by exact model. Example: iPhone10,4 (optional)
	type_ := "type__example" // string | Filter by exact type. Example: ipsw (optional)
	version := "version_example" // string | Filter by exact version. Example: 12.1.4 (optional)
	buildid := "buildid_example" // string | Filter by exact buildid. Example: 16D57 (optional)
	firmwareAssets := "firmwareAssets_example" // string | Filter by exact asset URL/ID. Example: https://wkms-public.apple.com/fcs-keys/rl_td3o_0EtXT8t6HvVJoeWXnoBuzumHyUTD8-MUaF8= -OR- rl_td3o_0EtXT8t6HvVJoeWXnoBuzumHyUTD8-MUaF8= (optional)
	installed := true // bool | Filter by installed status (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1ListFirmwaresFirmwareService(context.Background()).Limit(limit).Offset(offset).Search(search).Order(order).Filename(filename).Model(model).Type_(type_).Version(version).Buildid(buildid).FirmwareAssets(firmwareAssets).Installed(installed).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1ListFirmwaresFirmwareService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListFirmwaresFirmwareService`: []FirmwareV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1ListFirmwaresFirmwareService`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ListFirmwaresFirmwareServiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Number of results to return (min: 1, max: 10000, default: 100) | 
 **offset** | **float32** | Index of the first row to return (default: 0) | 
 **search** | **string** | Case-insensitive partial match across filename, model, type, version and buildid fields | 
 **order** | **string** | Comma-separated field names for sorting. Prefix with &#39;-&#39; for descending order (e.g., &#39;name,-platform&#39;). Allowed fields: filename, model, type, version, buildid  Filtering options: | 
 **filename** | **string** | Filter by exact filename. Example: iPhone_4.7_P3_12.1.4_16D57_Restore.ipsw | 
 **model** | **string** | Filter by exact model. Example: iPhone10,4 | 
 **type_** | **string** | Filter by exact type. Example: ipsw | 
 **version** | **string** | Filter by exact version. Example: 12.1.4 | 
 **buildid** | **string** | Filter by exact buildid. Example: 16D57 | 
 **firmwareAssets** | **string** | Filter by exact asset URL/ID. Example: https://wkms-public.apple.com/fcs-keys/rl_td3o_0EtXT8t6HvVJoeWXnoBuzumHyUTD8-MUaF8&#x3D; -OR- rl_td3o_0EtXT8t6HvVJoeWXnoBuzumHyUTD8-MUaF8&#x3D; | 
 **installed** | **bool** | Filter by installed status | 

### Return type

[**[]FirmwareV1**](FirmwareV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PatchConfigFirmwareService

> V1PatchConfigFirmwareService(ctx).FirmwareServiceConfiguration(firmwareServiceConfiguration).Execute()

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
	firmwareServiceConfiguration := *openapiclient.NewFirmwareServiceConfiguration() // FirmwareServiceConfiguration | Firmware configuration payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1PatchConfigFirmwareService(context.Background()).FirmwareServiceConfiguration(firmwareServiceConfiguration).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1PatchConfigFirmwareService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1PatchConfigFirmwareServiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **firmwareServiceConfiguration** | [**FirmwareServiceConfiguration**](FirmwareServiceConfiguration.md) | Firmware configuration payload | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UploadImageData

> ImageV1 V1UploadImageData(ctx, imageId).CorelliumChecksum(corelliumChecksum).File(file).Execute()

Upload Image Data



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
	imageId := "imageId_example" // string | Image ID - uuid
	corelliumChecksum := "corelliumChecksum_example" // string | Corellium Checksum of the uploaded firmware (optional)
	file := os.NewFile(1234, "some_file") // *os.File | Optionally the actual file (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationFirmwareServiceAPI.V1UploadImageData(context.Background(), imageId).CorelliumChecksum(corelliumChecksum).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationFirmwareServiceAPI.V1UploadImageData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UploadImageData`: ImageV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationFirmwareServiceAPI.V1UploadImageData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** | Image ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UploadImageDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **corelliumChecksum** | **string** | Corellium Checksum of the uploaded firmware | 
 **file** | ***os.File** | Optionally the actual file | 

### Return type

[**ImageV1**](ImageV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

