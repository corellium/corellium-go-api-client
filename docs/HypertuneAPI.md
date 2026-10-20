# \HypertuneAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3HypertuneHash**](HypertuneAPI.md#V3HypertuneHash) | **Get** /v3/hypertune/hash | Get Hypertune state hash
[**V3HypertuneInit**](HypertuneAPI.md#V3HypertuneInit) | **Get** /v3/hypertune/init | Get Hypertune initialization data



## V3HypertuneHash

> HypertuneHashResponse V3HypertuneHash(ctx).Token(token).Branch(branch).Body(body).Execute()

Get Hypertune state hash



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
	token := "token_example" // string | Hypertune access token. (optional)
	branch := "branch_example" // string | Hypertune branch name. (optional)
	body := "body_example" // string | URL-encoded Hypertune SDK request body. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HypertuneAPI.V3HypertuneHash(context.Background()).Token(token).Branch(branch).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HypertuneAPI.V3HypertuneHash``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3HypertuneHash`: HypertuneHashResponse
	fmt.Fprintf(os.Stdout, "Response from `HypertuneAPI.V3HypertuneHash`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3HypertuneHashRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string** | Hypertune access token. | 
 **branch** | **string** | Hypertune branch name. | 
 **body** | **string** | URL-encoded Hypertune SDK request body. | 

### Return type

[**HypertuneHashResponse**](HypertuneHashResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3HypertuneInit

> HypertuneInitResponse V3HypertuneInit(ctx).Token(token).Branch(branch).Body(body).Execute()

Get Hypertune initialization data



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
	token := "token_example" // string | Hypertune access token. (optional)
	branch := "branch_example" // string | Hypertune branch name. (optional)
	body := "body_example" // string | URL-encoded Hypertune SDK request body. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HypertuneAPI.V3HypertuneInit(context.Background()).Token(token).Branch(branch).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HypertuneAPI.V3HypertuneInit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3HypertuneInit`: HypertuneInitResponse
	fmt.Fprintf(os.Stdout, "Response from `HypertuneAPI.V3HypertuneInit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3HypertuneInitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string** | Hypertune access token. | 
 **branch** | **string** | Hypertune branch name. | 
 **body** | **string** | URL-encoded Hypertune SDK request body. | 

### Return type

[**HypertuneInitResponse**](HypertuneInitResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

