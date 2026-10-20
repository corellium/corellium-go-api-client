# \DomainAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateDomainWelcomeMessage**](DomainAPI.md#V3CreateDomainWelcomeMessage) | **Post** /v3/domain/welcome | Create a welcome message for a domain
[**V3DeleteDomainWelcomeMessage**](DomainAPI.md#V3DeleteDomainWelcomeMessage) | **Delete** /v3/domain/welcome | Delete the welcome message for the authenticated user&#39;s domain
[**V3GetDomainImageUpload**](DomainAPI.md#V3GetDomainImageUpload) | **Get** /v3/domain/image-upload/{type}/{imageId}/{name} | Get image upload status
[**V3GetDomainWelcomeMessage**](DomainAPI.md#V3GetDomainWelcomeMessage) | **Get** /v3/domain/welcome | Get the welcome message for the authenticated user&#39;s domain
[**V3ListDomainSoftware**](DomainAPI.md#V3ListDomainSoftware) | **Get** /v3/domain/software | List domain-level firmware images
[**V3PatchDomainWelcomeMessage**](DomainAPI.md#V3PatchDomainWelcomeMessage) | **Patch** /v3/domain/welcome | Update a welcome message for a domain
[**V3PutDomainImageUpload**](DomainAPI.md#V3PutDomainImageUpload) | **Put** /v3/domain/image-upload/{type}/{imageId}/{name} | Upload image chunk



## V3CreateDomainWelcomeMessage

> DomainWelcomeMessageResponse V3CreateDomainWelcomeMessage(ctx).SetDomainWelcomeMessageBody(setDomainWelcomeMessageBody).Execute()

Create a welcome message for a domain



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
	setDomainWelcomeMessageBody := *openapiclient.NewSetDomainWelcomeMessageBody("<p>Welcome to Acme Corp!</p>", true) // SetDomainWelcomeMessageBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainAPI.V3CreateDomainWelcomeMessage(context.Background()).SetDomainWelcomeMessageBody(setDomainWelcomeMessageBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAPI.V3CreateDomainWelcomeMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateDomainWelcomeMessage`: DomainWelcomeMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `DomainAPI.V3CreateDomainWelcomeMessage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateDomainWelcomeMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **setDomainWelcomeMessageBody** | [**SetDomainWelcomeMessageBody**](SetDomainWelcomeMessageBody.md) |  | 

### Return type

[**DomainWelcomeMessageResponse**](DomainWelcomeMessageResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteDomainWelcomeMessage

> V3DeleteDomainWelcomeMessage(ctx).Execute()

Delete the welcome message for the authenticated user's domain



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
	r, err := apiClient.DomainAPI.V3DeleteDomainWelcomeMessage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAPI.V3DeleteDomainWelcomeMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteDomainWelcomeMessageRequest struct via the builder pattern


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


## V3GetDomainImageUpload

> *os.File V3GetDomainImageUpload(ctx, type_, imageId, name).ResumableChunkNumber(resumableChunkNumber).Execute()

Get image upload status



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
	type_ := "type__example" // string | What kind of file this is, for example `fw` for firmware or `kernel`. Uses the same values as `type` on `POST /v3/images`; see `ImageType` for what each means. Types that need a license feature your license lacks are rejected with 403.
	imageId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload.
	name := "name_example" // string | The file name to store, URL-encoded (for example `my%20firmware.ipsw`). Becomes the image `name`.
	resumableChunkNumber := float32(56) // float32 | Chunk number. When present the response reports whether that chunk was already stored (200) or still needs to be uploaded (204) instead of returning the image file. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainAPI.V3GetDomainImageUpload(context.Background(), type_, imageId, name).ResumableChunkNumber(resumableChunkNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAPI.V3GetDomainImageUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetDomainImageUpload`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `DomainAPI.V3GetDomainImageUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**type_** | **string** | What kind of file this is, for example &#x60;fw&#x60; for firmware or &#x60;kernel&#x60;. Uses the same values as &#x60;type&#x60; on &#x60;POST /v3/images&#x60;; see &#x60;ImageType&#x60; for what each means. Types that need a license feature your license lacks are rejected with 403. | 
**imageId** | **string** | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload. | 
**name** | **string** | The file name to store, URL-encoded (for example &#x60;my%20firmware.ipsw&#x60;). Becomes the image &#x60;name&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetDomainImageUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **resumableChunkNumber** | **float32** | Chunk number. When present the response reports whether that chunk was already stored (200) or still needs to be uploaded (204) instead of returning the image file. | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetDomainWelcomeMessage

> DomainWelcomeMessageResponse V3GetDomainWelcomeMessage(ctx).Execute()

Get the welcome message for the authenticated user's domain



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
	resp, r, err := apiClient.DomainAPI.V3GetDomainWelcomeMessage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAPI.V3GetDomainWelcomeMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetDomainWelcomeMessage`: DomainWelcomeMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `DomainAPI.V3GetDomainWelcomeMessage`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetDomainWelcomeMessageRequest struct via the builder pattern


### Return type

[**DomainWelcomeMessageResponse**](DomainWelcomeMessageResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListDomainSoftware

> DomainSoftwareList V3ListDomainSoftware(ctx).Limit(limit).Offset(offset).Execute()

List domain-level firmware images



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainAPI.V3ListDomainSoftware(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAPI.V3ListDomainSoftware``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListDomainSoftware`: DomainSoftwareList
	fmt.Fprintf(os.Stdout, "Response from `DomainAPI.V3ListDomainSoftware`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListDomainSoftwareRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**DomainSoftwareList**](DomainSoftwareList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchDomainWelcomeMessage

> DomainWelcomeMessageResponse V3PatchDomainWelcomeMessage(ctx).PatchDomainWelcomeMessageBody(patchDomainWelcomeMessageBody).Execute()

Update a welcome message for a domain



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
	patchDomainWelcomeMessageBody := *openapiclient.NewPatchDomainWelcomeMessageBody() // PatchDomainWelcomeMessageBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainAPI.V3PatchDomainWelcomeMessage(context.Background()).PatchDomainWelcomeMessageBody(patchDomainWelcomeMessageBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAPI.V3PatchDomainWelcomeMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PatchDomainWelcomeMessage`: DomainWelcomeMessageResponse
	fmt.Fprintf(os.Stdout, "Response from `DomainAPI.V3PatchDomainWelcomeMessage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchDomainWelcomeMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **patchDomainWelcomeMessageBody** | [**PatchDomainWelcomeMessageBody**](PatchDomainWelcomeMessageBody.md) |  | 

### Return type

[**DomainWelcomeMessageResponse**](DomainWelcomeMessageResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PutDomainImageUpload

> map[string]interface{} V3PutDomainImageUpload(ctx, type_, imageId, name).Body(body).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).ResumableTotalSize(resumableTotalSize).ResumableTotalChunks(resumableTotalChunks).CorelliumChecksum(corelliumChecksum).Flavor(flavor).XCorelliumImageEncoding(xCorelliumImageEncoding).XCorelliumImageEncapsulated(xCorelliumImageEncapsulated).XCorelliumTotalFileSize(xCorelliumTotalFileSize).XCorelliumImagePassword(xCorelliumImagePassword).Execute()

Upload image chunk



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
	type_ := "type__example" // string | What kind of file this is, for example `fw` for firmware or `kernel`. Uses the same values as `type` on `POST /v3/images`; see `ImageType` for what each means. Types that need a license feature your license lacks are rejected with 403.
	imageId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload.
	name := "name_example" // string | The file name to store, URL-encoded (for example `my%20firmware.ipsw`). Becomes the image `name`.
	body := os.NewFile(1234, "some_file") // *os.File | 
	resumableChunkNumber := float32(56) // float32 | Which chunk this is, counting from 1. (optional)
	resumableChunkSize := float32(56) // float32 | The size, in bytes, you split the file into. Use the same value for every chunk; only the last chunk may be smaller. If you send `corelliumChecksum`, this must equal the block size inside it. (optional)
	resumableCurrentChunkSize := float32(56) // float32 | Actual size in bytes of this chunk's body. (optional)
	resumableTotalSize := float32(56) // float32 | Size of the whole file in bytes. (optional)
	resumableTotalChunks := float32(56) // float32 | How many chunks the whole file is split into. The upload completes when the last one arrives. (optional)
	corelliumChecksum := "corelliumChecksum_example" // string | Optional expected checksum of the whole file, formatted `algorithm$blockSize$hash`. When given, the finished upload is checked and rejected (and the image removed) if it does not match. Required for firmware (`fw`) uploads on air-gapped deployments. (optional)
	flavor := "flavor_example" // string | Device model (`flavor` from `GET /v3/models`) the image is for. Needed for `partition` uploads when the image is not attached to a device, so the partition name can be checked against that model. (optional)
	xCorelliumImageEncoding := "xCorelliumImageEncoding_example" // string | How the file is stored: `plain` (normal) or `encrypted`. Only read on the first chunk, when the image record is created; later chunks cannot change it. (optional)
	xCorelliumImageEncapsulated := true // bool | Whether the uploaded file is a ZIP wrapper the platform should unpack. Send false to store the file exactly as uploaded. Only read on the first chunk, when the image record is created. (optional)
	xCorelliumTotalFileSize := float32(56) // float32 | Size of the whole file in bytes. Send it on every chunk: the platform uses it to check up front that there is room for the entire file, and answers 507 if there is not, before storing any data. (optional)
	xCorelliumImagePassword := "xCorelliumImagePassword_example" // string | Password of a password-protected file (for example encrypted firmware), used to check the file after upload. Leave out for normal files. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainAPI.V3PutDomainImageUpload(context.Background(), type_, imageId, name).Body(body).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).ResumableTotalSize(resumableTotalSize).ResumableTotalChunks(resumableTotalChunks).CorelliumChecksum(corelliumChecksum).Flavor(flavor).XCorelliumImageEncoding(xCorelliumImageEncoding).XCorelliumImageEncapsulated(xCorelliumImageEncapsulated).XCorelliumTotalFileSize(xCorelliumTotalFileSize).XCorelliumImagePassword(xCorelliumImagePassword).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAPI.V3PutDomainImageUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PutDomainImageUpload`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `DomainAPI.V3PutDomainImageUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**type_** | **string** | What kind of file this is, for example &#x60;fw&#x60; for firmware or &#x60;kernel&#x60;. Uses the same values as &#x60;type&#x60; on &#x60;POST /v3/images&#x60;; see &#x60;ImageType&#x60; for what each means. Types that need a license feature your license lacks are rejected with 403. | 
**imageId** | **string** | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload. | 
**name** | **string** | The file name to store, URL-encoded (for example &#x60;my%20firmware.ipsw&#x60;). Becomes the image &#x60;name&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PutDomainImageUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **body** | ***os.File** |  | 
 **resumableChunkNumber** | **float32** | Which chunk this is, counting from 1. | 
 **resumableChunkSize** | **float32** | The size, in bytes, you split the file into. Use the same value for every chunk; only the last chunk may be smaller. If you send &#x60;corelliumChecksum&#x60;, this must equal the block size inside it. | 
 **resumableCurrentChunkSize** | **float32** | Actual size in bytes of this chunk&#39;s body. | 
 **resumableTotalSize** | **float32** | Size of the whole file in bytes. | 
 **resumableTotalChunks** | **float32** | How many chunks the whole file is split into. The upload completes when the last one arrives. | 
 **corelliumChecksum** | **string** | Optional expected checksum of the whole file, formatted &#x60;algorithm$blockSize$hash&#x60;. When given, the finished upload is checked and rejected (and the image removed) if it does not match. Required for firmware (&#x60;fw&#x60;) uploads on air-gapped deployments. | 
 **flavor** | **string** | Device model (&#x60;flavor&#x60; from &#x60;GET /v3/models&#x60;) the image is for. Needed for &#x60;partition&#x60; uploads when the image is not attached to a device, so the partition name can be checked against that model. | 
 **xCorelliumImageEncoding** | **string** | How the file is stored: &#x60;plain&#x60; (normal) or &#x60;encrypted&#x60;. Only read on the first chunk, when the image record is created; later chunks cannot change it. | 
 **xCorelliumImageEncapsulated** | **bool** | Whether the uploaded file is a ZIP wrapper the platform should unpack. Send false to store the file exactly as uploaded. Only read on the first chunk, when the image record is created. | 
 **xCorelliumTotalFileSize** | **float32** | Size of the whole file in bytes. Send it on every chunk: the platform uses it to check up front that there is room for the entire file, and answers 507 if there is not, before storing any data. | 
 **xCorelliumImagePassword** | **string** | Password of a password-protected file (for example encrypted firmware), used to check the file after upload. Leave out for normal files. | 

### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

