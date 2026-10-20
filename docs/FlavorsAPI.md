# \FlavorsAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3GetFrame**](FlavorsAPI.md#V3GetFrame) | **Get** /v3/flavors/{flavorId} | Get the device frame layout for a model
[**V3GetFrameImage**](FlavorsAPI.md#V3GetFrameImage) | **Get** /v3/flavors/{flavorId}/image | Get the device frame image for a model
[**V3GetProductImage**](FlavorsAPI.md#V3GetProductImage) | **Get** /v3/flavors/{flavorId}/productimage | Get the product image for a model



## V3GetFrame

> FlavorFrame V3GetFrame(ctx, flavorId).Execute()

Get the device frame layout for a model



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
	flavorId := "iphone8" // string | Flavor ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FlavorsAPI.V3GetFrame(context.Background(), flavorId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FlavorsAPI.V3GetFrame``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetFrame`: FlavorFrame
	fmt.Fprintf(os.Stdout, "Response from `FlavorsAPI.V3GetFrame`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**flavorId** | **string** | Flavor ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetFrameRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FlavorFrame**](FlavorFrame.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetFrameImage

> *os.File V3GetFrameImage(ctx, flavorId).Execute()

Get the device frame image for a model



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
	flavorId := "iphone8" // string | Flavor ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FlavorsAPI.V3GetFrameImage(context.Background(), flavorId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FlavorsAPI.V3GetFrameImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetFrameImage`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `FlavorsAPI.V3GetFrameImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**flavorId** | **string** | Flavor ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetFrameImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## V3GetProductImage

> *os.File V3GetProductImage(ctx, flavorId).Execute()

Get the product image for a model



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
	flavorId := "iphone8" // string | Flavor ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FlavorsAPI.V3GetProductImage(context.Background(), flavorId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FlavorsAPI.V3GetProductImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetProductImage`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `FlavorsAPI.V3GetProductImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**flavorId** | **string** | Flavor ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetProductImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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

