# \ActivityAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateActivityExport**](ActivityAPI.md#V3CreateActivityExport) | **Post** /v3/activity/export | Start activity export
[**V3DownloadActivity**](ActivityAPI.md#V3DownloadActivity) | **Get** /v3/activity/export/{taskId}/download | Download activity for a given task
[**V3GetActivityExportStatus**](ActivityAPI.md#V3GetActivityExportStatus) | **Get** /v3/activity/export/{taskId} | Get export task status
[**V3GetActivityExportTasks**](ActivityAPI.md#V3GetActivityExportTasks) | **Get** /v3/activity/export | Get all export tasks for user
[**V3ListActivities**](ActivityAPI.md#V3ListActivities) | **Get** /v3/activity | Get resource activities



## V3CreateActivityExport

> CreateActivityExportResponse V3CreateActivityExport(ctx).Accept(accept).CreateActivityExportBody(createActivityExportBody).Execute()

Start activity export



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
	accept := openapiclient.ActivityExportFormat("application/json") // ActivityExportFormat | Specifies the activity export file format.
	createActivityExportBody := *openapiclient.NewCreateActivityExportBody() // CreateActivityExportBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.V3CreateActivityExport(context.Background()).Accept(accept).CreateActivityExportBody(createActivityExportBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.V3CreateActivityExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateActivityExport`: CreateActivityExportResponse
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.V3CreateActivityExport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateActivityExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | [**ActivityExportFormat**](ActivityExportFormat.md) | Specifies the activity export file format. | 
 **createActivityExportBody** | [**CreateActivityExportBody**](CreateActivityExportBody.md) |  | 

### Return type

[**CreateActivityExportResponse**](CreateActivityExportResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DownloadActivity

> *os.File V3DownloadActivity(ctx, taskId).Execute()

Download activity for a given task



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
	taskId := "722cdce5-6f71-4f4a-b2b6-c00f11c015f6" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.V3DownloadActivity(context.Background(), taskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.V3DownloadActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3DownloadActivity`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.V3DownloadActivity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**taskId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DownloadActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[***os.File**](*os.File.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, text/csv

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetActivityExportStatus

> ActivityExportStatus V3GetActivityExportStatus(ctx, taskId).Execute()

Get export task status



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
	taskId := "722cdce5-6f71-4f4a-b2b6-c00f11c015f6" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.V3GetActivityExportStatus(context.Background(), taskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.V3GetActivityExportStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetActivityExportStatus`: ActivityExportStatus
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.V3GetActivityExportStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**taskId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetActivityExportStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ActivityExportStatus**](ActivityExportStatus.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetActivityExportTasks

> ActivityExportTaskList V3GetActivityExportTasks(ctx).Limit(limit).Offset(offset).Execute()

Get all export tasks for user



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
	resp, r, err := apiClient.ActivityAPI.V3GetActivityExportTasks(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.V3GetActivityExportTasks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetActivityExportTasks`: ActivityExportTaskList
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.V3GetActivityExportTasks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3GetActivityExportTasksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**ActivityExportTaskList**](ActivityExportTaskList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListActivities

> ActivityListResponse V3ListActivities(ctx).Resource(resource).Limit(limit).Offset(offset).OrderBy(orderBy).InstanceId(instanceId).ProjectId(projectId).Actor(actor).Search(search).To(to).From(from).Execute()

Get resource activities



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/corellium/corellium-go-api-client"
)

func main() {
	resource := TODO // interface{} | Resource equality or LHS prefix filter. Examples: `resource=value`, `resource[startsWith]=value`, and `resource[!startsWith]=value`. (optional)
	limit := float32(10) // float32 | Number of entries to return. (optional) (default to 10)
	offset := float32(56) // float32 | Number of results to skip. (optional) (default to 0)
	orderBy := "-createdAt" // string | Field to sort by, for example `createdAt`. Prefix with `-` for newest or largest first. Defaults to `-createdAt` (newest first). (optional) (default to "-createdAt")
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Only activity about this device. (optional)
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | Only activity in this project. (optional)
	actor := "e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320" // string | Only activity performed by this user (user ID). (optional)
	search := "iPhone15,2" // string | Free-text search. Applied last, as a loose match on the results that pass the other filters. (optional)
	to := time.Now() // time.Time | Only activity at or before this time (ISO 8601). (optional)
	from := time.Now() // time.Time | Only activity at or after this time (ISO 8601). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.V3ListActivities(context.Background()).Resource(resource).Limit(limit).Offset(offset).OrderBy(orderBy).InstanceId(instanceId).ProjectId(projectId).Actor(actor).Search(search).To(to).From(from).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.V3ListActivities``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListActivities`: ActivityListResponse
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.V3ListActivities`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListActivitiesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **resource** | [**interface{}**](interface{}.md) | Resource equality or LHS prefix filter. Examples: &#x60;resource&#x3D;value&#x60;, &#x60;resource[startsWith]&#x3D;value&#x60;, and &#x60;resource[!startsWith]&#x3D;value&#x60;. | 
 **limit** | **float32** | Number of entries to return. | [default to 10]
 **offset** | **float32** | Number of results to skip. | [default to 0]
 **orderBy** | **string** | Field to sort by, for example &#x60;createdAt&#x60;. Prefix with &#x60;-&#x60; for newest or largest first. Defaults to &#x60;-createdAt&#x60; (newest first). | [default to &quot;-createdAt&quot;]
 **instanceId** | **string** | Only activity about this device. | 
 **projectId** | **string** | Only activity in this project. | 
 **actor** | **string** | Only activity performed by this user (user ID). | 
 **search** | **string** | Free-text search. Applied last, as a loose match on the results that pass the other filters. | 
 **to** | **time.Time** | Only activity at or before this time (ISO 8601). | 
 **from** | **time.Time** | Only activity at or after this time (ISO 8601). | 

### Return type

[**ActivityListResponse**](ActivityListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

