# \ImagesV2API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1DeleteImage**](ImagesV2API.md#V1DeleteImage) | **Delete** /v2/images/{imageId} | Delete Image



## V1DeleteImage

> V1DeleteImage(ctx, imageId).Execute()

Delete Image

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
	r, err := apiClient.ImagesV2API.V1DeleteImage(context.Background(), imageId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesV2API.V1DeleteImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** | Image ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteImageRequest struct via the builder pattern


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

