# \CoreTraceAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3ClearCoreTrace**](CoreTraceAPI.md#V3ClearCoreTrace) | **Delete** /v3/instances/{instanceId}/strace | Clear CoreTrace output
[**V3ListThreads**](CoreTraceAPI.md#V3ListThreads) | **Get** /v3/instances/{instanceId}/strace/thread-list | List running processes (CoreTrace)
[**V3StartCoreTrace**](CoreTraceAPI.md#V3StartCoreTrace) | **Post** /v3/instances/{instanceId}/strace/enable | Start CoreTrace
[**V3StopCoreTrace**](CoreTraceAPI.md#V3StopCoreTrace) | **Post** /v3/instances/{instanceId}/strace/disable | Stop CoreTrace
[**V3StracePreauthorize**](CoreTraceAPI.md#V3StracePreauthorize) | **Get** /v3/instances/{instanceId}/strace-authorize | Get a CoreTrace download token



## V3ClearCoreTrace

> V3ClearCoreTrace(ctx, instanceId).Execute()

Clear CoreTrace output



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
	r, err := apiClient.CoreTraceAPI.V3ClearCoreTrace(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoreTraceAPI.V3ClearCoreTrace``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3ClearCoreTraceRequest struct via the builder pattern


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


## V3ListThreads

> []KernelTask V3ListThreads(ctx, instanceId).Execute()

List running processes (CoreTrace)



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
	resp, r, err := apiClient.CoreTraceAPI.V3ListThreads(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoreTraceAPI.V3ListThreads``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListThreads`: []KernelTask
	fmt.Fprintf(os.Stdout, "Response from `CoreTraceAPI.V3ListThreads`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListThreadsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]KernelTask**](KernelTask.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3StartCoreTrace

> V3StartCoreTrace(ctx, instanceId).Execute()

Start CoreTrace



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
	r, err := apiClient.CoreTraceAPI.V3StartCoreTrace(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoreTraceAPI.V3StartCoreTrace``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StartCoreTraceRequest struct via the builder pattern


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


## V3StopCoreTrace

> V3StopCoreTrace(ctx, instanceId).Execute()

Stop CoreTrace



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
	r, err := apiClient.CoreTraceAPI.V3StopCoreTrace(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoreTraceAPI.V3StopCoreTrace``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StopCoreTraceRequest struct via the builder pattern


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


## V3StracePreauthorize

> Token V3StracePreauthorize(ctx, instanceId).Execute()

Get a CoreTrace download token



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
	resp, r, err := apiClient.CoreTraceAPI.V3StracePreauthorize(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoreTraceAPI.V3StracePreauthorize``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3StracePreauthorize`: Token
	fmt.Fprintf(os.Stdout, "Response from `CoreTraceAPI.V3StracePreauthorize`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3StracePreauthorizeRequest struct via the builder pattern


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

