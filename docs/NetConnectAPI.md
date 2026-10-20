# \NetConnectAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateNetworkConnection**](NetConnectAPI.md#V3CreateNetworkConnection) | **Post** /v3/network/connections | Create a new Network Connection
[**V3DeleteNetworkConnection**](NetConnectAPI.md#V3DeleteNetworkConnection) | **Delete** /v3/network/connections/{id} | Delete an existing Network Connection
[**V3GetNetworkConnection**](NetConnectAPI.md#V3GetNetworkConnection) | **Get** /v3/network/connections/{id} | Fetch an existing Network Connection
[**V3ListNetworkConnections**](NetConnectAPI.md#V3ListNetworkConnections) | **Get** /v3/network/connections | List available network connections
[**V3ListNetworkInterfaces**](NetConnectAPI.md#V3ListNetworkInterfaces) | **Get** /v3/network/interfaces | List available physical network interfaces
[**V3ListNetworkProviders**](NetConnectAPI.md#V3ListNetworkProviders) | **Get** /v3/network/providers | List available network providers
[**V3PartialUpdateNetworkConnection**](NetConnectAPI.md#V3PartialUpdateNetworkConnection) | **Patch** /v3/network/connections/{id} | Update Network Connection (patch)
[**V3UpdateNetworkConnection**](NetConnectAPI.md#V3UpdateNetworkConnection) | **Put** /v3/network/connections/{id} | Update Network Connection



## V3CreateNetworkConnection

> []ProviderNetworkConnection V3CreateNetworkConnection(ctx).CreateNetworkConnectionBody(createNetworkConnectionBody).Execute()

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
	createNetworkConnectionBody := openapiclient.CreateNetworkConnectionBody{CreateOpenVPNNetworkConnectionBody: openapiclient.NewCreateOpenVPNNetworkConnectionBody("office-vpn", "Provider_example", *openapiclient.NewOpenVPNConfig("client
dev tun
proto udp
remote vpn.example.com 1194
resolv-retry infinite
nobind
persist-key
persist-tun
remote-cert-tls server
cipher AES-256-CBC
verb 3
<ca>
-----BEGIN CERTIFICATE-----
<ca-certificate>
-----END CERTIFICATE-----
</ca>
"))} // CreateNetworkConnectionBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectAPI.V3CreateNetworkConnection(context.Background()).CreateNetworkConnectionBody(createNetworkConnectionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectAPI.V3CreateNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateNetworkConnection`: []ProviderNetworkConnection
	fmt.Fprintf(os.Stdout, "Response from `NetConnectAPI.V3CreateNetworkConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createNetworkConnectionBody** | [**CreateNetworkConnectionBody**](CreateNetworkConnectionBody.md) |  | 

### Return type

[**[]ProviderNetworkConnection**](ProviderNetworkConnection.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteNetworkConnection

> V3DeleteNetworkConnection(ctx, id).V3DeleteNetworkConnectionRequest(v3DeleteNetworkConnectionRequest).Execute()

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
	id := "0eb5d1e7-2c10-42b1-95fc-30e4e4885cd7" // string | Network Connection Identifier.
	v3DeleteNetworkConnectionRequest := *openapiclient.NewV3DeleteNetworkConnectionRequest() // V3DeleteNetworkConnectionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.NetConnectAPI.V3DeleteNetworkConnection(context.Background(), id).V3DeleteNetworkConnectionRequest(v3DeleteNetworkConnectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectAPI.V3DeleteNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Network Connection Identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v3DeleteNetworkConnectionRequest** | [**V3DeleteNetworkConnectionRequest**](V3DeleteNetworkConnectionRequest.md) |  | 

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


## V3GetNetworkConnection

> ProviderNetworkConnection V3GetNetworkConnection(ctx, id).Execute()

Fetch an existing Network Connection



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
	id := "0eb5d1e7-2c10-42b1-95fc-30e4e4885cd7" // string | Network Connection Identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectAPI.V3GetNetworkConnection(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectAPI.V3GetNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetNetworkConnection`: ProviderNetworkConnection
	fmt.Fprintf(os.Stdout, "Response from `NetConnectAPI.V3GetNetworkConnection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Network Connection Identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProviderNetworkConnection**](ProviderNetworkConnection.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListNetworkConnections

> NetworkConnections V3ListNetworkConnections(ctx).Limit(limit).Offset(offset).Execute()

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
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectAPI.V3ListNetworkConnections(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectAPI.V3ListNetworkConnections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListNetworkConnections`: NetworkConnections
	fmt.Fprintf(os.Stdout, "Response from `NetConnectAPI.V3ListNetworkConnections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListNetworkConnectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**NetworkConnections**](NetworkConnections.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListNetworkInterfaces

> NetworkInterfaces V3ListNetworkInterfaces(ctx).Limit(limit).Offset(offset).Execute()

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
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectAPI.V3ListNetworkInterfaces(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectAPI.V3ListNetworkInterfaces``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListNetworkInterfaces`: NetworkInterfaces
	fmt.Fprintf(os.Stdout, "Response from `NetConnectAPI.V3ListNetworkInterfaces`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListNetworkInterfacesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**NetworkInterfaces**](NetworkInterfaces.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListNetworkProviders

> NetworkConnectionProviders V3ListNetworkProviders(ctx).Limit(limit).Offset(offset).Execute()

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
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectAPI.V3ListNetworkProviders(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectAPI.V3ListNetworkProviders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListNetworkProviders`: NetworkConnectionProviders
	fmt.Fprintf(os.Stdout, "Response from `NetConnectAPI.V3ListNetworkProviders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListNetworkProvidersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**NetworkConnectionProviders**](NetworkConnectionProviders.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PartialUpdateNetworkConnection

> ProviderNetworkConnection V3PartialUpdateNetworkConnection(ctx, id).PartialUpdateNetworkConnectionBody(partialUpdateNetworkConnectionBody).Execute()

Update Network Connection (patch)



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
	id := "0eb5d1e7-2c10-42b1-95fc-30e4e4885cd7" // string | Network Connection Identifier.
	partialUpdateNetworkConnectionBody := *openapiclient.NewPartialUpdateNetworkConnectionBody() // PartialUpdateNetworkConnectionBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectAPI.V3PartialUpdateNetworkConnection(context.Background(), id).PartialUpdateNetworkConnectionBody(partialUpdateNetworkConnectionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectAPI.V3PartialUpdateNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PartialUpdateNetworkConnection`: ProviderNetworkConnection
	fmt.Fprintf(os.Stdout, "Response from `NetConnectAPI.V3PartialUpdateNetworkConnection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Network Connection Identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PartialUpdateNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **partialUpdateNetworkConnectionBody** | [**PartialUpdateNetworkConnectionBody**](PartialUpdateNetworkConnectionBody.md) |  | 

### Return type

[**ProviderNetworkConnection**](ProviderNetworkConnection.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3UpdateNetworkConnection

> ProviderNetworkConnection V3UpdateNetworkConnection(ctx, id).UpdateNetworkConnectionBody(updateNetworkConnectionBody).Execute()

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
	id := "0eb5d1e7-2c10-42b1-95fc-30e4e4885cd7" // string | Network Connection Identifier.
	updateNetworkConnectionBody := *openapiclient.NewUpdateNetworkConnectionBody("office-vpn") // UpdateNetworkConnectionBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NetConnectAPI.V3UpdateNetworkConnection(context.Background(), id).UpdateNetworkConnectionBody(updateNetworkConnectionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NetConnectAPI.V3UpdateNetworkConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3UpdateNetworkConnection`: ProviderNetworkConnection
	fmt.Fprintf(os.Stdout, "Response from `NetConnectAPI.V3UpdateNetworkConnection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Network Connection Identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UpdateNetworkConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateNetworkConnectionBody** | [**UpdateNetworkConnectionBody**](UpdateNetworkConnectionBody.md) |  | 

### Return type

[**ProviderNetworkConnection**](ProviderNetworkConnection.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

