# \WebPlayerAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateWebPlayerSession**](WebPlayerAPI.md#V3CreateWebPlayerSession) | **Post** /v3/webplayer | Create a webplayer session
[**V3DeleteWebPlayerSession**](WebPlayerAPI.md#V3DeleteWebPlayerSession) | **Delete** /v3/webplayer/{sessionId} | Delete a webplayer session
[**V3GetWebPlayerAllowedDomains**](WebPlayerAPI.md#V3GetWebPlayerAllowedDomains) | **Get** /v3/webplayer/allowedDomains | Get allowed webplayer domains
[**V3GetWebPlayerSession**](WebPlayerAPI.md#V3GetWebPlayerSession) | **Get** /v3/webplayer/{sessionId} | Get a webplayer session
[**V3ListWebPlayerSessions**](WebPlayerAPI.md#V3ListWebPlayerSessions) | **Get** /v3/webplayer | List webplayer sessions



## V3CreateWebPlayerSession

> WebPlayerCreatedSession V3CreateWebPlayerSession(ctx).CreateWebPlayerSessionBody(createWebPlayerSessionBody).Execute()

Create a webplayer session



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
	createWebPlayerSessionBody := *openapiclient.NewCreateWebPlayerSessionBody("1c41b1bc-4f53-48a8-b690-ad30611e1960", "f7f9832a-f824-416f-a5ea-4adfe34754b5", float32(18000), *openapiclient.NewWebPlayerFeatures()) // CreateWebPlayerSessionBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebPlayerAPI.V3CreateWebPlayerSession(context.Background()).CreateWebPlayerSessionBody(createWebPlayerSessionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerAPI.V3CreateWebPlayerSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateWebPlayerSession`: WebPlayerCreatedSession
	fmt.Fprintf(os.Stdout, "Response from `WebPlayerAPI.V3CreateWebPlayerSession`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateWebPlayerSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createWebPlayerSessionBody** | [**CreateWebPlayerSessionBody**](CreateWebPlayerSessionBody.md) |  | 

### Return type

[**WebPlayerCreatedSession**](WebPlayerCreatedSession.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteWebPlayerSession

> V3DeleteWebPlayerSession(ctx, sessionId).Execute()

Delete a webplayer session



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
	sessionId := "a3569608-10e1-41c7-99fa-1a7d1f336c58" // string | Webplayer session identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WebPlayerAPI.V3DeleteWebPlayerSession(context.Background(), sessionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerAPI.V3DeleteWebPlayerSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sessionId** | **string** | Webplayer session identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteWebPlayerSessionRequest struct via the builder pattern


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


## V3GetWebPlayerAllowedDomains

> WebPlayerAllowedDomains V3GetWebPlayerAllowedDomains(ctx).Execute()

Get allowed webplayer domains



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
	resp, r, err := apiClient.WebPlayerAPI.V3GetWebPlayerAllowedDomains(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerAPI.V3GetWebPlayerAllowedDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetWebPlayerAllowedDomains`: WebPlayerAllowedDomains
	fmt.Fprintf(os.Stdout, "Response from `WebPlayerAPI.V3GetWebPlayerAllowedDomains`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetWebPlayerAllowedDomainsRequest struct via the builder pattern


### Return type

[**WebPlayerAllowedDomains**](WebPlayerAllowedDomains.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetWebPlayerSession

> []WebPlayerSession V3GetWebPlayerSession(ctx, sessionId).Execute()

Get a webplayer session



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
	sessionId := "a3569608-10e1-41c7-99fa-1a7d1f336c58" // string | Webplayer session identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebPlayerAPI.V3GetWebPlayerSession(context.Background(), sessionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerAPI.V3GetWebPlayerSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetWebPlayerSession`: []WebPlayerSession
	fmt.Fprintf(os.Stdout, "Response from `WebPlayerAPI.V3GetWebPlayerSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sessionId** | **string** | Webplayer session identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetWebPlayerSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]WebPlayerSession**](WebPlayerSession.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListWebPlayerSessions

> WebPlayerSessionListResponse V3ListWebPlayerSessions(ctx).Limit(limit).Offset(offset).Execute()

List webplayer sessions



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
	resp, r, err := apiClient.WebPlayerAPI.V3ListWebPlayerSessions(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerAPI.V3ListWebPlayerSessions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListWebPlayerSessions`: WebPlayerSessionListResponse
	fmt.Fprintf(os.Stdout, "Response from `WebPlayerAPI.V3ListWebPlayerSessions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListWebPlayerSessionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**WebPlayerSessionListResponse**](WebPlayerSessionListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

