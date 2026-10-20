# \ProjectsV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1AddProjectKey**](ProjectsV1API.md#V1AddProjectKey) | **Post** /v1/projects/{projectId}/keys | Add Project Authorized Key
[**V1CreateProject**](ProjectsV1API.md#V1CreateProject) | **Post** /v1/projects | Create a Project
[**V1DeleteProject**](ProjectsV1API.md#V1DeleteProject) | **Delete** /v1/projects/{projectId} | Delete a Project
[**V1GetProject**](ProjectsV1API.md#V1GetProject) | **Get** /v1/projects/{projectId} | Get a Project
[**V1GetProjectInstances**](ProjectsV1API.md#V1GetProjectInstances) | **Get** /v1/projects/{projectId}/instances | Get Instances in Project
[**V1GetProjectKeys**](ProjectsV1API.md#V1GetProjectKeys) | **Get** /v1/projects/{projectId}/keys | Get Project Authorized Keys
[**V1GetProjectNetworkLog**](ProjectsV1API.md#V1GetProjectNetworkLog) | **Get** /v1/projects/{projectId}/network/log | Retrieve the network connection log for a project
[**V1GetProjectNetworkStatus**](ProjectsV1API.md#V1GetProjectNetworkStatus) | **Get** /v1/projects/{projectId}/network/status | Retrieve the network connection status for a project
[**V1GetProjectVpnConfig**](ProjectsV1API.md#V1GetProjectVpnConfig) | **Get** /v1/projects/{projectId}/vpnconfig/{format} | Get Project VPN Configuration
[**V1GetProjects**](ProjectsV1API.md#V1GetProjects) | **Get** /v1/projects | Get Projects
[**V1RemoveProjectKey**](ProjectsV1API.md#V1RemoveProjectKey) | **Delete** /v1/projects/{projectId}/keys/{keyId} | Delete Project Authorized Key
[**V1UpdateProject**](ProjectsV1API.md#V1UpdateProject) | **Patch** /v1/projects/{projectId} | Update a Project
[**V1UpdateProjectSettings**](ProjectsV1API.md#V1UpdateProjectSettings) | **Patch** /v1/projects/{projectId}/settings | Change Project Settings



## V1AddProjectKey

> ProjectKeyV1 V1AddProjectKey(ctx, projectId).ProjectKeyV1(projectKeyV1).Execute()

Add Project Authorized Key

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
	projectId := "projectId_example" // string | Project ID - uuid
	projectKeyV1 := *openapiclient.NewProjectKeyV1("Kind_example", "Key_example") // ProjectKeyV1 | Key to add

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1AddProjectKey(context.Background(), projectId).ProjectKeyV1(projectKeyV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1AddProjectKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AddProjectKey`: ProjectKeyV1
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1AddProjectKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AddProjectKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectKeyV1** | [**ProjectKeyV1**](ProjectKeyV1.md) | Key to add | 

### Return type

[**ProjectKeyV1**](ProjectKeyV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1CreateProject

> ProjectV1 V1CreateProject(ctx).ProjectV1(projectV1).Execute()

Create a Project

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
	projectV1 := *openapiclient.NewProjectV1("Id_example") // ProjectV1 | Project

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1CreateProject(context.Background()).ProjectV1(projectV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1CreateProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateProject`: ProjectV1
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1CreateProject`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectV1** | [**ProjectV1**](ProjectV1.md) | Project | 

### Return type

[**ProjectV1**](ProjectV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteProject

> V1DeleteProject(ctx, projectId).Execute()

Delete a Project

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
	projectId := "projectId_example" // string | Project ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProjectsV1API.V1DeleteProject(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1DeleteProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteProjectRequest struct via the builder pattern


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


## V1GetProject

> ProjectWithKeysV1 V1GetProject(ctx, projectId).Execute()

Get a Project

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
	projectId := "projectId_example" // string | Project ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1GetProject(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1GetProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetProject`: ProjectWithKeysV1
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1GetProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProjectWithKeysV1**](ProjectWithKeysV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetProjectInstances

> []InstanceV1 V1GetProjectInstances(ctx, projectId).Name(name).ReturnAttr(returnAttr).Execute()

Get Instances in Project

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
	projectId := "projectId_example" // string | Project ID - uuid
	name := "name_example" // string | Filter by project name (optional)
	returnAttr := []string{"Inner_example"} // []string | Attributes to include in instance return (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1GetProjectInstances(context.Background(), projectId).Name(name).ReturnAttr(returnAttr).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1GetProjectInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetProjectInstances`: []InstanceV1
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1GetProjectInstances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetProjectInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **name** | **string** | Filter by project name | 
 **returnAttr** | **[]string** | Attributes to include in instance return | 

### Return type

[**[]InstanceV1**](InstanceV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetProjectKeys

> []ProjectKeyV1 V1GetProjectKeys(ctx, projectId).Execute()

Get Project Authorized Keys

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
	projectId := "projectId_example" // string | Project ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1GetProjectKeys(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1GetProjectKeys``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetProjectKeys`: []ProjectKeyV1
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1GetProjectKeys`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetProjectKeysRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]ProjectKeyV1**](ProjectKeyV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetProjectNetworkLog

> string V1GetProjectNetworkLog(ctx, projectId).Execute()

Retrieve the network connection log for a project

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
	projectId := "projectId_example" // string | Project ID (must be a valid UUID)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1GetProjectNetworkLog(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1GetProjectNetworkLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetProjectNetworkLog`: string
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1GetProjectNetworkLog`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID (must be a valid UUID) | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetProjectNetworkLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetProjectNetworkStatus

> NetworkStatusResponse V1GetProjectNetworkStatus(ctx, projectId).Execute()

Retrieve the network connection status for a project

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
	projectId := "projectId_example" // string | Project ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1GetProjectNetworkStatus(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1GetProjectNetworkStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetProjectNetworkStatus`: NetworkStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1GetProjectNetworkStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetProjectNetworkStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NetworkStatusResponse**](NetworkStatusResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetProjectVpnConfig

> string V1GetProjectVpnConfig(ctx, projectId, format).Execute()

Get Project VPN Configuration



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
	projectId := "projectId_example" // string | Project ID - uuid
	format := "format_example" // string | VPN Config format

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1GetProjectVpnConfig(context.Background(), projectId, format).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1GetProjectVpnConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetProjectVpnConfig`: string
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1GetProjectVpnConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 
**format** | **string** | VPN Config format | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetProjectVpnConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetProjects

> []ProjectWithKeysV1 V1GetProjects(ctx).Name(name).IdsOnly(idsOnly).Execute()

Get Projects

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
	name := "name_example" // string | Filter by project name (optional)
	idsOnly := true // bool | Only include id of project in results (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1GetProjects(context.Background()).Name(name).IdsOnly(idsOnly).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1GetProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetProjects`: []ProjectWithKeysV1
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1GetProjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1GetProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Filter by project name | 
 **idsOnly** | **bool** | Only include id of project in results | 

### Return type

[**[]ProjectWithKeysV1**](ProjectWithKeysV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1RemoveProjectKey

> V1RemoveProjectKey(ctx, projectId, keyId).Execute()

Delete Project Authorized Key

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
	projectId := "projectId_example" // string | Project ID - uuid
	keyId := "keyId_example" // string | Key ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProjectsV1API.V1RemoveProjectKey(context.Background(), projectId, keyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1RemoveProjectKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 
**keyId** | **string** | Key ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1RemoveProjectKeyRequest struct via the builder pattern


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


## V1UpdateProject

> ProjectV1 V1UpdateProject(ctx, projectId).ProjectV1(projectV1).Execute()

Update a Project

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
	projectId := "projectId_example" // string | Project ID - uuid
	projectV1 := *openapiclient.NewProjectV1("Id_example") // ProjectV1 | Updated Project Settings

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsV1API.V1UpdateProject(context.Background(), projectId).ProjectV1(projectV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1UpdateProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UpdateProject`: ProjectV1
	fmt.Fprintf(os.Stdout, "Response from `ProjectsV1API.V1UpdateProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UpdateProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectV1** | [**ProjectV1**](ProjectV1.md) | Updated Project Settings | 

### Return type

[**ProjectV1**](ProjectV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UpdateProjectSettings

> V1UpdateProjectSettings(ctx, projectId).ProjectSettingsV1(projectSettingsV1).Execute()

Change Project Settings

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
	projectId := "projectId_example" // string | Project ID - uuid
	projectSettingsV1 := *openapiclient.NewProjectSettingsV1() // ProjectSettingsV1 | New settings

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProjectsV1API.V1UpdateProjectSettings(context.Background(), projectId).ProjectSettingsV1(projectSettingsV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsV1API.V1UpdateProjectSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UpdateProjectSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectSettingsV1** | [**ProjectSettingsV1**](ProjectSettingsV1.md) | New settings | 

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

