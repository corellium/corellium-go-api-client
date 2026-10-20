# \RAMDumpAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3ClearRamDump**](RAMDumpAPI.md#V3ClearRamDump) | **Delete** /v3/instances/{instanceId}/ramdump | Delete a RAM dump
[**V3RamDumpPreauthorize**](RAMDumpAPI.md#V3RamDumpPreauthorize) | **Get** /v3/instances/{instanceId}/ramdump-authorize | Get a RAM dump download token
[**V3StartRamDump**](RAMDumpAPI.md#V3StartRamDump) | **Post** /v3/instances/{instanceId}/ramdump/start | Start a RAM dump



## V3ClearRamDump

> V3ClearRamDump(ctx, instanceId).Execute()

Delete a RAM dump



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RAMDumpAPI.V3ClearRamDump(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RAMDumpAPI.V3ClearRamDump``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ClearRamDumpRequest struct via the builder pattern


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


## V3RamDumpPreauthorize

> Token V3RamDumpPreauthorize(ctx, instanceId).Execute()

Get a RAM dump download token



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RAMDumpAPI.V3RamDumpPreauthorize(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RAMDumpAPI.V3RamDumpPreauthorize``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3RamDumpPreauthorize`: Token
	fmt.Fprintf(os.Stdout, "Response from `RAMDumpAPI.V3RamDumpPreauthorize`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RamDumpPreauthorizeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Token**](Token.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3StartRamDump

> V3StartRamDump(ctx, instanceId).Execute()

Start a RAM dump



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RAMDumpAPI.V3StartRamDump(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RAMDumpAPI.V3StartRamDump``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3StartRamDumpRequest struct via the builder pattern


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

