# \ProjectsAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateProject**](ProjectsAPI.md#V3CreateProject) | **Post** /v3/projects | Create a project
[**V3CreateProjectKey**](ProjectsAPI.md#V3CreateProjectKey) | **Post** /v3/projects/{projectId}/keys | Add a project key
[**V3DeleteProject**](ProjectsAPI.md#V3DeleteProject) | **Delete** /v3/projects/{projectId} | Delete a project
[**V3DeleteProjectKey**](ProjectsAPI.md#V3DeleteProjectKey) | **Delete** /v3/projects/{projectId}/keys/{keyId} | Delete a project key
[**V3FetchProjectFirmwareAssets**](ProjectsAPI.md#V3FetchProjectFirmwareAssets) | **Post** /v3/projects/{projectId}/firmware-assets | Fetch firmware assets for a project
[**V3GetProject**](ProjectsAPI.md#V3GetProject) | **Get** /v3/projects/{projectId} | Get a project
[**V3GetProjectImageUpload**](ProjectsAPI.md#V3GetProjectImageUpload) | **Get** /v3/projects/{projectId}/image-upload/{type}/{imageId}/{name} | Get image upload status
[**V3GetProjectNetworkLog**](ProjectsAPI.md#V3GetProjectNetworkLog) | **Get** /v3/projects/{projectId}/network/log | Get project network log
[**V3GetProjectNetworkStatus**](ProjectsAPI.md#V3GetProjectNetworkStatus) | **Get** /v3/projects/{projectId}/network/status | Get project network status
[**V3GetProjectVpnConfig**](ProjectsAPI.md#V3GetProjectVpnConfig) | **Get** /v3/projects/{projectId}/vpnconfig/{format} | Get project VPN configuration
[**V3ListProjectInstances**](ProjectsAPI.md#V3ListProjectInstances) | **Get** /v3/projects/{projectId}/instances | List project instances
[**V3ListProjectKeys**](ProjectsAPI.md#V3ListProjectKeys) | **Get** /v3/projects/{projectId}/keys | List project keys
[**V3ListProjects**](ProjectsAPI.md#V3ListProjects) | **Get** /v3/projects | List projects
[**V3PatchProject**](ProjectsAPI.md#V3PatchProject) | **Patch** /v3/projects/{projectId} | Update a project
[**V3PreauthVpnConfig**](ProjectsAPI.md#V3PreauthVpnConfig) | **Post** /v3/projects/{projectId}/preauth-vpn-config/{filename} | Pre-authorize a VPN configuration download
[**V3PutProjectImageUpload**](ProjectsAPI.md#V3PutProjectImageUpload) | **Put** /v3/projects/{projectId}/image-upload/{type}/{imageId}/{name} | Upload image chunk



## V3CreateProject

> Project V3CreateProject(ctx).CreateProjectBody(createProjectBody).Execute()

Create a project



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
	createProjectBody := *openapiclient.NewCreateProjectBody("Default Project") // CreateProjectBody | Project to create.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3CreateProject(context.Background()).CreateProjectBody(createProjectBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3CreateProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateProject`: Project
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3CreateProject`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createProjectBody** | [**CreateProjectBody**](CreateProjectBody.md) | Project to create. | 

### Return type

[**Project**](Project.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3CreateProjectKey

> ProjectKey V3CreateProjectKey(ctx, projectId).CreateProjectKeyBody(createProjectKeyBody).Execute()

Add a project key



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	createProjectKeyBody := *openapiclient.NewCreateProjectKeyBody("Kind_example", "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIJUlGdieyRXdiVIyQjqthDE1YzmwzH0ZeZuHkBuC9Gwr user@example.com") // CreateProjectKeyBody | Key to add.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3CreateProjectKey(context.Background(), projectId).CreateProjectKeyBody(createProjectKeyBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3CreateProjectKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateProjectKey`: ProjectKey
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3CreateProjectKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateProjectKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createProjectKeyBody** | [**CreateProjectKeyBody**](CreateProjectKeyBody.md) | Key to add. | 

### Return type

[**ProjectKey**](ProjectKey.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteProject

> V3DeleteProject(ctx, projectId).Execute()

Delete a project



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProjectsAPI.V3DeleteProject(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3DeleteProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteProjectRequest struct via the builder pattern


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


## V3DeleteProjectKey

> V3DeleteProjectKey(ctx, projectId, keyId).Execute()

Delete a project key



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	keyId := "9c1098dc-e881-41fb-b3af-e2d5ddd55d86" // string | Project key identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProjectsAPI.V3DeleteProjectKey(context.Background(), projectId, keyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3DeleteProjectKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 
**keyId** | **string** | Project key identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteProjectKeyRequest struct via the builder pattern


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


## V3FetchProjectFirmwareAssets

> FetchFirmwareAssetsResponse V3FetchProjectFirmwareAssets(ctx, projectId).FetchFirmwareAssetsBody(fetchFirmwareAssetsBody).Execute()

Fetch firmware assets for a project



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	fetchFirmwareAssetsBody := *openapiclient.NewFetchFirmwareAssetsBody([]string{"AssetUrls_example"}) // FetchFirmwareAssetsBody | Firmware asset URLs to fetch.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3FetchProjectFirmwareAssets(context.Background(), projectId).FetchFirmwareAssetsBody(fetchFirmwareAssetsBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3FetchProjectFirmwareAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3FetchProjectFirmwareAssets`: FetchFirmwareAssetsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3FetchProjectFirmwareAssets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3FetchProjectFirmwareAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **fetchFirmwareAssetsBody** | [**FetchFirmwareAssetsBody**](FetchFirmwareAssetsBody.md) | Firmware asset URLs to fetch. | 

### Return type

[**FetchFirmwareAssetsResponse**](FetchFirmwareAssetsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetProject

> Project V3GetProject(ctx, projectId).Execute()

Get a project



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3GetProject(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3GetProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetProject`: Project
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3GetProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Project**](Project.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetProjectImageUpload

> *os.File V3GetProjectImageUpload(ctx, projectId, type_, imageId, name).ResumableChunkNumber(resumableChunkNumber).Execute()

Get image upload status



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	type_ := "type__example" // string | What kind of file this is, for example `fw` for firmware or `kernel`. Uses the same values as `type` on `POST /v3/images`; see `ImageType` for what each means. Types that need a license feature your license lacks are rejected with 403.
	imageId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload.
	name := "name_example" // string | The file name to store, URL-encoded (for example `my%20firmware.ipsw`). Becomes the image `name`.
	resumableChunkNumber := float32(56) // float32 | Chunk number. When present the response reports whether that chunk was already stored (200) or still needs to be uploaded (204) instead of returning the image file. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3GetProjectImageUpload(context.Background(), projectId, type_, imageId, name).ResumableChunkNumber(resumableChunkNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3GetProjectImageUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetProjectImageUpload`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3GetProjectImageUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 
**type_** | **string** | What kind of file this is, for example &#x60;fw&#x60; for firmware or &#x60;kernel&#x60;. Uses the same values as &#x60;type&#x60; on &#x60;POST /v3/images&#x60;; see &#x60;ImageType&#x60; for what each means. Types that need a license feature your license lacks are rejected with 403. | 
**imageId** | **string** | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload. | 
**name** | **string** | The file name to store, URL-encoded (for example &#x60;my%20firmware.ipsw&#x60;). Becomes the image &#x60;name&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetProjectImageUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **resumableChunkNumber** | **float32** | Chunk number. When present the response reports whether that chunk was already stored (200) or still needs to be uploaded (204) instead of returning the image file. | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetProjectNetworkLog

> string V3GetProjectNetworkLog(ctx, projectId).Execute()

Get project network log



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3GetProjectNetworkLog(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3GetProjectNetworkLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetProjectNetworkLog`: string
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3GetProjectNetworkLog`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetProjectNetworkLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetProjectNetworkStatus

> NetworkStatus V3GetProjectNetworkStatus(ctx, projectId).Execute()

Get project network status



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3GetProjectNetworkStatus(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3GetProjectNetworkStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetProjectNetworkStatus`: NetworkStatus
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3GetProjectNetworkStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetProjectNetworkStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NetworkStatus**](NetworkStatus.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetProjectVpnConfig

> string V3GetProjectVpnConfig(ctx, projectId, format).Execute()

Get project VPN configuration



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	format := "ovpn" // string | VPN configuration format: 'ovpn' for an OpenVPN profile; any other value returns a Tunnelblick zip.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3GetProjectVpnConfig(context.Background(), projectId, format).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3GetProjectVpnConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetProjectVpnConfig`: string
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3GetProjectVpnConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 
**format** | **string** | VPN configuration format: &#39;ovpn&#39; for an OpenVPN profile; any other value returns a Tunnelblick zip. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetProjectVpnConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/x-openvpn-profile, application/zip, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListProjectInstances

> ProjectInstanceList V3ListProjectInstances(ctx, projectId).Limit(limit).Offset(offset).Name(name).Execute()

List project instances



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)
	name := "My Device" // string | Filter by exact instance name. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3ListProjectInstances(context.Background(), projectId).Limit(limit).Offset(offset).Name(name).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3ListProjectInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListProjectInstances`: ProjectInstanceList
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3ListProjectInstances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListProjectInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]
 **name** | **string** | Filter by exact instance name. | 

### Return type

[**ProjectInstanceList**](ProjectInstanceList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListProjectKeys

> ProjectKeyList V3ListProjectKeys(ctx, projectId).Limit(limit).Offset(offset).Execute()

List project keys



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3ListProjectKeys(context.Background(), projectId).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3ListProjectKeys``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListProjectKeys`: ProjectKeyList
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3ListProjectKeys`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListProjectKeysRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**ProjectKeyList**](ProjectKeyList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListProjects

> ProjectList V3ListProjects(ctx).Limit(limit).Offset(offset).Name(name).Execute()

List projects



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
	name := "Default Project" // string | Filter by exact project name (case-insensitive). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3ListProjects(context.Background()).Limit(limit).Offset(offset).Name(name).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3ListProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListProjects`: ProjectList
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3ListProjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]
 **name** | **string** | Filter by exact project name (case-insensitive). | 

### Return type

[**ProjectList**](ProjectList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchProject

> Project V3PatchProject(ctx, projectId).PatchProjectBody(patchProjectBody).Execute()

Update a project



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	patchProjectBody := *openapiclient.NewPatchProjectBody() // PatchProjectBody | Fields to update.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3PatchProject(context.Background(), projectId).PatchProjectBody(patchProjectBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3PatchProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PatchProject`: Project
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3PatchProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchProjectBody** | [**PatchProjectBody**](PatchProjectBody.md) | Fields to update. | 

### Return type

[**Project**](Project.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PreauthVpnConfig

> VpnConfigPreauthorization V3PreauthVpnConfig(ctx, projectId, filename).Execute()

Pre-authorize a VPN configuration download



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	filename := "researcher-laptop.ovpn" // string | VPN configuration filename, as '<clientId>.<format>'. The client identifier becomes the common name of the issued client certificate; a format of 'ovpn' yields an OpenVPN profile and any other value yields a Tunnelblick zip.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3PreauthVpnConfig(context.Background(), projectId, filename).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3PreauthVpnConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PreauthVpnConfig`: VpnConfigPreauthorization
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3PreauthVpnConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 
**filename** | **string** | VPN configuration filename, as &#39;&lt;clientId&gt;.&lt;format&gt;&#39;. The client identifier becomes the common name of the issued client certificate; a format of &#39;ovpn&#39; yields an OpenVPN profile and any other value yields a Tunnelblick zip. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PreauthVpnConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**VpnConfigPreauthorization**](VpnConfigPreauthorization.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PutProjectImageUpload

> map[string]interface{} V3PutProjectImageUpload(ctx, projectId, type_, imageId, name).Body(body).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).ResumableTotalSize(resumableTotalSize).ResumableTotalChunks(resumableTotalChunks).CorelliumChecksum(corelliumChecksum).Flavor(flavor).XCorelliumImageEncoding(xCorelliumImageEncoding).XCorelliumImageEncapsulated(xCorelliumImageEncapsulated).XCorelliumTotalFileSize(xCorelliumTotalFileSize).XCorelliumImagePassword(xCorelliumImagePassword).Execute()

Upload image chunk



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | ID of the project. Get it from `v3ListProjects`, or from the `id` returned when the project was created.
	type_ := "type__example" // string | What kind of file this is, for example `fw` for firmware or `kernel`. Uses the same values as `type` on `POST /v3/images`; see `ImageType` for what each means. Types that need a license feature your license lacks are rejected with 403.
	imageId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload.
	name := "name_example" // string | The file name to store, URL-encoded (for example `my%20firmware.ipsw`). Becomes the image `name`.
	body := os.NewFile(1234, "some_file") // *os.File | 
	resumableChunkNumber := float32(56) // float32 | Which chunk this is, counting from 1. (optional)
	resumableChunkSize := float32(56) // float32 | The size, in bytes, you split the file into. Use the same value for every chunk; only the last chunk may be smaller. If you send `corelliumChecksum`, this must equal the block size inside it. (optional)
	resumableCurrentChunkSize := float32(56) // float32 | Actual size in bytes of this chunk's body. (optional)
	resumableTotalSize := float32(56) // float32 | Size of the whole file in bytes. (optional)
	resumableTotalChunks := float32(56) // float32 | How many chunks the whole file is split into. The upload completes when the last one arrives. (optional)
	corelliumChecksum := "corelliumChecksum_example" // string | Optional expected checksum of the whole file, formatted `algorithm$blockSize$hash`. When given, the finished upload is checked and rejected (and the image removed) if it does not match. Required for firmware (`fw`) uploads on air-gapped deployments. (optional)
	flavor := "flavor_example" // string | Device model (`flavor` from `GET /v3/models`) the image is for. Needed for `partition` uploads when the image is not attached to a device, so the partition name can be checked against that model. (optional)
	xCorelliumImageEncoding := "xCorelliumImageEncoding_example" // string | How the file is stored: `plain` (normal) or `encrypted`. Only read on the first chunk, when the image record is created; later chunks cannot change it. (optional)
	xCorelliumImageEncapsulated := true // bool | Whether the uploaded file is a ZIP wrapper the platform should unpack. Send false to store the file exactly as uploaded. Only read on the first chunk, when the image record is created. (optional)
	xCorelliumTotalFileSize := float32(56) // float32 | Size of the whole file in bytes. Send it on every chunk: the platform uses it to check up front that there is room for the entire file, and answers 507 if there is not, before storing any data. (optional)
	xCorelliumImagePassword := "xCorelliumImagePassword_example" // string | Password of a password-protected file (for example encrypted firmware), used to check the file after upload. Leave out for normal files. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.V3PutProjectImageUpload(context.Background(), projectId, type_, imageId, name).Body(body).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).ResumableTotalSize(resumableTotalSize).ResumableTotalChunks(resumableTotalChunks).CorelliumChecksum(corelliumChecksum).Flavor(flavor).XCorelliumImageEncoding(xCorelliumImageEncoding).XCorelliumImageEncapsulated(xCorelliumImageEncapsulated).XCorelliumTotalFileSize(xCorelliumTotalFileSize).XCorelliumImagePassword(xCorelliumImagePassword).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.V3PutProjectImageUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PutProjectImageUpload`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.V3PutProjectImageUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | ID of the project. Get it from &#x60;v3ListProjects&#x60;, or from the &#x60;id&#x60; returned when the project was created. | 
**type_** | **string** | What kind of file this is, for example &#x60;fw&#x60; for firmware or &#x60;kernel&#x60;. Uses the same values as &#x60;type&#x60; on &#x60;POST /v3/images&#x60;; see &#x60;ImageType&#x60; for what each means. Types that need a license feature your license lacks are rejected with 403. | 
**imageId** | **string** | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload. | 
**name** | **string** | The file name to store, URL-encoded (for example &#x60;my%20firmware.ipsw&#x60;). Becomes the image &#x60;name&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PutProjectImageUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **body** | ***os.File** |  | 
 **resumableChunkNumber** | **float32** | Which chunk this is, counting from 1. | 
 **resumableChunkSize** | **float32** | The size, in bytes, you split the file into. Use the same value for every chunk; only the last chunk may be smaller. If you send &#x60;corelliumChecksum&#x60;, this must equal the block size inside it. | 
 **resumableCurrentChunkSize** | **float32** | Actual size in bytes of this chunk&#39;s body. | 
 **resumableTotalSize** | **float32** | Size of the whole file in bytes. | 
 **resumableTotalChunks** | **float32** | How many chunks the whole file is split into. The upload completes when the last one arrives. | 
 **corelliumChecksum** | **string** | Optional expected checksum of the whole file, formatted &#x60;algorithm$blockSize$hash&#x60;. When given, the finished upload is checked and rejected (and the image removed) if it does not match. Required for firmware (&#x60;fw&#x60;) uploads on air-gapped deployments. | 
 **flavor** | **string** | Device model (&#x60;flavor&#x60; from &#x60;GET /v3/models&#x60;) the image is for. Needed for &#x60;partition&#x60; uploads when the image is not attached to a device, so the partition name can be checked against that model. | 
 **xCorelliumImageEncoding** | **string** | How the file is stored: &#x60;plain&#x60; (normal) or &#x60;encrypted&#x60;. Only read on the first chunk, when the image record is created; later chunks cannot change it. | 
 **xCorelliumImageEncapsulated** | **bool** | Whether the uploaded file is a ZIP wrapper the platform should unpack. Send false to store the file exactly as uploaded. Only read on the first chunk, when the image record is created. | 
 **xCorelliumTotalFileSize** | **float32** | Size of the whole file in bytes. Send it on every chunk: the platform uses it to check up front that there is room for the entire file, and answers 507 if there is not, before storing any data. | 
 **xCorelliumImagePassword** | **string** | Password of a password-protected file (for example encrypted firmware), used to check the file after upload. Leave out for normal files. | 

### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

