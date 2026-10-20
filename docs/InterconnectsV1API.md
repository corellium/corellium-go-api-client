# \InterconnectsV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1CreateInterconnect**](InterconnectsV1API.md#V1CreateInterconnect) | **Post** /v1/interconnects | Create I/O Interconnect
[**V1DeleteInterconnect**](InterconnectsV1API.md#V1DeleteInterconnect) | **Delete** /v1/interconnects/{interconnectId} | Delete I/O Interconnect
[**V1GetInterconnect**](InterconnectsV1API.md#V1GetInterconnect) | **Get** /v1/interconnects/{interconnectId} | Get Interconnect
[**V1ListInterconnects**](InterconnectsV1API.md#V1ListInterconnects) | **Get** /v1/interconnects | Get all I/O Interconnects
[**V1PatchInterconnect**](InterconnectsV1API.md#V1PatchInterconnect) | **Patch** /v1/interconnects/{interconnectId} | Partial Update Interconnect
[**V1UpdateInterconnect**](InterconnectsV1API.md#V1UpdateInterconnect) | **Put** /v1/interconnects/{interconnectId} | Update Interconnect



## V1CreateInterconnect

> InterconnectResponse V1CreateInterconnect(ctx).CreateInterconnectBody(createInterconnectBody).Execute()

Create I/O Interconnect



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
	createInterconnectBody := *openapiclient.NewCreateInterconnectBody("Name_example", "Protocol_example", "Type_example", "Project_example", []string{"Interfaces_example"}) // CreateInterconnectBody | The interconnect details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsV1API.V1CreateInterconnect(context.Background()).CreateInterconnectBody(createInterconnectBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsV1API.V1CreateInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateInterconnect`: InterconnectResponse
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsV1API.V1CreateInterconnect`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateInterconnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createInterconnectBody** | [**CreateInterconnectBody**](CreateInterconnectBody.md) | The interconnect details | 

### Return type

[**InterconnectResponse**](InterconnectResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteInterconnect

> V1DeleteInterconnect(ctx, interconnectId).Execute()

Delete I/O Interconnect

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
	interconnectId := "interconnectId_example" // string | The interconnect identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InterconnectsV1API.V1DeleteInterconnect(context.Background(), interconnectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsV1API.V1DeleteInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**interconnectId** | **string** | The interconnect identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteInterconnectRequest struct via the builder pattern


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


## V1GetInterconnect

> InterconnectResponse V1GetInterconnect(ctx, interconnectId).Execute()

Get Interconnect

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
	interconnectId := "interconnectId_example" // string | The interconnect identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsV1API.V1GetInterconnect(context.Background(), interconnectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsV1API.V1GetInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInterconnect`: InterconnectResponse
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsV1API.V1GetInterconnect`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**interconnectId** | **string** | The interconnect identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInterconnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InterconnectResponse**](InterconnectResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListInterconnects

> GetInterconnectsResponse V1ListInterconnects(ctx).Limit(limit).Offset(offset).Name(name).Protocol(protocol).Type_(type_).Status(status).Project(project).Sort(sort).Execute()

Get all I/O Interconnects

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
	limit := float32(8.14) // float32 | Maximum number of results to return (1-1000, default: 100) (optional)
	offset := float32(8.14) // float32 | Number of results to skip (default: 0) (optional)
	name := "name_example" // string | Filter by interconnect name (case insensitive) (optional)
	protocol := "protocol_example" // string | Filter by protocol (comma separated) (optional)
	type_ := "type__example" // string | Filter by type (comma separated) (optional)
	status := "status_example" // string | Filter by status (comma separated) (optional)
	project := "project_example" // string | Filter by project ID (comma separated) (optional)
	sort := "sort_example" // string | Sort order (e.g. \"name\" for ascending, \"-name\" for descending, comma separated) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsV1API.V1ListInterconnects(context.Background()).Limit(limit).Offset(offset).Name(name).Protocol(protocol).Type_(type_).Status(status).Project(project).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsV1API.V1ListInterconnects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListInterconnects`: GetInterconnectsResponse
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsV1API.V1ListInterconnects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ListInterconnectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Maximum number of results to return (1-1000, default: 100) | 
 **offset** | **float32** | Number of results to skip (default: 0) | 
 **name** | **string** | Filter by interconnect name (case insensitive) | 
 **protocol** | **string** | Filter by protocol (comma separated) | 
 **type_** | **string** | Filter by type (comma separated) | 
 **status** | **string** | Filter by status (comma separated) | 
 **project** | **string** | Filter by project ID (comma separated) | 
 **sort** | **string** | Sort order (e.g. \&quot;name\&quot; for ascending, \&quot;-name\&quot; for descending, comma separated) | 

### Return type

[**GetInterconnectsResponse**](GetInterconnectsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PatchInterconnect

> InterconnectResponse V1PatchInterconnect(ctx, interconnectId).PartialUpdateInterconnectRequest(partialUpdateInterconnectRequest).Execute()

Partial Update Interconnect



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
	interconnectId := "interconnectId_example" // string | The interconnect identifier
	partialUpdateInterconnectRequest := *openapiclient.NewPartialUpdateInterconnectRequest() // PartialUpdateInterconnectRequest | The interconnect details to update

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsV1API.V1PatchInterconnect(context.Background(), interconnectId).PartialUpdateInterconnectRequest(partialUpdateInterconnectRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsV1API.V1PatchInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1PatchInterconnect`: InterconnectResponse
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsV1API.V1PatchInterconnect`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**interconnectId** | **string** | The interconnect identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PatchInterconnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **partialUpdateInterconnectRequest** | [**PartialUpdateInterconnectRequest**](PartialUpdateInterconnectRequest.md) | The interconnect details to update | 

### Return type

[**InterconnectResponse**](InterconnectResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UpdateInterconnect

> InterconnectResponse V1UpdateInterconnect(ctx, interconnectId).UpdateInterconnectBody(updateInterconnectBody).Execute()

Update Interconnect



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
	interconnectId := "interconnectId_example" // string | The interconnect identifier
	updateInterconnectBody := *openapiclient.NewUpdateInterconnectBody("Name_example", []map[string]interface{}{map[string]interface{}(123)}) // UpdateInterconnectBody | The interconnect details to update

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsV1API.V1UpdateInterconnect(context.Background(), interconnectId).UpdateInterconnectBody(updateInterconnectBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsV1API.V1UpdateInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UpdateInterconnect`: InterconnectResponse
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsV1API.V1UpdateInterconnect`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**interconnectId** | **string** | The interconnect identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UpdateInterconnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateInterconnectBody** | [**UpdateInterconnectBody**](UpdateInterconnectBody.md) | The interconnect details to update | 

### Return type

[**InterconnectResponse**](InterconnectResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

