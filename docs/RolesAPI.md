# \RolesAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3AddTeamRoleToDeployment**](RolesAPI.md#V3AddTeamRoleToDeployment) | **Put** /v3/roles/deployments/{deploymentId}/teams/{teamId}/roles/{roleId} | Add team role to deployment
[**V3AddTeamRoleToProject**](RolesAPI.md#V3AddTeamRoleToProject) | **Put** /v3/roles/projects/{projectId}/teams/{teamId}/roles/{roleId} | Add team role to project
[**V3AddUserRoleToDeployment**](RolesAPI.md#V3AddUserRoleToDeployment) | **Put** /v3/roles/deployments/{deploymentId}/users/{userId}/roles/{roleId} | Add user role to deployment
[**V3AddUserRoleToProject**](RolesAPI.md#V3AddUserRoleToProject) | **Put** /v3/roles/projects/{projectId}/users/{userId}/roles/{roleId} | Add user role to project
[**V3ListDeploymentRoles**](RolesAPI.md#V3ListDeploymentRoles) | **Get** /v3/roles/deployments | List deployment role assignments
[**V3ListRoles**](RolesAPI.md#V3ListRoles) | **Get** /v3/roles | List all role assignments for the caller&#39;s domain
[**V3RemoveTeamRoleFromDeployment**](RolesAPI.md#V3RemoveTeamRoleFromDeployment) | **Delete** /v3/roles/deployments/{deploymentId}/teams/{teamId}/roles/{roleId} | Remove team role from deployment
[**V3RemoveTeamRoleFromProject**](RolesAPI.md#V3RemoveTeamRoleFromProject) | **Delete** /v3/roles/projects/{projectId}/teams/{teamId}/roles/{roleId} | Remove team role from project
[**V3RemoveUserRoleFromDeployment**](RolesAPI.md#V3RemoveUserRoleFromDeployment) | **Delete** /v3/roles/deployments/{deploymentId}/users/{userId}/roles/{roleId} | Remove user role from deployment
[**V3RemoveUserRoleFromProject**](RolesAPI.md#V3RemoveUserRoleFromProject) | **Delete** /v3/roles/projects/{projectId}/users/{userId}/roles/{roleId} | Remove user role from project



## V3AddTeamRoleToDeployment

> V3AddTeamRoleToDeployment(ctx, deploymentId, teamId, roleId).Execute()

Add team role to deployment



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
	deploymentId := "prod-us-east" // string | Deployment identifier.
	teamId := "089c8ffd-ca4d-4d35-80ab-0847d18b7213" // string | Team identifier.
	roleId := "admin" // string | Role identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesAPI.V3AddTeamRoleToDeployment(context.Background(), deploymentId, teamId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3AddTeamRoleToDeployment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deploymentId** | **string** | Deployment identifier. | 
**teamId** | **string** | Team identifier. | 
**roleId** | **string** | Role identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3AddTeamRoleToDeploymentRequest struct via the builder pattern


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


## V3AddTeamRoleToProject

> V3AddTeamRoleToProject(ctx, projectId, teamId, roleId).Execute()

Add team role to project



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | Project identifier.
	teamId := "089c8ffd-ca4d-4d35-80ab-0847d18b7213" // string | Team ID from `GET /v3/teams`, or `all-users` to grant the role to everyone in your domain at once.
	roleId := "admin" // string | Role to grant or remove: `admin` or `member`. See `RoleName`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesAPI.V3AddTeamRoleToProject(context.Background(), projectId, teamId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3AddTeamRoleToProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project identifier. | 
**teamId** | **string** | Team ID from &#x60;GET /v3/teams&#x60;, or &#x60;all-users&#x60; to grant the role to everyone in your domain at once. | 
**roleId** | **string** | Role to grant or remove: &#x60;admin&#x60; or &#x60;member&#x60;. See &#x60;RoleName&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3AddTeamRoleToProjectRequest struct via the builder pattern


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


## V3AddUserRoleToDeployment

> V3AddUserRoleToDeployment(ctx, deploymentId, userId, roleId).Execute()

Add user role to deployment



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
	deploymentId := "prod-us-east" // string | Deployment identifier.
	userId := "e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320" // string | User identifier.
	roleId := "admin" // string | Role identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesAPI.V3AddUserRoleToDeployment(context.Background(), deploymentId, userId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3AddUserRoleToDeployment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deploymentId** | **string** | Deployment identifier. | 
**userId** | **string** | User identifier. | 
**roleId** | **string** | Role identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3AddUserRoleToDeploymentRequest struct via the builder pattern


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


## V3AddUserRoleToProject

> V3AddUserRoleToProject(ctx, projectId, userId, roleId).Execute()

Add user role to project



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | Project identifier.
	userId := "e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320" // string | User identifier.
	roleId := "admin" // string | Role to grant or remove: `admin` or `member`. See `RoleName`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesAPI.V3AddUserRoleToProject(context.Background(), projectId, userId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3AddUserRoleToProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project identifier. | 
**userId** | **string** | User identifier. | 
**roleId** | **string** | Role to grant or remove: &#x60;admin&#x60; or &#x60;member&#x60;. See &#x60;RoleName&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3AddUserRoleToProjectRequest struct via the builder pattern


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


## V3ListDeploymentRoles

> RolesListResponse V3ListDeploymentRoles(ctx).Limit(limit).Offset(offset).Execute()

List deployment role assignments



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
	resp, r, err := apiClient.RolesAPI.V3ListDeploymentRoles(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3ListDeploymentRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListDeploymentRoles`: RolesListResponse
	fmt.Fprintf(os.Stdout, "Response from `RolesAPI.V3ListDeploymentRoles`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListDeploymentRolesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**RolesListResponse**](RolesListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListRoles

> RolesListResponse V3ListRoles(ctx).Limit(limit).Offset(offset).Execute()

List all role assignments for the caller's domain



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
	resp, r, err := apiClient.RolesAPI.V3ListRoles(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3ListRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListRoles`: RolesListResponse
	fmt.Fprintf(os.Stdout, "Response from `RolesAPI.V3ListRoles`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListRolesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**RolesListResponse**](RolesListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3RemoveTeamRoleFromDeployment

> V3RemoveTeamRoleFromDeployment(ctx, deploymentId, teamId, roleId).Execute()

Remove team role from deployment



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
	deploymentId := "prod-us-east" // string | Deployment identifier.
	teamId := "089c8ffd-ca4d-4d35-80ab-0847d18b7213" // string | Team identifier.
	roleId := "admin" // string | Role identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesAPI.V3RemoveTeamRoleFromDeployment(context.Background(), deploymentId, teamId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3RemoveTeamRoleFromDeployment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deploymentId** | **string** | Deployment identifier. | 
**teamId** | **string** | Team identifier. | 
**roleId** | **string** | Role identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RemoveTeamRoleFromDeploymentRequest struct via the builder pattern


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


## V3RemoveTeamRoleFromProject

> V3RemoveTeamRoleFromProject(ctx, projectId, teamId, roleId).Execute()

Remove team role from project



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | Project identifier.
	teamId := "089c8ffd-ca4d-4d35-80ab-0847d18b7213" // string | Team identifier.
	roleId := "admin" // string | Role to grant or remove: `admin` or `member`. See `RoleName`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesAPI.V3RemoveTeamRoleFromProject(context.Background(), projectId, teamId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3RemoveTeamRoleFromProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project identifier. | 
**teamId** | **string** | Team identifier. | 
**roleId** | **string** | Role to grant or remove: &#x60;admin&#x60; or &#x60;member&#x60;. See &#x60;RoleName&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RemoveTeamRoleFromProjectRequest struct via the builder pattern


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


## V3RemoveUserRoleFromDeployment

> V3RemoveUserRoleFromDeployment(ctx, deploymentId, userId, roleId).Execute()

Remove user role from deployment



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
	deploymentId := "prod-us-east" // string | Deployment identifier.
	userId := "e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320" // string | User identifier.
	roleId := "admin" // string | Role identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesAPI.V3RemoveUserRoleFromDeployment(context.Background(), deploymentId, userId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3RemoveUserRoleFromDeployment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deploymentId** | **string** | Deployment identifier. | 
**userId** | **string** | User identifier. | 
**roleId** | **string** | Role identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RemoveUserRoleFromDeploymentRequest struct via the builder pattern


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


## V3RemoveUserRoleFromProject

> V3RemoveUserRoleFromProject(ctx, projectId, userId, roleId).Execute()

Remove user role from project



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
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | Project identifier.
	userId := "e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320" // string | User identifier.
	roleId := "admin" // string | Role to grant or remove: `admin` or `member`. See `RoleName`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesAPI.V3RemoveUserRoleFromProject(context.Background(), projectId, userId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesAPI.V3RemoveUserRoleFromProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project identifier. | 
**userId** | **string** | User identifier. | 
**roleId** | **string** | Role to grant or remove: &#x60;admin&#x60; or &#x60;member&#x60;. See &#x60;RoleName&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RemoveUserRoleFromProjectRequest struct via the builder pattern


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

