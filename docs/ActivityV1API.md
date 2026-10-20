# \ActivityV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1ActivityExport**](ActivityV1API.md#V1ActivityExport) | **Post** /v1/activity/export | Start activity export
[**V1ActivityList**](ActivityV1API.md#V1ActivityList) | **Get** /v1/activity | Get resource activities
[**V1DownloadActivity**](ActivityV1API.md#V1DownloadActivity) | **Get** /v1/activity/export/{taskId}/download | Download activity
[**V1GetActivityExportStatus**](ActivityV1API.md#V1GetActivityExportStatus) | **Get** /v1/activity/export/{taskId} | Get export task status
[**V1GetActivityExportTasks**](ActivityV1API.md#V1GetActivityExportTasks) | **Get** /v1/activity/export | Get all export tasks for user



## V1ActivityExport

> ActivityExportResponse V1ActivityExport(ctx).ActivityExportDto(activityExportDto).Execute()

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
	activityExportDto := *openapiclient.NewActivityExportDto() // ActivityExportDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityV1API.V1ActivityExport(context.Background()).ActivityExportDto(activityExportDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityV1API.V1ActivityExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ActivityExport`: ActivityExportResponse
	fmt.Fprintf(os.Stdout, "Response from `ActivityV1API.V1ActivityExport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ActivityExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **activityExportDto** | [**ActivityExportDto**](ActivityExportDto.md) |  | 

### Return type

[**ActivityExportResponse**](ActivityExportResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ActivityList

> ActivityList V1ActivityList(ctx).Request(request).Execute()

Get resource activities

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
	request := *openapiclient.NewActivityRequest() // ActivityRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityV1API.V1ActivityList(context.Background()).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityV1API.V1ActivityList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ActivityList`: ActivityList
	fmt.Fprintf(os.Stdout, "Response from `ActivityV1API.V1ActivityList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ActivityListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**ActivityRequest**](ActivityRequest.md) |  | 

### Return type

[**ActivityList**](ActivityList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DownloadActivity

> ActivityList V1DownloadActivity(ctx, taskId).Execute()

Download activity



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
	taskId := "taskId_example" // string | Export ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityV1API.V1DownloadActivity(context.Background(), taskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityV1API.V1DownloadActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DownloadActivity`: ActivityList
	fmt.Fprintf(os.Stdout, "Response from `ActivityV1API.V1DownloadActivity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**taskId** | **string** | Export ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DownloadActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ActivityList**](ActivityList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetActivityExportStatus

> ActivityList V1GetActivityExportStatus(ctx, taskId).Execute()

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
	taskId := "taskId_example" // string | Export ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityV1API.V1GetActivityExportStatus(context.Background(), taskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityV1API.V1GetActivityExportStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetActivityExportStatus`: ActivityList
	fmt.Fprintf(os.Stdout, "Response from `ActivityV1API.V1GetActivityExportStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**taskId** | **string** | Export ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetActivityExportStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ActivityList**](ActivityList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetActivityExportTasks

> ActivityList V1GetActivityExportTasks(ctx).Execute()

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityV1API.V1GetActivityExportTasks(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityV1API.V1GetActivityExportTasks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetActivityExportTasks`: ActivityList
	fmt.Fprintf(os.Stdout, "Response from `ActivityV1API.V1GetActivityExportTasks`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetActivityExportTasksRequest struct via the builder pattern


### Return type

[**ActivityList**](ActivityList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

