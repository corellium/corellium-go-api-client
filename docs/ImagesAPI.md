# \ImagesAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateImage**](ImagesAPI.md#V3CreateImage) | **Post** /v3/images | Create an image
[**V3DeleteImage**](ImagesAPI.md#V3DeleteImage) | **Delete** /v3/images/{imageId} | Delete an image
[**V3GetImage**](ImagesAPI.md#V3GetImage) | **Get** /v3/images/{imageId} | Get image metadata
[**V3GetImageChunk**](ImagesAPI.md#V3GetImageChunk) | **Get** /v3/images/{imageId}/file | Check whether an image chunk was already uploaded
[**V3GetImageFirmwareInfo**](ImagesAPI.md#V3GetImageFirmwareInfo) | **Post** /v3/images/{imageId}/fwinfo | Get firmware info embedded in an image
[**V3GetInstallFirmwareStatus**](ImagesAPI.md#V3GetInstallFirmwareStatus) | **Get** /v3/images/install-firmware/{taskId} | Get install-firmware task status
[**V3InstallFirmware**](ImagesAPI.md#V3InstallFirmware) | **Post** /v3/images/install-firmware | Install firmware cluster-wide
[**V3InstallFirmwareAssets**](ImagesAPI.md#V3InstallFirmwareAssets) | **Post** /v3/images/install-firmware-assets | Install firmware assets cluster-wide
[**V3ListImages**](ImagesAPI.md#V3ListImages) | **Get** /v3/images | List image metadata
[**V3UploadImageChunk**](ImagesAPI.md#V3UploadImageChunk) | **Put** /v3/images/{imageId}/file | Upload one chunk of an image file
[**V3UploadImageData**](ImagesAPI.md#V3UploadImageData) | **Post** /v3/images/{imageId} | Upload image file contents



## V3CreateImage

> Image V3CreateImage(ctx).CreateImageBody(createImageBody).Execute()

Create an image



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
	createImageBody := *openapiclient.NewCreateImageBody(openapiclient.ImageType("fwbinary"), openapiclient.ImageEncoding("plain")) // CreateImageBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.V3CreateImage(context.Background()).CreateImageBody(createImageBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3CreateImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateImage`: Image
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.V3CreateImage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createImageBody** | [**CreateImageBody**](CreateImageBody.md) |  | 

### Return type

[**Image**](Image.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteImage

> V3DeleteImage(ctx, imageId).Execute()

Delete an image



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
	imageId := "3e1354a3-fb10-46c0-8b05-56e28edbde69" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ImagesAPI.V3DeleteImage(context.Background(), imageId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3DeleteImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteImageRequest struct via the builder pattern


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


## V3GetImage

> Image V3GetImage(ctx, imageId).Execute()

Get image metadata



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
	imageId := "3e1354a3-fb10-46c0-8b05-56e28edbde69" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.V3GetImage(context.Background(), imageId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3GetImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetImage`: Image
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.V3GetImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Image**](Image.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetImageChunk

> map[string]interface{} V3GetImageChunk(ctx, imageId).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).Execute()

Check whether an image chunk was already uploaded



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
	imageId := "3e1354a3-fb10-46c0-8b05-56e28edbde69" // string | 
	resumableChunkNumber := float32(1) // float32 | Chunk sequence number.
	resumableChunkSize := float32(1048576) // float32 | Size of each chunk.
	resumableCurrentChunkSize := float32(1048576) // float32 | Size of the current chunk.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.V3GetImageChunk(context.Background(), imageId).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3GetImageChunk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetImageChunk`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.V3GetImageChunk`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetImageChunkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **resumableChunkNumber** | **float32** | Chunk sequence number. | 
 **resumableChunkSize** | **float32** | Size of each chunk. | 
 **resumableCurrentChunkSize** | **float32** | Size of the current chunk. | 

### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetImageFirmwareInfo

> ImageFirmwareInfo V3GetImageFirmwareInfo(ctx, imageId).GetFirmwareInfoBody(getFirmwareInfoBody).Execute()

Get firmware info embedded in an image



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
	imageId := "3e1354a3-fb10-46c0-8b05-56e28edbde69" // string | 
	getFirmwareInfoBody := *openapiclient.NewGetFirmwareInfoBody() // GetFirmwareInfoBody | Optional decryption password and extended-info flag. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.V3GetImageFirmwareInfo(context.Background(), imageId).GetFirmwareInfoBody(getFirmwareInfoBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3GetImageFirmwareInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetImageFirmwareInfo`: ImageFirmwareInfo
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.V3GetImageFirmwareInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetImageFirmwareInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **getFirmwareInfoBody** | [**GetFirmwareInfoBody**](GetFirmwareInfoBody.md) | Optional decryption password and extended-info flag. | 

### Return type

[**ImageFirmwareInfo**](ImageFirmwareInfo.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInstallFirmwareStatus

> InstallFirmwareStatusResponse V3GetInstallFirmwareStatus(ctx, taskId).Execute()

Get install-firmware task status



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
	taskId := "722cdce5-6f71-4f4a-b2b6-c00f11c015f6" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.V3GetInstallFirmwareStatus(context.Background(), taskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3GetInstallFirmwareStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstallFirmwareStatus`: InstallFirmwareStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.V3GetInstallFirmwareStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**taskId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstallFirmwareStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InstallFirmwareStatusResponse**](InstallFirmwareStatusResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3InstallFirmware

> InstallFirmwareResponse V3InstallFirmware(ctx).InstallFirmwareBody(installFirmwareBody).Execute()

Install firmware cluster-wide



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
	installFirmwareBody := *openapiclient.NewInstallFirmwareBody("3e1354a3-fb10-46c0-8b05-56e28edbde69") // InstallFirmwareBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.V3InstallFirmware(context.Background()).InstallFirmwareBody(installFirmwareBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3InstallFirmware``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3InstallFirmware`: InstallFirmwareResponse
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.V3InstallFirmware`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3InstallFirmwareRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **installFirmwareBody** | [**InstallFirmwareBody**](InstallFirmwareBody.md) |  | 

### Return type

[**InstallFirmwareResponse**](InstallFirmwareResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3InstallFirmwareAssets

> InstallFirmwareAssetsResponse V3InstallFirmwareAssets(ctx).InstallFirmwareAssetsBody(installFirmwareAssetsBody).Execute()

Install firmware assets cluster-wide



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
	installFirmwareAssetsBody := *openapiclient.NewInstallFirmwareAssetsBody("3e1354a3-fb10-46c0-8b05-56e28edbde69") // InstallFirmwareAssetsBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.V3InstallFirmwareAssets(context.Background()).InstallFirmwareAssetsBody(installFirmwareAssetsBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3InstallFirmwareAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3InstallFirmwareAssets`: InstallFirmwareAssetsResponse
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.V3InstallFirmwareAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3InstallFirmwareAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **installFirmwareAssetsBody** | [**InstallFirmwareAssetsBody**](InstallFirmwareAssetsBody.md) |  | 

### Return type

[**InstallFirmwareAssetsResponse**](InstallFirmwareAssetsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListImages

> ImageList V3ListImages(ctx).Limit(limit).Offset(offset).ProjectId(projectId).Execute()

List image metadata



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
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | Filter results to a single project. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.V3ListImages(context.Background()).Limit(limit).Offset(offset).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3ListImages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListImages`: ImageList
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.V3ListImages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListImagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]
 **projectId** | **string** | Filter results to a single project. | 

### Return type

[**ImageList**](ImageList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3UploadImageChunk

> V3UploadImageChunk(ctx, imageId).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).ResumableTotalSize(resumableTotalSize).ResumableTotalChunks(resumableTotalChunks).Body(body).ResumableIdentifier(resumableIdentifier).ResumableFilename(resumableFilename).ResumableRelativePath(resumableRelativePath).ResumableType(resumableType).CorelliumChecksum(corelliumChecksum).XCorelliumTotalFileSize(xCorelliumTotalFileSize).Execute()

Upload one chunk of an image file



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
	imageId := "3e1354a3-fb10-46c0-8b05-56e28edbde69" // string | 
	resumableChunkNumber := float32(1) // float32 | Chunk sequence number.
	resumableChunkSize := float32(1048576) // float32 | Size of each chunk.
	resumableCurrentChunkSize := float32(1048576) // float32 | Size of the current chunk.
	resumableTotalSize := float32(2147483648) // float32 | Total file size.
	resumableTotalChunks := float32(2048) // float32 | Total number of chunks.
	body := os.NewFile(1234, "some_file") // *os.File | 
	resumableIdentifier := "2147483648-customfirmwareipsw" // string | Client-side identifier of the file being uploaded. (optional)
	resumableFilename := "custom-firmware.ipsw" // string | Original filename. (optional)
	resumableRelativePath := "custom-firmware.ipsw" // string | Relative path. (optional)
	resumableType := "application/octet-stream" // string | MIME type. (optional)
	corelliumChecksum := "sha256$1048576$e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855" // string | Expected Corellium checksum of the complete file, formatted `algorithm$blockSize$hash`. When supplied, every chunk is re-hashed and the upload is rejected (and the image removed) unless the recomputed checksum matches. The chunk size used for the upload must equal the block size embedded in the checksum. Required for `fw` uploads on airgapped deployments. (optional)
	xCorelliumTotalFileSize := "2147483648" // string | Total size of the whole file in bytes. Send it on every chunk so the image-pool pre-flight check sees the full upload size rather than the size of a single chunk. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ImagesAPI.V3UploadImageChunk(context.Background(), imageId).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).ResumableTotalSize(resumableTotalSize).ResumableTotalChunks(resumableTotalChunks).Body(body).ResumableIdentifier(resumableIdentifier).ResumableFilename(resumableFilename).ResumableRelativePath(resumableRelativePath).ResumableType(resumableType).CorelliumChecksum(corelliumChecksum).XCorelliumTotalFileSize(xCorelliumTotalFileSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3UploadImageChunk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UploadImageChunkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **resumableChunkNumber** | **float32** | Chunk sequence number. | 
 **resumableChunkSize** | **float32** | Size of each chunk. | 
 **resumableCurrentChunkSize** | **float32** | Size of the current chunk. | 
 **resumableTotalSize** | **float32** | Total file size. | 
 **resumableTotalChunks** | **float32** | Total number of chunks. | 
 **body** | ***os.File** |  | 
 **resumableIdentifier** | **string** | Client-side identifier of the file being uploaded. | 
 **resumableFilename** | **string** | Original filename. | 
 **resumableRelativePath** | **string** | Relative path. | 
 **resumableType** | **string** | MIME type. | 
 **corelliumChecksum** | **string** | Expected Corellium checksum of the complete file, formatted &#x60;algorithm$blockSize$hash&#x60;. When supplied, every chunk is re-hashed and the upload is rejected (and the image removed) unless the recomputed checksum matches. The chunk size used for the upload must equal the block size embedded in the checksum. Required for &#x60;fw&#x60; uploads on airgapped deployments. | 
 **xCorelliumTotalFileSize** | **string** | Total size of the whole file in bytes. Send it on every chunk so the image-pool pre-flight check sees the full upload size rather than the size of a single chunk. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3UploadImageData

> Image V3UploadImageData(ctx, imageId).File(file).CorelliumChecksum(corelliumChecksum).Execute()

Upload image file contents



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
	imageId := "3e1354a3-fb10-46c0-8b05-56e28edbde69" // string | 
	file := os.NewFile(1234, "some_file") // *os.File | 
	corelliumChecksum := "sha256$1048576$e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855" // string | Optional. Expected Corellium checksum of the whole file, formatted `algorithm$blockSize$hash` (for example `sha256$1048576$<hex>`). When supplied, the upload is rejected and the image removed if the file does not match. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.V3UploadImageData(context.Background(), imageId).File(file).CorelliumChecksum(corelliumChecksum).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.V3UploadImageData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3UploadImageData`: Image
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.V3UploadImageData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UploadImageDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **file** | ***os.File** |  | 
 **corelliumChecksum** | **string** | Optional. Expected Corellium checksum of the whole file, formatted &#x60;algorithm$blockSize$hash&#x60; (for example &#x60;sha256$1048576$&lt;hex&gt;&#x60;). When supplied, the upload is rejected and the image removed if the file does not match. | 

### Return type

[**Image**](Image.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

