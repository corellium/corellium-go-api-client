# \WebPlayerV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1WebPlayerAllowedDomains**](WebPlayerV1API.md#V1WebPlayerAllowedDomains) | **Get** /v1/webplayer/allowedDomains | Retrieve the list of allowed domains for all Webplayer sessions
[**V1WebPlayerCreateSession**](WebPlayerV1API.md#V1WebPlayerCreateSession) | **Post** /v1/webplayer | Create a new Webplayer Session
[**V1WebPlayerDestroySession**](WebPlayerV1API.md#V1WebPlayerDestroySession) | **Delete** /v1/webplayer/{sessionId} | Tear down a Webplayer Session
[**V1WebPlayerListSessions**](WebPlayerV1API.md#V1WebPlayerListSessions) | **Get** /v1/webplayer | List all Webplayer sessions
[**V1WebPlayerSessionInfo**](WebPlayerV1API.md#V1WebPlayerSessionInfo) | **Get** /v1/webplayer/{sessionId} | Retrieve Webplayer Session Information



## V1WebPlayerAllowedDomains

> V1WebPlayerAllowedDomains(ctx).Execute()

Retrieve the list of allowed domains for all Webplayer sessions

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
	r, err := apiClient.WebPlayerV1API.V1WebPlayerAllowedDomains(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerV1API.V1WebPlayerAllowedDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1WebPlayerAllowedDomainsRequest struct via the builder pattern


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


## V1WebPlayerCreateSession

> WebPlayerSessionV1 V1WebPlayerCreateSession(ctx).WebPlayerCreateSessionRequest(webPlayerCreateSessionRequest).Execute()

Create a new Webplayer Session

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
	webPlayerCreateSessionRequest := *openapiclient.NewWebPlayerCreateSessionRequest("ProjectId_example", "InstanceId_example", float32(123), *openapiclient.NewFeatures()) // WebPlayerCreateSessionRequest | Request Data

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebPlayerV1API.V1WebPlayerCreateSession(context.Background()).WebPlayerCreateSessionRequest(webPlayerCreateSessionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerV1API.V1WebPlayerCreateSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1WebPlayerCreateSession`: WebPlayerSessionV1
	fmt.Fprintf(os.Stdout, "Response from `WebPlayerV1API.V1WebPlayerCreateSession`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1WebPlayerCreateSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **webPlayerCreateSessionRequest** | [**WebPlayerCreateSessionRequest**](WebPlayerCreateSessionRequest.md) | Request Data | 

### Return type

[**WebPlayerSessionV1**](WebPlayerSessionV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1WebPlayerDestroySession

> []string V1WebPlayerDestroySession(ctx, sessionId).Execute()

Tear down a Webplayer Session

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
	sessionId := "sessionId_example" // string | Webplayer Session identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebPlayerV1API.V1WebPlayerDestroySession(context.Background(), sessionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerV1API.V1WebPlayerDestroySession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1WebPlayerDestroySession`: []string
	fmt.Fprintf(os.Stdout, "Response from `WebPlayerV1API.V1WebPlayerDestroySession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sessionId** | **string** | Webplayer Session identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1WebPlayerDestroySessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## V1WebPlayerListSessions

> []WebPlayerSessionV1 V1WebPlayerListSessions(ctx).Execute()

List all Webplayer sessions

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
	resp, r, err := apiClient.WebPlayerV1API.V1WebPlayerListSessions(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerV1API.V1WebPlayerListSessions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1WebPlayerListSessions`: []WebPlayerSessionV1
	fmt.Fprintf(os.Stdout, "Response from `WebPlayerV1API.V1WebPlayerListSessions`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1WebPlayerListSessionsRequest struct via the builder pattern


### Return type

[**[]WebPlayerSessionV1**](WebPlayerSessionV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1WebPlayerSessionInfo

> WebPlayerSessionV1 V1WebPlayerSessionInfo(ctx, sessionId).Execute()

Retrieve Webplayer Session Information

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
	sessionId := "sessionId_example" // string | Webplayer Session identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebPlayerV1API.V1WebPlayerSessionInfo(context.Background(), sessionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebPlayerV1API.V1WebPlayerSessionInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1WebPlayerSessionInfo`: WebPlayerSessionV1
	fmt.Fprintf(os.Stdout, "Response from `WebPlayerV1API.V1WebPlayerSessionInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sessionId** | **string** | Webplayer Session identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1WebPlayerSessionInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**WebPlayerSessionV1**](WebPlayerSessionV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

