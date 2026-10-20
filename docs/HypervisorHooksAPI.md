# \HypervisorHooksAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3ClearHyperTraceHooks**](HypervisorHooksAPI.md#V3ClearHyperTraceHooks) | **Post** /v3/instances/{instanceId}/hooks/clear | Stop hypervisor hooks
[**V3CreateHook**](HypervisorHooksAPI.md#V3CreateHook) | **Post** /v3/instances/{instanceId}/hooks | Create a hypervisor hook for an instance
[**V3DeleteHook**](HypervisorHooksAPI.md#V3DeleteHook) | **Delete** /v3/hooks/{hookId} | Delete a hypervisor hook
[**V3ExecuteHyperTraceHooks**](HypervisorHooksAPI.md#V3ExecuteHyperTraceHooks) | **Post** /v3/instances/{instanceId}/hooks/execute | Run hypervisor hooks
[**V3GetHook**](HypervisorHooksAPI.md#V3GetHook) | **Get** /v3/hooks/{hookId} | Get a hypervisor hook by ID
[**V3ListHooks**](HypervisorHooksAPI.md#V3ListHooks) | **Get** /v3/instances/{instanceId}/hooks | List hypervisor hooks for an instance
[**V3UpdateHook**](HypervisorHooksAPI.md#V3UpdateHook) | **Put** /v3/hooks/{hookId} | Update a hypervisor hook



## V3ClearHyperTraceHooks

> V3ClearHyperTraceHooks(ctx, instanceId).Execute()

Stop hypervisor hooks



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
	r, err := apiClient.HypervisorHooksAPI.V3ClearHyperTraceHooks(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HypervisorHooksAPI.V3ClearHyperTraceHooks``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3ClearHyperTraceHooksRequest struct via the builder pattern


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


## V3CreateHook

> Hook V3CreateHook(ctx, instanceId).CreateHookBody(createHookBody).Execute()

Create a hypervisor hook for an instance



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance identifier.
	createHookBody := *openapiclient.NewCreateHookBody("Bypass jailbreak detection", "0x1000042a4", "return 0;", openapiclient.HookPatchType("csmfcc")) // CreateHookBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HypervisorHooksAPI.V3CreateHook(context.Background(), instanceId).CreateHookBody(createHookBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HypervisorHooksAPI.V3CreateHook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateHook`: Hook
	fmt.Fprintf(os.Stdout, "Response from `HypervisorHooksAPI.V3CreateHook`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateHookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createHookBody** | [**CreateHookBody**](CreateHookBody.md) |  | 

### Return type

[**Hook**](Hook.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteHook

> V3DeleteHook(ctx, hookId).Execute()

Delete a hypervisor hook



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
	hookId := "2a1192e8-c7de-4981-bc11-c87fd1f12d13" // string | Hook identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HypervisorHooksAPI.V3DeleteHook(context.Background(), hookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HypervisorHooksAPI.V3DeleteHook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**hookId** | **string** | Hook identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteHookRequest struct via the builder pattern


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


## V3ExecuteHyperTraceHooks

> V3ExecuteHyperTraceHooks(ctx, instanceId).Execute()

Run hypervisor hooks



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
	r, err := apiClient.HypervisorHooksAPI.V3ExecuteHyperTraceHooks(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HypervisorHooksAPI.V3ExecuteHyperTraceHooks``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3ExecuteHyperTraceHooksRequest struct via the builder pattern


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


## V3GetHook

> Hook V3GetHook(ctx, hookId).Execute()

Get a hypervisor hook by ID



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
	hookId := "2a1192e8-c7de-4981-bc11-c87fd1f12d13" // string | Hook identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HypervisorHooksAPI.V3GetHook(context.Background(), hookId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HypervisorHooksAPI.V3GetHook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetHook`: Hook
	fmt.Fprintf(os.Stdout, "Response from `HypervisorHooksAPI.V3GetHook`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**hookId** | **string** | Hook identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetHookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Hook**](Hook.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListHooks

> HookList V3ListHooks(ctx, instanceId).Limit(limit).Offset(offset).Sort(sort).Execute()

List hypervisor hooks for an instance



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance identifier.
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)
	sort := "sort_example" // string | Sort order by creation date. (optional) (default to "DESC")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HypervisorHooksAPI.V3ListHooks(context.Background(), instanceId).Limit(limit).Offset(offset).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HypervisorHooksAPI.V3ListHooks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListHooks`: HookList
	fmt.Fprintf(os.Stdout, "Response from `HypervisorHooksAPI.V3ListHooks`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListHooksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]
 **sort** | **string** | Sort order by creation date. | [default to &quot;DESC&quot;]

### Return type

[**HookList**](HookList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3UpdateHook

> Hook V3UpdateHook(ctx, hookId).UpdateHookBody(updateHookBody).Execute()

Update a hypervisor hook



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
	hookId := "2a1192e8-c7de-4981-bc11-c87fd1f12d13" // string | Hook identifier.
	updateHookBody := *openapiclient.NewUpdateHookBody() // UpdateHookBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HypervisorHooksAPI.V3UpdateHook(context.Background(), hookId).UpdateHookBody(updateHookBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HypervisorHooksAPI.V3UpdateHook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3UpdateHook`: Hook
	fmt.Fprintf(os.Stdout, "Response from `HypervisorHooksAPI.V3UpdateHook`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**hookId** | **string** | Hook identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UpdateHookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateHookBody** | [**UpdateHookBody**](UpdateHookBody.md) |  | 

### Return type

[**Hook**](Hook.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

