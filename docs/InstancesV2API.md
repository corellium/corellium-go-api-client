# \InstancesV2API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V2GetInstanceQuickConnectCommand**](InstancesV2API.md#V2GetInstanceQuickConnectCommand) | **Get** /v2/instances/{instanceId}/quickConnectCommand | Recommended SSH Command for Quick Connect
[**V2GetInstanceState**](InstancesV2API.md#V2GetInstanceState) | **Get** /v2/instances/{instanceId}/state | Get state of Instance



## V2GetInstanceQuickConnectCommand

> string V2GetInstanceQuickConnectCommand(ctx, instanceId).Execute()

Recommended SSH Command for Quick Connect

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV2API.V2GetInstanceQuickConnectCommand(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV2API.V2GetInstanceQuickConnectCommand``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V2GetInstanceQuickConnectCommand`: string
	fmt.Fprintf(os.Stdout, "Response from `InstancesV2API.V2GetInstanceQuickConnectCommand`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV2GetInstanceQuickConnectCommandRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V2GetInstanceState

> InstanceStateV1 V2GetInstanceState(ctx, instanceId).ReturnAttr(returnAttr).Execute()

Get state of Instance

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	returnAttr := []string{"Inner_example"} // []string | The attributes to return. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV2API.V2GetInstanceState(context.Background(), instanceId).ReturnAttr(returnAttr).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV2API.V2GetInstanceState``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V2GetInstanceState`: InstanceStateV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV2API.V2GetInstanceState`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV2GetInstanceStateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **returnAttr** | **[]string** | The attributes to return. | 

### Return type

[**InstanceStateV1**](InstanceStateV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

