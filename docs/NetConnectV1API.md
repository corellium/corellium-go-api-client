# \NetConnectV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1CreateNetworkConnection**](NetConnectV1API.md#V1CreateNetworkConnection) | **Post** /v1/network/connections | Create a new Network Connection
[**V1DeleteNetworkConnection**](NetConnectV1API.md#V1DeleteNetworkConnection) | **Delete** /v1/network/connections/{id} | Delete an existing Network Connection
[**V1GetNetworkConnection**](NetConnectV1API.md#V1GetNetworkConnection) | **Get** /v1/network/connections/{id} | Return the configuration and per project statuses for a single network provider.
[**V1ListNetworkConnections**](NetConnectV1API.md#V1ListNetworkConnections) | **Get** /v1/network/connections | List available network connections
[**V1ListNetworkInterfaces**](NetConnectV1API.md#V1ListNetworkInterfaces) | **Get** /v1/network/interfaces | List available physical network interfaces
[**V1ListNetworkProviders**](NetConnectV1API.md#V1ListNetworkProviders) | **Get** /v1/network/providers | List available network providers
[**V1PartialUpdateNetworkConnection**](NetConnectV1API.md#V1PartialUpdateNetworkConnection) | **Patch** /v1/network/connections/{id} | Update Network Connection (partial)
[**V1UpdateNetworkConnection**](NetConnectV1API.md#V1UpdateNetworkConnection) | **Put** /v1/network/connections/{id} | Update Network Connection



## V1CreateNetworkConnection

> NetworkConnection V1CreateNetworkConnection(ctx).CreateNetworkConnectionOptions(createNetworkConnectionOptions).Execute()

Create a new Network Connection



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
	createNetworkConnectionOptions := openapiclient.CreateNetworkConnectionOptions{CreateOpenVPNNetworkConnectionBodyV1: openapiclient.NewCreateOpenVPNNetworkConnectionBodyV1("Name_example", "Provider_example", *openapiclient.NewOpenVPNConfigV1("Config_example"))} // CreateNetworkConnectionOptions | Network Connection Options

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectV1API.V1CreateNetworkConnection(context.Background()).CreateNetworkConnectionOptions(createNetworkConnectionOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectV1API.V1CreateNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateNetworkConnection`: NetworkConnection
	fmt.Fprintf(os.Stdout, "Response from `NetConnectV1API.V1CreateNetworkConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createNetworkConnectionOptions** | [**CreateNetworkConnectionOptions**](CreateNetworkConnectionOptions.md) | Network Connection Options | 

### Return type

[**NetworkConnection**](NetworkConnection.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteNetworkConnection

> V1DeleteNetworkConnection(ctx, id).DeleteNetworkConnectionOptions(deleteNetworkConnectionOptions).Execute()

Delete an existing Network Connection



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
	id := "id_example" // string | Network Connection Identifier - uuid
	deleteNetworkConnectionOptions := *openapiclient.NewDeleteNetworkConnectionOptions() // DeleteNetworkConnectionOptions | Delete options (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.NetConnectV1API.V1DeleteNetworkConnection(context.Background(), id).DeleteNetworkConnectionOptions(deleteNetworkConnectionOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectV1API.V1DeleteNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Network Connection Identifier - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deleteNetworkConnectionOptions** | [**DeleteNetworkConnectionOptions**](DeleteNetworkConnectionOptions.md) | Delete options | 

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


## V1GetNetworkConnection

> NetworkConnection V1GetNetworkConnection(ctx, id).Execute()

Return the configuration and per project statuses for a single network provider.



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
	id := "id_example" // string | Network Connection Identifier - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectV1API.V1GetNetworkConnection(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectV1API.V1GetNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetNetworkConnection`: NetworkConnection
	fmt.Fprintf(os.Stdout, "Response from `NetConnectV1API.V1GetNetworkConnection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Network Connection Identifier - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NetworkConnection**](NetworkConnection.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListNetworkConnections

> NetworkConnectionPaginationResult V1ListNetworkConnections(ctx).Limit(limit).Offset(offset).Execute()

List available network connections



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
	limit := float32(8.14) // float32 | The maximum number of items to return. (optional)
	offset := float32(8.14) // float32 | The starting index of the items to return. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectV1API.V1ListNetworkConnections(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectV1API.V1ListNetworkConnections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListNetworkConnections`: NetworkConnectionPaginationResult
	fmt.Fprintf(os.Stdout, "Response from `NetConnectV1API.V1ListNetworkConnections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ListNetworkConnectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | The maximum number of items to return. | 
 **offset** | **float32** | The starting index of the items to return. | 

### Return type

[**NetworkConnectionPaginationResult**](NetworkConnectionPaginationResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListNetworkInterfaces

> []string V1ListNetworkInterfaces(ctx).Execute()

List available physical network interfaces



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
	resp, r, err := apiClient.NetConnectV1API.V1ListNetworkInterfaces(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectV1API.V1ListNetworkInterfaces``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListNetworkInterfaces`: []string
	fmt.Fprintf(os.Stdout, "Response from `NetConnectV1API.V1ListNetworkInterfaces`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1ListNetworkInterfacesRequest struct via the builder pattern


### Return type

**[]string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ListNetworkProviders

> NetworkConnectionProviderPaginationResult V1ListNetworkProviders(ctx).Execute()

List available network providers



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
	resp, r, err := apiClient.NetConnectV1API.V1ListNetworkProviders(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectV1API.V1ListNetworkProviders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ListNetworkProviders`: NetworkConnectionProviderPaginationResult
	fmt.Fprintf(os.Stdout, "Response from `NetConnectV1API.V1ListNetworkProviders`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1ListNetworkProvidersRequest struct via the builder pattern


### Return type

[**NetworkConnectionProviderPaginationResult**](NetworkConnectionProviderPaginationResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PartialUpdateNetworkConnection

> NetworkConnection V1PartialUpdateNetworkConnection(ctx, id).PartialUpdateNetworkConnectionOptions(partialUpdateNetworkConnectionOptions).Execute()

Update Network Connection (partial)



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
	id := "id_example" // string | Network Connection Identifier - uuid
	partialUpdateNetworkConnectionOptions := *openapiclient.NewPartialUpdateNetworkConnectionOptions() // PartialUpdateNetworkConnectionOptions | Network Connection Options

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectV1API.V1PartialUpdateNetworkConnection(context.Background(), id).PartialUpdateNetworkConnectionOptions(partialUpdateNetworkConnectionOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectV1API.V1PartialUpdateNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1PartialUpdateNetworkConnection`: NetworkConnection
	fmt.Fprintf(os.Stdout, "Response from `NetConnectV1API.V1PartialUpdateNetworkConnection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Network Connection Identifier - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PartialUpdateNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **partialUpdateNetworkConnectionOptions** | [**PartialUpdateNetworkConnectionOptions**](PartialUpdateNetworkConnectionOptions.md) | Network Connection Options | 

### Return type

[**NetworkConnection**](NetworkConnection.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UpdateNetworkConnection

> NetworkConnection V1UpdateNetworkConnection(ctx, id).UpdateNetworkConnectionOptions(updateNetworkConnectionOptions).Execute()

Update Network Connection



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
	id := "id_example" // string | Network Connection Identifier - uuid
	updateNetworkConnectionOptions := *openapiclient.NewUpdateNetworkConnectionOptions("Name_example") // UpdateNetworkConnectionOptions | Network Connection Options

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectV1API.V1UpdateNetworkConnection(context.Background(), id).UpdateNetworkConnectionOptions(updateNetworkConnectionOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectV1API.V1UpdateNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UpdateNetworkConnection`: NetworkConnection
	fmt.Fprintf(os.Stdout, "Response from `NetConnectV1API.V1UpdateNetworkConnection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Network Connection Identifier - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UpdateNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateNetworkConnectionOptions** | [**UpdateNetworkConnectionOptions**](UpdateNetworkConnectionOptions.md) | Network Connection Options | 

### Return type

[**NetworkConnection**](NetworkConnection.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

