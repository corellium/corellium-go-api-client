# \ClusterAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3DeleteClusterSnapshot**](ClusterAPI.md#V3DeleteClusterSnapshot) | **Delete** /v3/cluster/snapshots/{snapshotId} | Delete cluster snapshot
[**V3GetClusterConfig**](ClusterAPI.md#V3GetClusterConfig) | **Get** /v3/cluster/config | Get cluster configuration
[**V3GetClusterNode**](ClusterAPI.md#V3GetClusterNode) | **Get** /v3/cluster/nodes/{nodeId} | Get cluster node
[**V3GetClusterNodeConsole**](ClusterAPI.md#V3GetClusterNodeConsole) | **Get** /v3/cluster/nodes/{nodeId}/console | Get node console websocket URL
[**V3GetClusterSnapshot**](ClusterAPI.md#V3GetClusterSnapshot) | **Get** /v3/cluster/snapshots/{snapshotId} | Get cluster snapshot
[**V3ListClusterNodes**](ClusterAPI.md#V3ListClusterNodes) | **Get** /v3/cluster/nodes | List cluster nodes
[**V3ListClusterSnapshots**](ClusterAPI.md#V3ListClusterSnapshots) | **Get** /v3/cluster/snapshots | List cluster snapshots
[**V3PatchClusterConfig**](ClusterAPI.md#V3PatchClusterConfig) | **Patch** /v3/cluster/config | Update cluster configuration



## V3DeleteClusterSnapshot

> V3DeleteClusterSnapshot(ctx, snapshotId).Execute()

Delete cluster snapshot



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
	snapshotId := "c67af9c0-26cd-4233-9782-436c842b60db" // string | Snapshot identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ClusterAPI.V3DeleteClusterSnapshot(context.Background(), snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAPI.V3DeleteClusterSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteClusterSnapshotRequest struct via the builder pattern


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


## V3GetClusterConfig

> ClusterConfig V3GetClusterConfig(ctx).Execute()

Get cluster configuration



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAPI.V3GetClusterConfig(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAPI.V3GetClusterConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetClusterConfig`: ClusterConfig
	fmt.Fprintf(os.Stdout, "Response from `ClusterAPI.V3GetClusterConfig`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetClusterConfigRequest struct via the builder pattern


### Return type

[**ClusterConfig**](ClusterConfig.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetClusterNode

> NodeInformation V3GetClusterNode(ctx, nodeId).Execute()

Get cluster node



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
	nodeId := "2x3ZOdu4pshouoY0kttRPoiIk5s" // string | Node identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAPI.V3GetClusterNode(context.Background(), nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAPI.V3GetClusterNode``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetClusterNode`: NodeInformation
	fmt.Fprintf(os.Stdout, "Response from `ClusterAPI.V3GetClusterNode`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**nodeId** | **string** | Node identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetClusterNodeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NodeInformation**](NodeInformation.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetClusterNodeConsole

> NodeConsoleEndpoint V3GetClusterNodeConsole(ctx, nodeId).Execute()

Get node console websocket URL



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
	nodeId := "2x3ZOdu4pshouoY0kttRPoiIk5s" // string | Node identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAPI.V3GetClusterNodeConsole(context.Background(), nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAPI.V3GetClusterNodeConsole``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetClusterNodeConsole`: NodeConsoleEndpoint
	fmt.Fprintf(os.Stdout, "Response from `ClusterAPI.V3GetClusterNodeConsole`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**nodeId** | **string** | Node identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetClusterNodeConsoleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NodeConsoleEndpoint**](NodeConsoleEndpoint.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetClusterSnapshot

> ClusterSnapshot V3GetClusterSnapshot(ctx, snapshotId).Execute()

Get cluster snapshot



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
	snapshotId := "c67af9c0-26cd-4233-9782-436c842b60db" // string | Snapshot identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAPI.V3GetClusterSnapshot(context.Background(), snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAPI.V3GetClusterSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetClusterSnapshot`: ClusterSnapshot
	fmt.Fprintf(os.Stdout, "Response from `ClusterAPI.V3GetClusterSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetClusterSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ClusterSnapshot**](ClusterSnapshot.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListClusterNodes

> NodeList V3ListClusterNodes(ctx).Limit(limit).Offset(offset).Execute()

List cluster nodes



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
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAPI.V3ListClusterNodes(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAPI.V3ListClusterNodes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListClusterNodes`: NodeList
	fmt.Fprintf(os.Stdout, "Response from `ClusterAPI.V3ListClusterNodes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListClusterNodesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**NodeList**](NodeList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListClusterSnapshots

> ClusterSnapshotList V3ListClusterSnapshots(ctx).Limit(limit).Offset(offset).Springboard(springboard).Live(live).Fresh(fresh).DeviceName(deviceName).Task(task).Search(search).To(to).From(from).OrderBy(orderBy).Execute()

List cluster snapshots



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	limit := float32(100) // float32 | Number of entries to return. (optional) (default to 100)
	offset := float32(0) // float32 | Number of rows to skip. (optional) (default to 0)
	springboard := "true" // string | Filter by springboard snapshot flag. (optional)
	live := "true" // string | Filter by live snapshot flag. (optional)
	fresh := "false" // string | Filter by fresh snapshot flag. (optional)
	deviceName := "iPhone 13 Pro" // string | Filter by device name. (optional)
	task := "creating" // string | Filter by task being executed on the snapshot. (optional)
	search := "pre-update" // string | Fuzzy search on snapshot and instance name or ID. (optional)
	to := time.Now() // time.Time | Filter to this date (based on createdAt). (optional)
	from := time.Now() // time.Time | Filter from this date (based on createdAt). (optional)
	orderBy := "-createdAt" // string | Sort field and direction. (optional) (default to "-createdAt")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterAPI.V3ListClusterSnapshots(context.Background()).Limit(limit).Offset(offset).Springboard(springboard).Live(live).Fresh(fresh).DeviceName(deviceName).Task(task).Search(search).To(to).From(from).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAPI.V3ListClusterSnapshots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListClusterSnapshots`: ClusterSnapshotList
	fmt.Fprintf(os.Stdout, "Response from `ClusterAPI.V3ListClusterSnapshots`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListClusterSnapshotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Number of entries to return. | [default to 100]
 **offset** | **float32** | Number of rows to skip. | [default to 0]
 **springboard** | **string** | Filter by springboard snapshot flag. | 
 **live** | **string** | Filter by live snapshot flag. | 
 **fresh** | **string** | Filter by fresh snapshot flag. | 
 **deviceName** | **string** | Filter by device name. | 
 **task** | **string** | Filter by task being executed on the snapshot. | 
 **search** | **string** | Fuzzy search on snapshot and instance name or ID. | 
 **to** | **time.Time** | Filter to this date (based on createdAt). | 
 **from** | **time.Time** | Filter from this date (based on createdAt). | 
 **orderBy** | **string** | Sort field and direction. | [default to &quot;-createdAt&quot;]

### Return type

[**ClusterSnapshotList**](ClusterSnapshotList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchClusterConfig

> V3PatchClusterConfig(ctx).PatchClusterConfigBody(patchClusterConfigBody).Execute()

Update cluster configuration



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
	patchClusterConfigBody := *openapiclient.NewPatchClusterConfigBody() // PatchClusterConfigBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ClusterAPI.V3PatchClusterConfig(context.Background()).PatchClusterConfigBody(patchClusterConfigBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAPI.V3PatchClusterConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchClusterConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **patchClusterConfigBody** | [**PatchClusterConfigBody**](PatchClusterConfigBody.md) |  | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

