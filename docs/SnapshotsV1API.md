# \SnapshotsV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1CreateSnapshot**](SnapshotsV1API.md#V1CreateSnapshot) | **Post** /v1/instances/{instanceId}/snapshots | Create Instance Snapshot
[**V1DeleteInstanceSnapshot**](SnapshotsV1API.md#V1DeleteInstanceSnapshot) | **Delete** /v1/instances/{instanceId}/snapshots/{snapshotId} | Delete an Instance Snapshot
[**V1DeleteSnapshot**](SnapshotsV1API.md#V1DeleteSnapshot) | **Delete** /v1/snapshots/{snapshotId} | Delete a Snapshot
[**V1GetInstanceSnapshot**](SnapshotsV1API.md#V1GetInstanceSnapshot) | **Get** /v1/instances/{instanceId}/snapshots/{snapshotId} | Get Instance Snapshot
[**V1GetInstanceSnapshots**](SnapshotsV1API.md#V1GetInstanceSnapshots) | **Get** /v1/instances/{instanceId}/snapshots | Get Instance Snapshots
[**V1GetSnapshot**](SnapshotsV1API.md#V1GetSnapshot) | **Get** /v1/snapshots/{snapshotId} | Get Snapshot
[**V1RenameInstanceSnapshot**](SnapshotsV1API.md#V1RenameInstanceSnapshot) | **Patch** /v1/instances/{instanceId}/snapshots/{snapshotId} | Rename an Instance Snapshot
[**V1RestoreInstanceSnapshot**](SnapshotsV1API.md#V1RestoreInstanceSnapshot) | **Post** /v1/instances/{instanceId}/snapshots/{snapshotId}/restore | Restore an Instance Snapshot
[**V1SnapshotRename**](SnapshotsV1API.md#V1SnapshotRename) | **Patch** /v1/snapshots/{snapshotId} | Rename a Snapshot



## V1CreateSnapshot

> SnapshotV1 V1CreateSnapshot(ctx, instanceId).SnapshotCreationOptions(snapshotCreationOptions).Execute()

Create Instance Snapshot

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
	snapshotCreationOptions := *openapiclient.NewSnapshotCreationOptions("Name_example") // SnapshotCreationOptions | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotsV1API.V1CreateSnapshot(context.Background(), instanceId).SnapshotCreationOptions(snapshotCreationOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsV1API.V1CreateSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateSnapshot`: SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsV1API.V1CreateSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **snapshotCreationOptions** | [**SnapshotCreationOptions**](SnapshotCreationOptions.md) |  | 

### Return type

[**SnapshotV1**](SnapshotV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteInstanceSnapshot

> V1DeleteInstanceSnapshot(ctx, instanceId, snapshotId).Execute()

Delete an Instance Snapshot

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
	snapshotId := "snapshotId_example" // string | Snapshot ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SnapshotsV1API.V1DeleteInstanceSnapshot(context.Background(), instanceId, snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsV1API.V1DeleteInstanceSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteInstanceSnapshotRequest struct via the builder pattern


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


## V1DeleteSnapshot

> V1DeleteSnapshot(ctx, snapshotId).Execute()

Delete a Snapshot

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
	r, err := apiClient.SnapshotsV1API.V1DeleteSnapshot(context.Background(), snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsV1API.V1DeleteSnapshot``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1DeleteSnapshotRequest struct via the builder pattern


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


## V1GetInstanceSnapshot

> SnapshotV1 V1GetInstanceSnapshot(ctx, instanceId, snapshotId).Execute()

Get Instance Snapshot

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
	snapshotId := "snapshotId_example" // string | Snapshot ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotsV1API.V1GetInstanceSnapshot(context.Background(), instanceId, snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsV1API.V1GetInstanceSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstanceSnapshot`: SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsV1API.V1GetInstanceSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstanceSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**SnapshotV1**](SnapshotV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetInstanceSnapshots

> []SnapshotV1 V1GetInstanceSnapshots(ctx, instanceId).Execute()

Get Instance Snapshots

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
	resp, r, err := apiClient.SnapshotsV1API.V1GetInstanceSnapshots(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsV1API.V1GetInstanceSnapshots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstanceSnapshots`: []SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsV1API.V1GetInstanceSnapshots`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstanceSnapshotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]SnapshotV1**](SnapshotV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetSnapshot

> SnapshotV1 V1GetSnapshot(ctx, snapshotId).Execute()

Get Snapshot

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
	resp, r, err := apiClient.SnapshotsV1API.V1GetSnapshot(context.Background(), snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsV1API.V1GetSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetSnapshot`: SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsV1API.V1GetSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SnapshotV1**](SnapshotV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1RenameInstanceSnapshot

> SnapshotV1 V1RenameInstanceSnapshot(ctx, instanceId, snapshotId).SnapshotCreationOptions(snapshotCreationOptions).Execute()

Rename an Instance Snapshot

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
	snapshotId := "snapshotId_example" // string | Snapshot ID - uuid
	snapshotCreationOptions := *openapiclient.NewSnapshotCreationOptions("Name_example") // SnapshotCreationOptions | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotsV1API.V1RenameInstanceSnapshot(context.Background(), instanceId, snapshotId).SnapshotCreationOptions(snapshotCreationOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsV1API.V1RenameInstanceSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1RenameInstanceSnapshot`: SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsV1API.V1RenameInstanceSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1RenameInstanceSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **snapshotCreationOptions** | [**SnapshotCreationOptions**](SnapshotCreationOptions.md) |  | 

### Return type

[**SnapshotV1**](SnapshotV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1RestoreInstanceSnapshot

> V1RestoreInstanceSnapshot(ctx, instanceId, snapshotId).Execute()

Restore an Instance Snapshot

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
	snapshotId := "snapshotId_example" // string | Snapshot ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SnapshotsV1API.V1RestoreInstanceSnapshot(context.Background(), instanceId, snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsV1API.V1RestoreInstanceSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1RestoreInstanceSnapshotRequest struct via the builder pattern


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


## V1SnapshotRename

> SnapshotV1 V1SnapshotRename(ctx, snapshotId).SnapshotCreationOptions(snapshotCreationOptions).Execute()

Rename a Snapshot

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
	snapshotCreationOptions := *openapiclient.NewSnapshotCreationOptions("Name_example") // SnapshotCreationOptions | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotsV1API.V1SnapshotRename(context.Background(), snapshotId).SnapshotCreationOptions(snapshotCreationOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsV1API.V1SnapshotRename``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1SnapshotRename`: SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsV1API.V1SnapshotRename`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1SnapshotRenameRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **snapshotCreationOptions** | [**SnapshotCreationOptions**](SnapshotCreationOptions.md) |  | 

### Return type

[**SnapshotV1**](SnapshotV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

