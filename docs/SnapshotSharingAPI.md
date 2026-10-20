# \SnapshotSharingAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3AcceptSharedSnapshot**](SnapshotSharingAPI.md#V3AcceptSharedSnapshot) | **Post** /v3/snapshots/accept | Accept a shared snapshot
[**V3DeleteSnapshotPermissions**](SnapshotSharingAPI.md#V3DeleteSnapshotPermissions) | **Delete** /v3/snapshots/{snapshotId}/permissions | Delete member(s)
[**V3GetSharedSnapshots**](SnapshotSharingAPI.md#V3GetSharedSnapshots) | **Get** /v3/snapshots/shared | Fetch shared snapshots
[**V3SetSnapshotPermissions**](SnapshotSharingAPI.md#V3SetSnapshotPermissions) | **Post** /v3/snapshots/{snapshotId}/permissions | Set member list
[**V3ShareSnapshot**](SnapshotSharingAPI.md#V3ShareSnapshot) | **Post** /v3/snapshots/{snapshotId}/share | Create or update snapshot sharing



## V3AcceptSharedSnapshot

> Snapshot V3AcceptSharedSnapshot(ctx).AcceptSnapshotBody(acceptSnapshotBody).Execute()

Accept a shared snapshot



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
	acceptSnapshotBody := *openapiclient.NewAcceptSnapshotBody("X7QK9P2M") // AcceptSnapshotBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotSharingAPI.V3AcceptSharedSnapshot(context.Background()).AcceptSnapshotBody(acceptSnapshotBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingAPI.V3AcceptSharedSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3AcceptSharedSnapshot`: Snapshot
	fmt.Fprintf(os.Stdout, "Response from `SnapshotSharingAPI.V3AcceptSharedSnapshot`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3AcceptSharedSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptSnapshotBody** | [**AcceptSnapshotBody**](AcceptSnapshotBody.md) |  | 

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


## V3DeleteSnapshotPermissions

> V3DeleteSnapshotPermissions(ctx, snapshotId).SetSnapshotPermissionsBody(setSnapshotPermissionsBody).Execute()

Delete member(s)



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
	setSnapshotPermissionsBody := *openapiclient.NewSetSnapshotPermissionsBody([]string{"Members_example"}) // SetSnapshotPermissionsBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SnapshotSharingAPI.V3DeleteSnapshotPermissions(context.Background(), snapshotId).SetSnapshotPermissionsBody(setSnapshotPermissionsBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingAPI.V3DeleteSnapshotPermissions``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3DeleteSnapshotPermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setSnapshotPermissionsBody** | [**SetSnapshotPermissionsBody**](SetSnapshotPermissionsBody.md) |  | 

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


## V3GetSharedSnapshots

> SharedSnapshotsResponse V3GetSharedSnapshots(ctx).Execute()

Fetch shared snapshots



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
	resp, r, err := apiClient.SnapshotSharingAPI.V3GetSharedSnapshots(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingAPI.V3GetSharedSnapshots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetSharedSnapshots`: SharedSnapshotsResponse
	fmt.Fprintf(os.Stdout, "Response from `SnapshotSharingAPI.V3GetSharedSnapshots`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetSharedSnapshotsRequest struct via the builder pattern


### Return type

[**SharedSnapshotsResponse**](SharedSnapshotsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3SetSnapshotPermissions

> Snapshot V3SetSnapshotPermissions(ctx, snapshotId).SetSnapshotPermissionsBody(setSnapshotPermissionsBody).Execute()

Set member list



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
	setSnapshotPermissionsBody := *openapiclient.NewSetSnapshotPermissionsBody([]string{"Members_example"}) // SetSnapshotPermissionsBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotSharingAPI.V3SetSnapshotPermissions(context.Background(), snapshotId).SetSnapshotPermissionsBody(setSnapshotPermissionsBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingAPI.V3SetSnapshotPermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3SetSnapshotPermissions`: Snapshot
	fmt.Fprintf(os.Stdout, "Response from `SnapshotSharingAPI.V3SetSnapshotPermissions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3SetSnapshotPermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setSnapshotPermissionsBody** | [**SetSnapshotPermissionsBody**](SetSnapshotPermissionsBody.md) |  | 

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


## V3ShareSnapshot

> Snapshot V3ShareSnapshot(ctx, snapshotId).ShareSnapshotBody(shareSnapshotBody).Execute()

Create or update snapshot sharing



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
	shareSnapshotBody := *openapiclient.NewShareSnapshotBody(openapiclient.SnapshotSharingType("publicLink")) // ShareSnapshotBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotSharingAPI.V3ShareSnapshot(context.Background(), snapshotId).ShareSnapshotBody(shareSnapshotBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingAPI.V3ShareSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ShareSnapshot`: Snapshot
	fmt.Fprintf(os.Stdout, "Response from `SnapshotSharingAPI.V3ShareSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ShareSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **shareSnapshotBody** | [**ShareSnapshotBody**](ShareSnapshotBody.md) |  | 

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

