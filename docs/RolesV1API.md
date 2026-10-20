# \RolesV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1AddTeamRoleToProject**](RolesV1API.md#V1AddTeamRoleToProject) | **Put** /v1/roles/projects/{projectId}/teams/{teamId}/roles/{roleId} | Add team role to project
[**V1AddUserRoleToProject**](RolesV1API.md#V1AddUserRoleToProject) | **Put** /v1/roles/projects/{projectId}/users/{userId}/roles/{roleId} | Add user role to project
[**V1RemoveTeamRoleFromProject**](RolesV1API.md#V1RemoveTeamRoleFromProject) | **Delete** /v1/roles/projects/{projectId}/teams/{teamId}/roles/{roleId} | Remove team role from project
[**V1RemoveUserRoleFromProject**](RolesV1API.md#V1RemoveUserRoleFromProject) | **Delete** /v1/roles/projects/{projectId}/users/{userId}/roles/{roleId} | Remove user role from project
[**V1Roles**](RolesV1API.md#V1Roles) | **Get** /v1/roles | Get all roles



## V1AddTeamRoleToProject

> V1AddTeamRoleToProject(ctx, projectId, teamId, roleId).Execute()

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
	projectId := "projectId_example" // string | Project ID - uuid
	teamId := "teamId_example" // string | Team ID - uuid
	roleId := "roleId_example" // string | Role ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesV1API.V1AddTeamRoleToProject(context.Background(), projectId, teamId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesV1API.V1AddTeamRoleToProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 
**teamId** | **string** | Team ID - uuid | 
**roleId** | **string** | Role ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AddTeamRoleToProjectRequest struct via the builder pattern


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


## V1AddUserRoleToProject

> V1AddUserRoleToProject(ctx, projectId, userId, roleId).Execute()

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
	projectId := "projectId_example" // string | Project ID - uuid
	userId := "userId_example" // string | User ID - uuid
	roleId := "roleId_example" // string | Role ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesV1API.V1AddUserRoleToProject(context.Background(), projectId, userId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesV1API.V1AddUserRoleToProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 
**userId** | **string** | User ID - uuid | 
**roleId** | **string** | Role ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AddUserRoleToProjectRequest struct via the builder pattern


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


## V1RemoveTeamRoleFromProject

> V1RemoveTeamRoleFromProject(ctx, projectId, teamId, roleId).Execute()

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
	projectId := "projectId_example" // string | Project ID - uuid
	teamId := "teamId_example" // string | Team ID - uuid
	roleId := "roleId_example" // string | Role ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesV1API.V1RemoveTeamRoleFromProject(context.Background(), projectId, teamId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesV1API.V1RemoveTeamRoleFromProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 
**teamId** | **string** | Team ID - uuid | 
**roleId** | **string** | Role ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1RemoveTeamRoleFromProjectRequest struct via the builder pattern


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


## V1RemoveUserRoleFromProject

> V1RemoveUserRoleFromProject(ctx, projectId, userId, roleId).Execute()

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
	projectId := "projectId_example" // string | Project ID - uuid
	userId := "userId_example" // string | User ID - uuid
	roleId := "roleId_example" // string | Role ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RolesV1API.V1RemoveUserRoleFromProject(context.Background(), projectId, userId, roleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesV1API.V1RemoveUserRoleFromProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Project ID - uuid | 
**userId** | **string** | User ID - uuid | 
**roleId** | **string** | Role ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1RemoveUserRoleFromProjectRequest struct via the builder pattern


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


## V1Roles

> []RoleV1 V1Roles(ctx).Execute()

Get all roles



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
	resp, r, err := apiClient.RolesV1API.V1Roles(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RolesV1API.V1Roles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1Roles`: []RoleV1
	fmt.Fprintf(os.Stdout, "Response from `RolesV1API.V1Roles`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1RolesRequest struct via the builder pattern


### Return type

[**[]RoleV1**](RoleV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

