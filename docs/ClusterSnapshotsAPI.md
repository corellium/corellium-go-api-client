# \ClusterSnapshotsAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1DeleteClusterSnapshot**](ClusterSnapshotsAPI.md#V1DeleteClusterSnapshot) | **Delete** /v1/cluster/snapshots/{snapshotId} | Delete a Cluster Snapshot
[**V1GetClusterSnapshot**](ClusterSnapshotsAPI.md#V1GetClusterSnapshot) | **Get** /v1/cluster/snapshots/{snapshotId} | Get Cluster Snapshot
[**V1GetClusterSnapshots**](ClusterSnapshotsAPI.md#V1GetClusterSnapshots) | **Get** /v1/cluster/snapshots | Get Cluster Snapshots



## V1DeleteClusterSnapshot

> V1DeleteClusterSnapshot(ctx, snapshotId).Execute()

Delete a Cluster Snapshot

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
	snapshotId := "snapshotId_example" // string | Snapshot ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ClusterSnapshotsAPI.V1DeleteClusterSnapshot(context.Background(), snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterSnapshotsAPI.V1DeleteClusterSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteClusterSnapshotRequest struct via the builder pattern


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


## V1GetClusterSnapshot

> ClusterSnapshotV1 V1GetClusterSnapshot(ctx, snapshotId).Execute()

Get Cluster Snapshot

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
	snapshotId := "snapshotId_example" // string | Snapshot ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterSnapshotsAPI.V1GetClusterSnapshot(context.Background(), snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterSnapshotsAPI.V1GetClusterSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetClusterSnapshot`: ClusterSnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `ClusterSnapshotsAPI.V1GetClusterSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetClusterSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ClusterSnapshotV1**](ClusterSnapshotV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetClusterSnapshots

> SnapshotList V1GetClusterSnapshots(ctx).Request(request).Execute()

Get Cluster Snapshots

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
	request := *openapiclient.NewSnapshotRequest() // SnapshotRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClusterSnapshotsAPI.V1GetClusterSnapshots(context.Background()).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterSnapshotsAPI.V1GetClusterSnapshots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetClusterSnapshots`: SnapshotList
	fmt.Fprintf(os.Stdout, "Response from `ClusterSnapshotsAPI.V1GetClusterSnapshots`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1GetClusterSnapshotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**SnapshotRequest**](SnapshotRequest.md) |  | 

### Return type

[**SnapshotList**](SnapshotList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

