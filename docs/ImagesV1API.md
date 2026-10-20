# \ImagesV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1GetImage**](ImagesV1API.md#V1GetImage) | **Get** /v1/images/{imageId} | Get Image Metadata
[**V1GetImages**](ImagesV1API.md#V1GetImages) | **Get** /v1/images | Get all Images Metadata



## V1GetImage

> ImageV1 V1GetImage(ctx, imageId).Execute()

Get Image Metadata

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesV1API.V1GetImage(context.Background(), imageId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesV1API.V1GetImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetImage`: ImageV1
	fmt.Fprintf(os.Stdout, "Response from `ImagesV1API.V1GetImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** | Image ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImageV1**](ImageV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetImages

> []ImageV1 V1GetImages(ctx).Project(project).Execute()

Get all Images Metadata

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
	project := "project_example" // string | Optionally filter by project - uuid (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesV1API.V1GetImages(context.Background()).Project(project).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesV1API.V1GetImages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetImages`: []ImageV1
	fmt.Fprintf(os.Stdout, "Response from `ImagesV1API.V1GetImages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1GetImagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project** | **string** | Optionally filter by project - uuid | 

### Return type

[**[]ImageV1**](ImageV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

