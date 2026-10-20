# \TeamsAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3AddUserToTeam**](TeamsAPI.md#V3AddUserToTeam) | **Put** /v3/teams/{teamId}/users/{userId} | Add a user to a team
[**V3CreateTeam**](TeamsAPI.md#V3CreateTeam) | **Post** /v3/teams | Create a team
[**V3DeleteTeam**](TeamsAPI.md#V3DeleteTeam) | **Delete** /v3/teams/{teamId} | Delete a team
[**V3ListTeams**](TeamsAPI.md#V3ListTeams) | **Get** /v3/teams | List teams
[**V3RemoveUserFromTeam**](TeamsAPI.md#V3RemoveUserFromTeam) | **Delete** /v3/teams/{teamId}/users/{userId} | Remove a user from a team
[**V3UpdateTeam**](TeamsAPI.md#V3UpdateTeam) | **Patch** /v3/teams/{teamId} | Update a team



## V3AddUserToTeam

> V3AddUserToTeam(ctx, teamId, userId).Execute()

Add a user to a team



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
	teamId := "089c8ffd-ca4d-4d35-80ab-0847d18b7213" // string | Team identifier.
	userId := "e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320" // string | User identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TeamsAPI.V3AddUserToTeam(context.Background(), teamId, userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamsAPI.V3AddUserToTeam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **string** | Team identifier. | 
**userId** | **string** | User identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3AddUserToTeamRequest struct via the builder pattern


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


## V3CreateTeam

> TeamCreated V3CreateTeam(ctx).CreateTeamBody(createTeamBody).Execute()

Create a team



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
	createTeamBody := *openapiclient.NewCreateTeamBody("Mobile QA") // CreateTeamBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamsAPI.V3CreateTeam(context.Background()).CreateTeamBody(createTeamBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamsAPI.V3CreateTeam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateTeam`: TeamCreated
	fmt.Fprintf(os.Stdout, "Response from `TeamsAPI.V3CreateTeam`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateTeamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createTeamBody** | [**CreateTeamBody**](CreateTeamBody.md) |  | 

### Return type

[**TeamCreated**](TeamCreated.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteTeam

> V3DeleteTeam(ctx, teamId).Execute()

Delete a team



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
	teamId := "089c8ffd-ca4d-4d35-80ab-0847d18b7213" // string | Team identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TeamsAPI.V3DeleteTeam(context.Background(), teamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamsAPI.V3DeleteTeam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **string** | Team identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteTeamRequest struct via the builder pattern


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


## V3ListTeams

> TeamsListResponse V3ListTeams(ctx).Limit(limit).Offset(offset).Execute()

List teams



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
	resp, r, err := apiClient.TeamsAPI.V3ListTeams(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamsAPI.V3ListTeams``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListTeams`: TeamsListResponse
	fmt.Fprintf(os.Stdout, "Response from `TeamsAPI.V3ListTeams`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListTeamsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**TeamsListResponse**](TeamsListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3RemoveUserFromTeam

> V3RemoveUserFromTeam(ctx, teamId, userId).Execute()

Remove a user from a team



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
	teamId := "089c8ffd-ca4d-4d35-80ab-0847d18b7213" // string | Team identifier.
	userId := "e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320" // string | User identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TeamsAPI.V3RemoveUserFromTeam(context.Background(), teamId, userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamsAPI.V3RemoveUserFromTeam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **string** | Team identifier. | 
**userId** | **string** | User identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RemoveUserFromTeamRequest struct via the builder pattern


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


## V3UpdateTeam

> V3UpdateTeam(ctx, teamId).UpdateTeamBody(updateTeamBody).Execute()

Update a team



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
	teamId := "089c8ffd-ca4d-4d35-80ab-0847d18b7213" // string | Team identifier.
	updateTeamBody := *openapiclient.NewUpdateTeamBody() // UpdateTeamBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TeamsAPI.V3UpdateTeam(context.Background(), teamId).UpdateTeamBody(updateTeamBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamsAPI.V3UpdateTeam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**teamId** | **string** | Team identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UpdateTeamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateTeamBody** | [**UpdateTeamBody**](UpdateTeamBody.md) |  | 

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

