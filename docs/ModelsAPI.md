# \ModelsAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3GetModelSoftware**](ModelsAPI.md#V3GetModelSoftware) | **Get** /v3/models/{model}/software | List software for a model
[**V3GetModels**](ModelsAPI.md#V3GetModels) | **Get** /v3/models | List device models



## V3GetModelSoftware

> []ModelFirmware V3GetModelSoftware(ctx, model).Execute()

List software for a model



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
	model := "iphone17a" // string | Which model to list software for: a flavor ID (the `flavor` value from `v3GetModels`, for example \"iphone17a\") or a product identifier such as \"iPhone18,4\". Only a flavor ID returns `springboardSnapshot`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ModelsAPI.V3GetModelSoftware(context.Background(), model).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelsAPI.V3GetModelSoftware``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetModelSoftware`: []ModelFirmware
	fmt.Fprintf(os.Stdout, "Response from `ModelsAPI.V3GetModelSoftware`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**model** | **string** | Which model to list software for: a flavor ID (the &#x60;flavor&#x60; value from &#x60;v3GetModels&#x60;, for example \&quot;iphone17a\&quot;) or a product identifier such as \&quot;iPhone18,4\&quot;. Only a flavor ID returns &#x60;springboardSnapshot&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetModelSoftwareRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]ModelFirmware**](ModelFirmware.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetModels

> []Model V3GetModels(ctx).IfNoneMatch(ifNoneMatch).Execute()

List device models



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
	ifNoneMatch := ""20184446fd197a424d5221fc7bfcd0084414c4b1ba822cac6f8f2221ebc80d06"" // string | An ETag a previous response carried, quotes included. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ModelsAPI.V3GetModels(context.Background()).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelsAPI.V3GetModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetModels`: []Model
	fmt.Fprintf(os.Stdout, "Response from `ModelsAPI.V3GetModels`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3GetModelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ifNoneMatch** | **string** | An ETag a previous response carried, quotes included. | 

### Return type

[**[]Model**](Model.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

