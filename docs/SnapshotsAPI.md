# \SnapshotsAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateInstanceSnapshot**](SnapshotsAPI.md#V3CreateInstanceSnapshot) | **Post** /v3/instances/{instanceId}/snapshots | Create instance snapshot
[**V3DeleteInstanceSnapshot**](SnapshotsAPI.md#V3DeleteInstanceSnapshot) | **Delete** /v3/instances/{instanceId}/snapshots/{snapshotId} | Delete an instance snapshot
[**V3DeleteSnapshot**](SnapshotsAPI.md#V3DeleteSnapshot) | **Delete** /v3/snapshots/{snapshotId} | Delete a snapshot
[**V3GetInstanceSnapshot**](SnapshotsAPI.md#V3GetInstanceSnapshot) | **Get** /v3/instances/{instanceId}/snapshots/{snapshotId} | Get instance snapshot
[**V3GetSnapshot**](SnapshotsAPI.md#V3GetSnapshot) | **Get** /v3/snapshots/{snapshotId} | Get snapshot
[**V3ListInstanceSnapshots**](SnapshotsAPI.md#V3ListInstanceSnapshots) | **Get** /v3/instances/{instanceId}/snapshots | List instance snapshots
[**V3PatchInstanceSnapshot**](SnapshotsAPI.md#V3PatchInstanceSnapshot) | **Patch** /v3/instances/{instanceId}/snapshots/{snapshotId} | Update an instance snapshot
[**V3RestoreInstanceSnapshot**](SnapshotsAPI.md#V3RestoreInstanceSnapshot) | **Post** /v3/instances/{instanceId}/snapshots/{snapshotId}/restore | Restore instance snapshot
[**V3UpdateSnapshot**](SnapshotsAPI.md#V3UpdateSnapshot) | **Patch** /v3/snapshots/{snapshotId} | Update snapshot name



## V3CreateInstanceSnapshot

> Snapshot V3CreateInstanceSnapshot(ctx, instanceId).CreateSnapshotBody(createSnapshotBody).Execute()

Create instance snapshot



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
	createSnapshotBody := *openapiclient.NewCreateSnapshotBody("before-update") // CreateSnapshotBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotsAPI.V3CreateInstanceSnapshot(context.Background(), instanceId).CreateSnapshotBody(createSnapshotBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsAPI.V3CreateInstanceSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateInstanceSnapshot`: Snapshot
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsAPI.V3CreateInstanceSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateInstanceSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createSnapshotBody** | [**CreateSnapshotBody**](CreateSnapshotBody.md) |  | 

### Return type

[**Snapshot**](Snapshot.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteInstanceSnapshot

> V3DeleteInstanceSnapshot(ctx, instanceId, snapshotId).Execute()

Delete an instance snapshot



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
	snapshotId := "c67af9c0-26cd-4233-9782-436c842b60db" // string | Snapshot identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SnapshotsAPI.V3DeleteInstanceSnapshot(context.Background(), instanceId, snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsAPI.V3DeleteInstanceSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance identifier. | 
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteInstanceSnapshotRequest struct via the builder pattern


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


## V3DeleteSnapshot

> V3DeleteSnapshot(ctx, snapshotId).Execute()

Delete a snapshot



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
	r, err := apiClient.SnapshotsAPI.V3DeleteSnapshot(context.Background(), snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsAPI.V3DeleteSnapshot``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3DeleteSnapshotRequest struct via the builder pattern


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


## V3GetInstanceSnapshot

> Snapshot V3GetInstanceSnapshot(ctx, instanceId, snapshotId).Execute()

Get instance snapshot



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
	snapshotId := "c67af9c0-26cd-4233-9782-436c842b60db" // string | Snapshot identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotsAPI.V3GetInstanceSnapshot(context.Background(), instanceId, snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsAPI.V3GetInstanceSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstanceSnapshot`: Snapshot
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsAPI.V3GetInstanceSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance identifier. | 
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstanceSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Snapshot**](Snapshot.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetSnapshot

> Snapshot V3GetSnapshot(ctx, snapshotId).Execute()

Get snapshot



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
	resp, r, err := apiClient.SnapshotsAPI.V3GetSnapshot(context.Background(), snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsAPI.V3GetSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetSnapshot`: Snapshot
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsAPI.V3GetSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Snapshot**](Snapshot.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListInstanceSnapshots

> InstanceSnapshotsList V3ListInstanceSnapshots(ctx, instanceId).Limit(limit).Offset(offset).Execute()

List instance snapshots



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotsAPI.V3ListInstanceSnapshots(context.Background(), instanceId).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsAPI.V3ListInstanceSnapshots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListInstanceSnapshots`: InstanceSnapshotsList
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsAPI.V3ListInstanceSnapshots`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListInstanceSnapshotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**InstanceSnapshotsList**](InstanceSnapshotsList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchInstanceSnapshot

> Snapshot V3PatchInstanceSnapshot(ctx, instanceId, snapshotId).CreateSnapshotBody(createSnapshotBody).Execute()

Update an instance snapshot



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
	snapshotId := "c67af9c0-26cd-4233-9782-436c842b60db" // string | Snapshot identifier.
	createSnapshotBody := *openapiclient.NewCreateSnapshotBody("before-update") // CreateSnapshotBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotsAPI.V3PatchInstanceSnapshot(context.Background(), instanceId, snapshotId).CreateSnapshotBody(createSnapshotBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsAPI.V3PatchInstanceSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PatchInstanceSnapshot`: Snapshot
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsAPI.V3PatchInstanceSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance identifier. | 
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchInstanceSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createSnapshotBody** | [**CreateSnapshotBody**](CreateSnapshotBody.md) |  | 

### Return type

[**Snapshot**](Snapshot.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3RestoreInstanceSnapshot

> V3RestoreInstanceSnapshot(ctx, instanceId, snapshotId).Execute()

Restore instance snapshot



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
	snapshotId := "c67af9c0-26cd-4233-9782-436c842b60db" // string | Snapshot identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SnapshotsAPI.V3RestoreInstanceSnapshot(context.Background(), instanceId, snapshotId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsAPI.V3RestoreInstanceSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance identifier. | 
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RestoreInstanceSnapshotRequest struct via the builder pattern


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


## V3UpdateSnapshot

> Snapshot V3UpdateSnapshot(ctx, snapshotId).V3UpdateSnapshotRequest(v3UpdateSnapshotRequest).Execute()

Update snapshot name



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
	v3UpdateSnapshotRequest := *openapiclient.NewV3UpdateSnapshotRequest("Clean boot") // V3UpdateSnapshotRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotsAPI.V3UpdateSnapshot(context.Background(), snapshotId).V3UpdateSnapshotRequest(v3UpdateSnapshotRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotsAPI.V3UpdateSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3UpdateSnapshot`: Snapshot
	fmt.Fprintf(os.Stdout, "Response from `SnapshotsAPI.V3UpdateSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UpdateSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v3UpdateSnapshotRequest** | [**V3UpdateSnapshotRequest**](V3UpdateSnapshotRequest.md) |  | 

### Return type

[**Snapshot**](Snapshot.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

