# \ExtensionsV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1DeleteExtension**](ExtensionsV1API.md#V1DeleteExtension) | **Delete** /v1/extensions/{extensionId} | Delete an existing extension
[**V1GetExtensionById**](ExtensionsV1API.md#V1GetExtensionById) | **Get** /v1/extensions/{extensionId} | Get extension by id
[**V1GetExtensions**](ExtensionsV1API.md#V1GetExtensions) | **Get** /v1/extensions | Get all extensions
[**V1LoadExtension**](ExtensionsV1API.md#V1LoadExtension) | **Post** /v1/extensions | Load an extension
[**V1ParseExtensionJson**](ExtensionsV1API.md#V1ParseExtensionJson) | **Post** /v1/extensions/parse/extension.json | Validates extension.json
[**V1UpdateExtension**](ExtensionsV1API.md#V1UpdateExtension) | **Put** /v1/extensions/{extensionId} | Update an existing extension



## V1DeleteExtension

> V1DeleteExtension(ctx, extensionId).Execute()

Delete an existing extension

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
	extensionId := "extensionId_example" // string | Extension ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ExtensionsV1API.V1DeleteExtension(context.Background(), extensionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsV1API.V1DeleteExtension``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**extensionId** | **string** | Extension ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteExtensionRequest struct via the builder pattern


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


## V1GetExtensionById

> ExtensionV1 V1GetExtensionById(ctx, extensionId).Execute()

Get extension by id

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
	extensionId := "extensionId_example" // string | Extension Id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtensionsV1API.V1GetExtensionById(context.Background(), extensionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsV1API.V1GetExtensionById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetExtensionById`: ExtensionV1
	fmt.Fprintf(os.Stdout, "Response from `ExtensionsV1API.V1GetExtensionById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**extensionId** | **string** | Extension Id | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetExtensionByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ExtensionV1**](ExtensionV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetExtensions

> []ExtensionV1 V1GetExtensions(ctx).Limit(limit).Offset(offset).IfNoneMatch(ifNoneMatch).Execute()

Get all extensions

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
	limit := float32(8.14) // float32 | limit for pagination results, defaults to 20 (optional)
	offset := float32(8.14) // float32 | offset for pagination results, defaults to 0 (optional)
	ifNoneMatch := "ifNoneMatch_example" // string | sha256sum of the last response with the same parameters (optional) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtensionsV1API.V1GetExtensions(context.Background()).Limit(limit).Offset(offset).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsV1API.V1GetExtensions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetExtensions`: []ExtensionV1
	fmt.Fprintf(os.Stdout, "Response from `ExtensionsV1API.V1GetExtensions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1GetExtensionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | limit for pagination results, defaults to 20 | 
 **offset** | **float32** | offset for pagination results, defaults to 0 | 
 **ifNoneMatch** | **string** | sha256sum of the last response with the same parameters (optional) | 

### Return type

[**[]ExtensionV1**](ExtensionV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1LoadExtension

> ExtensionV1 V1LoadExtension(ctx).V1LoadExtensionParameters(v1LoadExtensionParameters).Execute()

Load an extension

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
	v1LoadExtensionParameters := *openapiclient.NewV1LoadExtensionParameters("ImageId_example") // V1LoadExtensionParameters | application/json

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtensionsV1API.V1LoadExtension(context.Background()).V1LoadExtensionParameters(v1LoadExtensionParameters).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsV1API.V1LoadExtension``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1LoadExtension`: ExtensionV1
	fmt.Fprintf(os.Stdout, "Response from `ExtensionsV1API.V1LoadExtension`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1LoadExtensionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **v1LoadExtensionParameters** | [**V1LoadExtensionParameters**](V1LoadExtensionParameters.md) | application/json | 

### Return type

[**ExtensionV1**](ExtensionV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ParseExtensionJson

> map[string]interface{} V1ParseExtensionJson(ctx).ExtensionV1(extensionV1).Execute()

Validates extension.json

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
	extensionV1 := *openapiclient.NewExtensionV1() // ExtensionV1 | extension.json contents

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtensionsV1API.V1ParseExtensionJson(context.Background()).ExtensionV1(extensionV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsV1API.V1ParseExtensionJson``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ParseExtensionJson`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ExtensionsV1API.V1ParseExtensionJson`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ParseExtensionJsonRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **extensionV1** | [**ExtensionV1**](ExtensionV1.md) | extension.json contents | 

### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UpdateExtension

> V1UpdateExtension(ctx, extensionId).UpdateExtension(updateExtension).Execute()

Update an existing extension

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
	extensionId := "extensionId_example" // string | Extension ID
	updateExtension := *openapiclient.NewUpdateExtension() // UpdateExtension | application/json

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ExtensionsV1API.V1UpdateExtension(context.Background(), extensionId).UpdateExtension(updateExtension).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsV1API.V1UpdateExtension``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**extensionId** | **string** | Extension ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UpdateExtensionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateExtension** | [**UpdateExtension**](UpdateExtension.md) | application/json | 

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

