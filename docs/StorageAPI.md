# \StorageAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3AttachClusterStorage**](StorageAPI.md#V3AttachClusterStorage) | **Post** /v3/cluster/storage/{id}/attach | Attach storage device
[**V3EjectClusterStorage**](StorageAPI.md#V3EjectClusterStorage) | **Post** /v3/cluster/storage/{id}/eject | Eject storage device
[**V3ListClusterStorage**](StorageAPI.md#V3ListClusterStorage) | **Get** /v3/cluster/storage | List cluster storage devices
[**V3ListStorage**](StorageAPI.md#V3ListStorage) | **Get** /v3/storage | List server-attached storage devices
[**V3ListStorageFiles**](StorageAPI.md#V3ListStorageFiles) | **Get** /v3/storage/{id}/files/{path} | List storage files



## V3AttachClusterStorage

> StorageAlreadyMountedResponse V3AttachClusterStorage(ctx, id).Execute()

Attach storage device



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
	id := "73357171-23a0-4a3e-8661-216dbfbdd7ab" // string | Storage device identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageAPI.V3AttachClusterStorage(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageAPI.V3AttachClusterStorage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3AttachClusterStorage`: StorageAlreadyMountedResponse
	fmt.Fprintf(os.Stdout, "Response from `StorageAPI.V3AttachClusterStorage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Storage device identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3AttachClusterStorageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StorageAlreadyMountedResponse**](StorageAlreadyMountedResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3EjectClusterStorage

> StorageEjectAlreadyUnmountedResponse V3EjectClusterStorage(ctx, id).Execute()

Eject storage device



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
	id := "73357171-23a0-4a3e-8661-216dbfbdd7ab" // string | Storage device identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageAPI.V3EjectClusterStorage(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageAPI.V3EjectClusterStorage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3EjectClusterStorage`: StorageEjectAlreadyUnmountedResponse
	fmt.Fprintf(os.Stdout, "Response from `StorageAPI.V3EjectClusterStorage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Storage device identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3EjectClusterStorageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StorageEjectAlreadyUnmountedResponse**](StorageEjectAlreadyUnmountedResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListClusterStorage

> StorageDeviceList V3ListClusterStorage(ctx).Limit(limit).Offset(offset).Id(id).Device(device).FsType(fsType).FsUuid(fsUuid).Label(label).Serial(serial).Vendor(vendor).Model(model).MountPolicy(mountPolicy).Status(status).Sort(sort).Execute()

List cluster storage devices



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
	limit := float32(100) // float32 | Maximum results to return. (optional) (default to 100)
	offset := float32(0) // float32 | Results to skip. (optional) (default to 0)
	id := "73357171-23a0-4a3e-8661-216dbfbdd7ab" // string | Filter by identifier (comma-separated for multiple). (optional)
	device := "sdb1" // string | Filter by device name (partial match). (optional)
	fsType := "ext4" // string | Filter by filesystem type (comma-separated). (optional)
	fsUuid := "4a3f2e1d" // string | Filter by filesystem UUID (partial match). (optional)
	label := "EXTERNAL" // string | Filter by label (partial match). (optional)
	serial := "0123456789" // string | Filter by serial number (partial match). (optional)
	vendor := "SanDisk" // string | Filter by vendor (partial match). (optional)
	model := "Ultra" // string | Filter by model (partial match). (optional)
	mountPolicy := "mountPolicy_example" // string | Filter by mount policy. (optional)
	status := "status_example" // string | Filter by mount status. (optional)
	sort := "-device" // string | Sort order (e.g. 'device' or '-device'). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageAPI.V3ListClusterStorage(context.Background()).Limit(limit).Offset(offset).Id(id).Device(device).FsType(fsType).FsUuid(fsUuid).Label(label).Serial(serial).Vendor(vendor).Model(model).MountPolicy(mountPolicy).Status(status).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageAPI.V3ListClusterStorage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListClusterStorage`: StorageDeviceList
	fmt.Fprintf(os.Stdout, "Response from `StorageAPI.V3ListClusterStorage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListClusterStorageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Maximum results to return. | [default to 100]
 **offset** | **float32** | Results to skip. | [default to 0]
 **id** | **string** | Filter by identifier (comma-separated for multiple). | 
 **device** | **string** | Filter by device name (partial match). | 
 **fsType** | **string** | Filter by filesystem type (comma-separated). | 
 **fsUuid** | **string** | Filter by filesystem UUID (partial match). | 
 **label** | **string** | Filter by label (partial match). | 
 **serial** | **string** | Filter by serial number (partial match). | 
 **vendor** | **string** | Filter by vendor (partial match). | 
 **model** | **string** | Filter by model (partial match). | 
 **mountPolicy** | **string** | Filter by mount policy. | 
 **status** | **string** | Filter by mount status. | 
 **sort** | **string** | Sort order (e.g. &#39;device&#39; or &#39;-device&#39;). | 

### Return type

[**StorageDeviceList**](StorageDeviceList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListStorage

> StorageList V3ListStorage(ctx).Limit(limit).Offset(offset).Sort(sort).Identifier(identifier).Device(device).FsType(fsType).MountPolicy(mountPolicy).Status(status).Execute()

List server-attached storage devices



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
	sort := "-createdAt" // string | Sort order (prefix a field with \"-\" for descending). (optional)
	identifier := "73357171-23a0-4a3e-8661-216dbfbdd7ab,9f2b6c04-58ad-4d61-b0e7-1ac9d8e07f35" // string | Filter by identifier (comma separated). (optional)
	device := "sdb" // string | Filter by device name (partial match). (optional)
	fsType := "ext4,exfat" // string | Filter by filesystem type (comma separated). (optional)
	mountPolicy := "mountPolicy_example" // string | Filter by mount policy. (optional)
	status := "status_example" // string | Filter by mount status. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageAPI.V3ListStorage(context.Background()).Limit(limit).Offset(offset).Sort(sort).Identifier(identifier).Device(device).FsType(fsType).MountPolicy(mountPolicy).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageAPI.V3ListStorage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListStorage`: StorageList
	fmt.Fprintf(os.Stdout, "Response from `StorageAPI.V3ListStorage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListStorageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]
 **sort** | **string** | Sort order (prefix a field with \&quot;-\&quot; for descending). | 
 **identifier** | **string** | Filter by identifier (comma separated). | 
 **device** | **string** | Filter by device name (partial match). | 
 **fsType** | **string** | Filter by filesystem type (comma separated). | 
 **mountPolicy** | **string** | Filter by mount policy. | 
 **status** | **string** | Filter by mount status. | 

### Return type

[**StorageList**](StorageList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListStorageFiles

> StorageFileList V3ListStorageFiles(ctx, id, path).Limit(limit).Offset(offset).Sort(sort).Name(name).Type_(type_).Execute()

List storage files



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
	id := "73357171-23a0-4a3e-8661-216dbfbdd7ab" // string | Storage device identifier.
	path := "/var/mobile/Media" // string | Folder to list, relative to the top of the storage device. Slashes are kept as path separators.
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)
	sort := "-lastModifiedTime" // string | Sort order (prefix a field with \"-\" for descending). (optional)
	name := "firmware.ipsw,boot.img" // string | Filter by name (case-insensitive exact match, comma separated). (optional)
	type_ := "file" // string | Filter by type (case-insensitive partial match, e.g. \"file\" or \"dir\"). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageAPI.V3ListStorageFiles(context.Background(), id, path).Limit(limit).Offset(offset).Sort(sort).Name(name).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageAPI.V3ListStorageFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListStorageFiles`: StorageFileList
	fmt.Fprintf(os.Stdout, "Response from `StorageAPI.V3ListStorageFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Storage device identifier. | 
**path** | **string** | Folder to list, relative to the top of the storage device. Slashes are kept as path separators. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListStorageFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]
 **sort** | **string** | Sort order (prefix a field with \&quot;-\&quot; for descending). | 
 **name** | **string** | Filter by name (case-insensitive exact match, comma separated). | 
 **type_** | **string** | Filter by type (case-insensitive partial match, e.g. \&quot;file\&quot; or \&quot;dir\&quot;). | 

### Return type

[**StorageFileList**](StorageFileList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

