# \ClusterAdministrationNodesAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1GetClusterNodes**](ClusterAdministrationNodesAPI.md#V1GetClusterNodes) | **Get** /v1/cluster/nodes/{nodeId} | Get node details by ID
[**V1GetConsoleClusterNodes**](ClusterAdministrationNodesAPI.md#V1GetConsoleClusterNodes) | **Get** /v1/cluster/nodes/{nodeId}/console | Access node console via SSH
[**V1ListClusterNodes**](ClusterAdministrationNodesAPI.md#V1ListClusterNodes) | **Get** /v1/cluster/nodes | List servers in the cluster



## V1GetClusterNodes

> NodeInformationV1 V1GetClusterNodes(ctx, nodeId).Execute()

Get node details by ID

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
	nodeId := "nodeId_example" // string | Node ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationNodesAPI.V1GetClusterNodes(context.Background(), nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationNodesAPI.V1GetClusterNodes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetClusterNodes`: NodeInformationV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationNodesAPI.V1GetClusterNodes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**nodeId** | **string** | Node ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetClusterNodesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NodeInformationV1**](NodeInformationV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetConsoleClusterNodes

> V1GetConsoleClusterNodes(ctx, nodeId).Execute()

Access node console via SSH



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
	nodeId := "nodeId_example" // string | Node ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ClusterAdministrationNodesAPI.V1GetConsoleClusterNodes(context.Background(), nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationNodesAPI.V1GetConsoleClusterNodes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**nodeId** | **string** | Node ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetConsoleClusterNodesRequest struct via the builder pattern


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


## V1ListClusterNodes

> []NodeInformationV1 V1ListClusterNodes(ctx).Limit(limit).Offset(offset).Execute()

List servers in the cluster

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
	limit := float32(8.14) // float32 | limit for pagination results, defaults to 100 (optional)
	offset := float32(8.14) // float32 | offset for pagination results, defaults to 0 (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAdministrationNodesAPI.V1ListClusterNodes(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationNodesAPI.V1ListClusterNodes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListClusterNodes`: []NodeInformationV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationNodesAPI.V1ListClusterNodes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ListClusterNodesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | limit for pagination results, defaults to 100 | 
 **offset** | **float32** | offset for pagination results, defaults to 0 | 

### Return type

[**[]NodeInformationV1**](NodeInformationV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

