# \ExtensionsAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3DeleteExtension**](ExtensionsAPI.md#V3DeleteExtension) | **Delete** /v3/extensions/{extensionId} | Delete an existing extension
[**V3GetExtensionById**](ExtensionsAPI.md#V3GetExtensionById) | **Get** /v3/extensions/{extensionId} | Get extension by ID
[**V3ListExtensions**](ExtensionsAPI.md#V3ListExtensions) | **Get** /v3/extensions | List all extensions
[**V3LoadExtension**](ExtensionsAPI.md#V3LoadExtension) | **Post** /v3/extensions | Load an extension
[**V3ParseExtensionJson**](ExtensionsAPI.md#V3ParseExtensionJson) | **Post** /v3/extensions/parse/extension.json | Validates extension.json
[**V3UpdateExtension**](ExtensionsAPI.md#V3UpdateExtension) | **Put** /v3/extensions/{extensionId} | Update an existing extension



## V3DeleteExtension

> V3DeleteExtension(ctx, extensionId).Execute()

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
	extensionId := "rpi4b" // string | Extension ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ExtensionsAPI.V3DeleteExtension(context.Background(), extensionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsAPI.V3DeleteExtension``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**extensionId** | **string** | Extension ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteExtensionRequest struct via the builder pattern


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


## V3GetExtensionById

> Extension V3GetExtensionById(ctx, extensionId).Execute()

Get extension by ID



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
	extensionId := "rpi4b" // string | Extension ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtensionsAPI.V3GetExtensionById(context.Background(), extensionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsAPI.V3GetExtensionById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetExtensionById`: Extension
	fmt.Fprintf(os.Stdout, "Response from `ExtensionsAPI.V3GetExtensionById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**extensionId** | **string** | Extension ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetExtensionByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Extension**](Extension.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListExtensions

> ExtensionList V3ListExtensions(ctx).Limit(limit).Offset(offset).IfNoneMatch(ifNoneMatch).Execute()

List all extensions



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
	ifNoneMatch := "9f86d081884c7d659a2feaa0c55ad015a3bf4f1b2b0b822cd15d6c15b0f00a08" // string | SHA-256 sum of the last response with the same parameters. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtensionsAPI.V3ListExtensions(context.Background()).Limit(limit).Offset(offset).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsAPI.V3ListExtensions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListExtensions`: ExtensionList
	fmt.Fprintf(os.Stdout, "Response from `ExtensionsAPI.V3ListExtensions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListExtensionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]
 **ifNoneMatch** | **string** | SHA-256 sum of the last response with the same parameters. | 

### Return type

[**ExtensionList**](ExtensionList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3LoadExtension

> Extension V3LoadExtension(ctx).LoadExtensionBody(loadExtensionBody).Execute()

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
	loadExtensionBody := *openapiclient.NewLoadExtensionBody("3e1354a3-fb10-46c0-8b05-56e28edbde69") // LoadExtensionBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtensionsAPI.V3LoadExtension(context.Background()).LoadExtensionBody(loadExtensionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsAPI.V3LoadExtension``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3LoadExtension`: Extension
	fmt.Fprintf(os.Stdout, "Response from `ExtensionsAPI.V3LoadExtension`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3LoadExtensionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **loadExtensionBody** | [**LoadExtensionBody**](LoadExtensionBody.md) |  | 

### Return type

[**Extension**](Extension.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ParseExtensionJson

> map[string]interface{} V3ParseExtensionJson(ctx).RequestBody(requestBody).Execute()

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
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | Contents of the extension.json file.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtensionsAPI.V3ParseExtensionJson(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsAPI.V3ParseExtensionJson``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ParseExtensionJson`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ExtensionsAPI.V3ParseExtensionJson`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ParseExtensionJsonRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]interface{}** | Contents of the extension.json file. | 

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


## V3UpdateExtension

> Extension V3UpdateExtension(ctx, extensionId).UpdateExtensionBody(updateExtensionBody).Execute()

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
	extensionId := "rpi4b" // string | Extension ID.
	updateExtensionBody := *openapiclient.NewUpdateExtensionBody(false) // UpdateExtensionBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtensionsAPI.V3UpdateExtension(context.Background(), extensionId).UpdateExtensionBody(updateExtensionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtensionsAPI.V3UpdateExtension``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3UpdateExtension`: Extension
	fmt.Fprintf(os.Stdout, "Response from `ExtensionsAPI.V3UpdateExtension`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**extensionId** | **string** | Extension ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UpdateExtensionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateExtensionBody** | [**UpdateExtensionBody**](UpdateExtensionBody.md) |  | 

### Return type

[**Extension**](Extension.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

