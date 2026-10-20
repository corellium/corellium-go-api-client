# \SnapshotSharingV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1AcceptSharedSnapshot**](SnapshotSharingV1API.md#V1AcceptSharedSnapshot) | **Post** /v1/snapshots/accept | Accept a snapshot shared with you
[**V1DeleteSnapshotPermissions**](SnapshotSharingV1API.md#V1DeleteSnapshotPermissions) | **Delete** /v1/snapshots/{snapshotId}/permissions | Delete member(s)
[**V1GetSharedSnapshots**](SnapshotSharingV1API.md#V1GetSharedSnapshots) | **Get** /v1/snapshots/shared | Fetch shared snapshots
[**V1SetSnapshotPermissions**](SnapshotSharingV1API.md#V1SetSnapshotPermissions) | **Post** /v1/snapshots/{snapshotId}/permissions | Set member list
[**V1ShareSnapshot**](SnapshotSharingV1API.md#V1ShareSnapshot) | **Post** /v1/snapshots/{snapshotId}/share | Share snapshot



## V1AcceptSharedSnapshot

> SnapshotV1 V1AcceptSharedSnapshot(ctx).AcceptSnapshotRequestPayload(acceptSnapshotRequestPayload).Execute()

Accept a snapshot shared with you

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
	acceptSnapshotRequestPayload := *openapiclient.NewAcceptSnapshotRequestPayload("AccessCode_example") // AcceptSnapshotRequestPayload | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotSharingV1API.V1AcceptSharedSnapshot(context.Background()).AcceptSnapshotRequestPayload(acceptSnapshotRequestPayload).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingV1API.V1AcceptSharedSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AcceptSharedSnapshot`: SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotSharingV1API.V1AcceptSharedSnapshot`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1AcceptSharedSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptSnapshotRequestPayload** | [**AcceptSnapshotRequestPayload**](AcceptSnapshotRequestPayload.md) |  | 

### Return type

[**SnapshotV1**](SnapshotV1.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteSnapshotPermissions

> SnapshotV1 V1DeleteSnapshotPermissions(ctx, snapshotId).SnapshotPermissionsRequestPayload(snapshotPermissionsRequestPayload).Execute()

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
	snapshotId := "snapshotId_example" // string | Snapshot ID - uuid
	snapshotPermissionsRequestPayload := *openapiclient.NewSnapshotPermissionsRequestPayload([]string{"Members_example"}) // SnapshotPermissionsRequestPayload | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotSharingV1API.V1DeleteSnapshotPermissions(context.Background(), snapshotId).SnapshotPermissionsRequestPayload(snapshotPermissionsRequestPayload).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingV1API.V1DeleteSnapshotPermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DeleteSnapshotPermissions`: SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotSharingV1API.V1DeleteSnapshotPermissions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteSnapshotPermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **snapshotPermissionsRequestPayload** | [**SnapshotPermissionsRequestPayload**](SnapshotPermissionsRequestPayload.md) |  | 

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


## V1GetSharedSnapshots

> UserSnapshots V1GetSharedSnapshots(ctx).Execute()

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
	resp, r, err := apiClient.SnapshotSharingV1API.V1GetSharedSnapshots(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingV1API.V1GetSharedSnapshots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetSharedSnapshots`: UserSnapshots
	fmt.Fprintf(os.Stdout, "Response from `SnapshotSharingV1API.V1GetSharedSnapshots`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetSharedSnapshotsRequest struct via the builder pattern


### Return type

[**UserSnapshots**](UserSnapshots.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1SetSnapshotPermissions

> SnapshotV1 V1SetSnapshotPermissions(ctx, snapshotId).SnapshotPermissionsRequestPayload(snapshotPermissionsRequestPayload).Execute()

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
	snapshotId := "snapshotId_example" // string | Snapshot ID - uuid
	snapshotPermissionsRequestPayload := *openapiclient.NewSnapshotPermissionsRequestPayload([]string{"Members_example"}) // SnapshotPermissionsRequestPayload | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotSharingV1API.V1SetSnapshotPermissions(context.Background(), snapshotId).SnapshotPermissionsRequestPayload(snapshotPermissionsRequestPayload).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingV1API.V1SetSnapshotPermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1SetSnapshotPermissions`: SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotSharingV1API.V1SetSnapshotPermissions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1SetSnapshotPermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **snapshotPermissionsRequestPayload** | [**SnapshotPermissionsRequestPayload**](SnapshotPermissionsRequestPayload.md) |  | 

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


## V1ShareSnapshot

> SnapshotV1 V1ShareSnapshot(ctx, snapshotId).PostShareSnapshotRequestPayload(postShareSnapshotRequestPayload).Execute()

Share snapshot



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
	postShareSnapshotRequestPayload := *openapiclient.NewPostShareSnapshotRequestPayload("SharingType_example") // PostShareSnapshotRequestPayload | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SnapshotSharingV1API.V1ShareSnapshot(context.Background(), snapshotId).PostShareSnapshotRequestPayload(postShareSnapshotRequestPayload).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SnapshotSharingV1API.V1ShareSnapshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ShareSnapshot`: SnapshotV1
	fmt.Fprintf(os.Stdout, "Response from `SnapshotSharingV1API.V1ShareSnapshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**snapshotId** | **string** | Snapshot ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1ShareSnapshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **postShareSnapshotRequestPayload** | [**PostShareSnapshotRequestPayload**](PostShareSnapshotRequestPayload.md) |  | 

### Return type

[**SnapshotV1**](SnapshotV1.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

