# \InterconnectsAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateInterconnect**](InterconnectsAPI.md#V3CreateInterconnect) | **Post** /v3/interconnects | Create I/O Interconnect
[**V3DeleteInterconnect**](InterconnectsAPI.md#V3DeleteInterconnect) | **Delete** /v3/interconnects/{interconnectId} | Delete I/O Interconnect
[**V3GetInterconnect**](InterconnectsAPI.md#V3GetInterconnect) | **Get** /v3/interconnects/{interconnectId} | Get Interconnect
[**V3ListInterconnects**](InterconnectsAPI.md#V3ListInterconnects) | **Get** /v3/interconnects | List I/O Interconnects
[**V3PatchInterconnect**](InterconnectsAPI.md#V3PatchInterconnect) | **Patch** /v3/interconnects/{interconnectId} | Patch I/O Interconnect
[**V3UpdateInterconnect**](InterconnectsAPI.md#V3UpdateInterconnect) | **Put** /v3/interconnects/{interconnectId} | Update I/O Interconnect



## V3CreateInterconnect

> Interconnect V3CreateInterconnect(ctx).CreateInterconnectV3Body(createInterconnectV3Body).Execute()

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
	createInterconnectV3Body := *openapiclient.NewCreateInterconnectV3Body("vpn-gateway", "Type_example", []openapiclient.InterfacesSchemaInner{*openapiclient.NewInterfacesSchemaInner("f7f9832a-f824-416f-a5ea-4adfe34754b5", "eth0:1/2")}, "1c41b1bc-4f53-48a8-b690-ad30611e1960", openapiclient.InterconnectProtocol("can")) // CreateInterconnectV3Body | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsAPI.V3CreateInterconnect(context.Background()).CreateInterconnectV3Body(createInterconnectV3Body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsAPI.V3CreateInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateInterconnect`: Interconnect
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsAPI.V3CreateInterconnect`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateInterconnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createInterconnectV3Body** | [**CreateInterconnectV3Body**](CreateInterconnectV3Body.md) |  | 

### Return type

[**Interconnect**](Interconnect.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteInterconnect

> V3DeleteInterconnect(ctx, interconnectId).Execute()

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
	interconnectId := "56494514-33f7-4fc2-9fdc-865e3957e6d3" // string | The interconnect identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InterconnectsAPI.V3DeleteInterconnect(context.Background(), interconnectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsAPI.V3DeleteInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**interconnectId** | **string** | The interconnect identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteInterconnectRequest struct via the builder pattern


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


## V3GetInterconnect

> Interconnect V3GetInterconnect(ctx, interconnectId).Execute()

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
	interconnectId := "56494514-33f7-4fc2-9fdc-865e3957e6d3" // string | The interconnect identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsAPI.V3GetInterconnect(context.Background(), interconnectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsAPI.V3GetInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInterconnect`: Interconnect
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsAPI.V3GetInterconnect`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**interconnectId** | **string** | The interconnect identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInterconnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Interconnect**](Interconnect.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListInterconnects

> InterconnectList V3ListInterconnects(ctx).Limit(limit).Offset(offset).Name(name).Protocol(protocol).Type_(type_).Status(status).Sort(sort).ProjectId(projectId).Execute()

List I/O Interconnects



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
	name := "vpn-gateway" // string | Filter by interconnect name (case insensitive). (optional)
	protocol := "eth" // string | Filter by protocol (comma separated). (optional)
	type_ := "type__example" // string | Filter by type (comma separated). (optional)
	status := "status_example" // string | Filter by status (comma separated). (optional)
	sort := "-name" // string | Sort order (e.g. \"name\" for ascending, \"-name\" for descending, comma separated). (optional)
	projectId := "1c41b1bc-4f53-48a8-b690-ad30611e1960" // string | Filter by project ID (comma separated). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsAPI.V3ListInterconnects(context.Background()).Limit(limit).Offset(offset).Name(name).Protocol(protocol).Type_(type_).Status(status).Sort(sort).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsAPI.V3ListInterconnects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListInterconnects`: InterconnectList
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsAPI.V3ListInterconnects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListInterconnectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]
 **name** | **string** | Filter by interconnect name (case insensitive). | 
 **protocol** | **string** | Filter by protocol (comma separated). | 
 **type_** | **string** | Filter by type (comma separated). | 
 **status** | **string** | Filter by status (comma separated). | 
 **sort** | **string** | Sort order (e.g. \&quot;name\&quot; for ascending, \&quot;-name\&quot; for descending, comma separated). | 
 **projectId** | **string** | Filter by project ID (comma separated). | 

### Return type

[**InterconnectList**](InterconnectList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchInterconnect

> Interconnect V3PatchInterconnect(ctx, interconnectId).PatchInterconnectBody(patchInterconnectBody).Execute()

Patch I/O Interconnect



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
	interconnectId := "56494514-33f7-4fc2-9fdc-865e3957e6d3" // string | The interconnect identifier.
	patchInterconnectBody := *openapiclient.NewPatchInterconnectBody() // PatchInterconnectBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsAPI.V3PatchInterconnect(context.Background(), interconnectId).PatchInterconnectBody(patchInterconnectBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsAPI.V3PatchInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PatchInterconnect`: Interconnect
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsAPI.V3PatchInterconnect`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**interconnectId** | **string** | The interconnect identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchInterconnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchInterconnectBody** | [**PatchInterconnectBody**](PatchInterconnectBody.md) |  | 

### Return type

[**Interconnect**](Interconnect.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3UpdateInterconnect

> Interconnect V3UpdateInterconnect(ctx, interconnectId).UpdateInterconnectV3Body(updateInterconnectV3Body).Execute()

Update I/O Interconnect



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
	interconnectId := "56494514-33f7-4fc2-9fdc-865e3957e6d3" // string | The interconnect identifier.
	updateInterconnectV3Body := *openapiclient.NewUpdateInterconnectV3Body("vpn-gateway", []openapiclient.InterfacesSchemaInner{*openapiclient.NewInterfacesSchemaInner("f7f9832a-f824-416f-a5ea-4adfe34754b5", "eth0:1/2")}) // UpdateInterconnectV3Body | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InterconnectsAPI.V3UpdateInterconnect(context.Background(), interconnectId).UpdateInterconnectV3Body(updateInterconnectV3Body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InterconnectsAPI.V3UpdateInterconnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3UpdateInterconnect`: Interconnect
	fmt.Fprintf(os.Stdout, "Response from `InterconnectsAPI.V3UpdateInterconnect`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**interconnectId** | **string** | The interconnect identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UpdateInterconnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateInterconnectV3Body** | [**UpdateInterconnectV3Body**](UpdateInterconnectV3Body.md) |  | 

### Return type

[**Interconnect**](Interconnect.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

