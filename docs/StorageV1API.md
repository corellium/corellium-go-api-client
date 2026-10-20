# \StorageV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1AttachStorageCluster**](StorageV1API.md#V1AttachStorageCluster) | **Post** /v1/cluster/storage/{id}/attach | Mount and attach a storage device
[**V1EjectStorageCluster**](StorageV1API.md#V1EjectStorageCluster) | **Post** /v1/cluster/storage/{id}/eject | Eject/Unmount removable media
[**V1ListStorage**](StorageV1API.md#V1ListStorage) | **Get** /v1/storage | Get storage devices
[**V1ListStorageCluster**](StorageV1API.md#V1ListStorageCluster) | **Get** /v1/cluster/storage | Get storage devices
[**V1ListStorageFiles**](StorageV1API.md#V1ListStorageFiles) | **Get** /v1/storage/{id}/files/{path} | List Storage Files



## V1AttachStorageCluster

> map[string]interface{} V1AttachStorageCluster(ctx, id).Execute()

Mount and attach a storage device



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
	id := "id_example" // string | The unique identifier of the storage media

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageV1API.V1AttachStorageCluster(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageV1API.V1AttachStorageCluster``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AttachStorageCluster`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `StorageV1API.V1AttachStorageCluster`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique identifier of the storage media | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AttachStorageClusterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1EjectStorageCluster

> map[string]interface{} V1EjectStorageCluster(ctx, id).Execute()

Eject/Unmount removable media



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
	id := "id_example" // string | Storage device identifier (UUID)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageV1API.V1EjectStorageCluster(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageV1API.V1EjectStorageCluster``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1EjectStorageCluster`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `StorageV1API.V1EjectStorageCluster`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Storage device identifier (UUID) | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1EjectStorageClusterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListStorage

> GetStorageResponse V1ListStorage(ctx).Limit(limit).Offset(offset).Identifier(identifier).Device(device).FsType(fsType).MountPolicy(mountPolicy).Status(status).Sort(sort).Execute()

Get storage devices



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
	limit := float32(8.14) // float32 | Maximum number of results to return (1–1000, default: 100) (optional)
	offset := float32(8.14) // float32 | Number of results to skip (default: 0) (optional)
	identifier := "identifier_example" // string | Filter by identifier (comma separated) (optional)
	device := "device_example" // string | Filter by device name (partial match) (optional)
	fsType := "fsType_example" // string | Filter by filesystem type (comma separated) (optional)
	mountPolicy := "mountPolicy_example" // string | Filter by mount policy (RO or RW) (optional)
	status := "status_example" // string | Filter by status (unmounted or mounted) (optional)
	sort := "sort_example" // string | Sort order (e.g. \"device\" or \"-device\") (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageV1API.V1ListStorage(context.Background()).Limit(limit).Offset(offset).Identifier(identifier).Device(device).FsType(fsType).MountPolicy(mountPolicy).Status(status).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageV1API.V1ListStorage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListStorage`: GetStorageResponse
	fmt.Fprintf(os.Stdout, "Response from `StorageV1API.V1ListStorage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ListStorageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Maximum number of results to return (1–1000, default: 100) | 
 **offset** | **float32** | Number of results to skip (default: 0) | 
 **identifier** | **string** | Filter by identifier (comma separated) | 
 **device** | **string** | Filter by device name (partial match) | 
 **fsType** | **string** | Filter by filesystem type (comma separated) | 
 **mountPolicy** | **string** | Filter by mount policy (RO or RW) | 
 **status** | **string** | Filter by status (unmounted or mounted) | 
 **sort** | **string** | Sort order (e.g. \&quot;device\&quot; or \&quot;-device\&quot;) | 

### Return type

[**GetStorageResponse**](GetStorageResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListStorageCluster

> GetStorageResponse V1ListStorageCluster(ctx).Limit(limit).Offset(offset).Device(device).FsType(fsType).FsUUID(fsUUID).Label(label).Serial(serial).Vendor(vendor).Model(model).MountPolicy(mountPolicy).Status(status).Sort(sort).Execute()

Get storage devices



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
	limit := float32(8.14) // float32 | Maximum number of results to return (1–1000, default: 100) (optional)
	offset := float32(8.14) // float32 | Number of results to skip (default: 0) (optional)
	device := "device_example" // string | Filter by device name (partial match) (optional)
	fsType := "fsType_example" // string | Filter by filesystem type (comma separated) (optional)
	fsUUID := "fsUUID_example" // string | Filter by filesystem UUID (partial match) (optional)
	label := "label_example" // string | Filter by label (partial match) (optional)
	serial := "serial_example" // string | Filter by serial number (partial match) (optional)
	vendor := "vendor_example" // string | Filter by vendor (partial match) (optional)
	model := "model_example" // string | Filter by model (partial match) (optional)
	mountPolicy := "mountPolicy_example" // string | Filter by mount policy (RO or RW) (optional)
	status := "status_example" // string | Filter by status (unmounted or mounted) (optional)
	sort := "sort_example" // string | Sort order (e.g. \"device\" or \"-device\") (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageV1API.V1ListStorageCluster(context.Background()).Limit(limit).Offset(offset).Device(device).FsType(fsType).FsUUID(fsUUID).Label(label).Serial(serial).Vendor(vendor).Model(model).MountPolicy(mountPolicy).Status(status).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageV1API.V1ListStorageCluster``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListStorageCluster`: GetStorageResponse
	fmt.Fprintf(os.Stdout, "Response from `StorageV1API.V1ListStorageCluster`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ListStorageClusterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Maximum number of results to return (1–1000, default: 100) | 
 **offset** | **float32** | Number of results to skip (default: 0) | 
 **device** | **string** | Filter by device name (partial match) | 
 **fsType** | **string** | Filter by filesystem type (comma separated) | 
 **fsUUID** | **string** | Filter by filesystem UUID (partial match) | 
 **label** | **string** | Filter by label (partial match) | 
 **serial** | **string** | Filter by serial number (partial match) | 
 **vendor** | **string** | Filter by vendor (partial match) | 
 **model** | **string** | Filter by model (partial match) | 
 **mountPolicy** | **string** | Filter by mount policy (RO or RW) | 
 **status** | **string** | Filter by status (unmounted or mounted) | 
 **sort** | **string** | Sort order (e.g. \&quot;device\&quot; or \&quot;-device\&quot;) | 

### Return type

[**GetStorageResponse**](GetStorageResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListStorageFiles

> map[string]interface{} V1ListStorageFiles(ctx, id, path).Limit(limit).Offset(offset).Name(name).Type_(type_).Sort(sort).Execute()

List Storage Files



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
	id := "id_example" // string | Storage device identifier (MediaStore identifier)
	path := "path_example" // string | Path within the storage device to list
	limit := float32(8.14) // float32 | Maximum number of results to return (1–1000, default: 100) (optional)
	offset := float32(8.14) // float32 | Number of results to skip (default: 0) (optional)
	name := "name_example" // string | Filter by name (case insensitive exact match, comma separated for multiple values) (optional)
	type_ := "type__example" // string | Filter by type (case insensitive partial match, e.g. \"file\" or \"dir\") (optional)
	sort := "sort_example" // string | Sort order (e.g., 'name', '-name', 'type,-size,-lastModifiedTime'). Prefix with '-' for descending. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageV1API.V1ListStorageFiles(context.Background(), id, path).Limit(limit).Offset(offset).Name(name).Type_(type_).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageV1API.V1ListStorageFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListStorageFiles`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `StorageV1API.V1ListStorageFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Storage device identifier (MediaStore identifier) | 
**path** | **string** | Path within the storage device to list | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1ListStorageFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **limit** | **float32** | Maximum number of results to return (1–1000, default: 100) | 
 **offset** | **float32** | Number of results to skip (default: 0) | 
 **name** | **string** | Filter by name (case insensitive exact match, comma separated for multiple values) | 
 **type_** | **string** | Filter by type (case insensitive partial match, e.g. \&quot;file\&quot; or \&quot;dir\&quot;) | 
 **sort** | **string** | Sort order (e.g., &#39;name&#39;, &#39;-name&#39;, &#39;type,-size,-lastModifiedTime&#39;). Prefix with &#39;-&#39; for descending. | 

### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

