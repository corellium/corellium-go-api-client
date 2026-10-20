# \DomainAuthProvidersAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateDomainAuthProvider**](DomainAuthProvidersAPI.md#V3CreateDomainAuthProvider) | **Post** /v3/domain/{domainId}/auth | Create a new auth provider for a domain
[**V3DeleteDomainAuthProvider**](DomainAuthProvidersAPI.md#V3DeleteDomainAuthProvider) | **Delete** /v3/domain/{domainId}/auth/{providerId} | Delete an auth provider from a domain
[**V3ListDomainAuthProviders**](DomainAuthProvidersAPI.md#V3ListDomainAuthProviders) | **Get** /v3/domain/{domainId}/auth | Return all configured auth providers for a domain (including globally configured providers)
[**V3PatchDomainAuthProvider**](DomainAuthProvidersAPI.md#V3PatchDomainAuthProvider) | **Patch** /v3/domain/{domainId}/auth/{providerId} | Partially update an auth provider for a domain
[**V3UpdateDomainAuthProvider**](DomainAuthProvidersAPI.md#V3UpdateDomainAuthProvider) | **Put** /v3/domain/{domainId}/auth/{providerId} | Update an auth provider for a domain



## V3CreateDomainAuthProvider

> CreateDomainAuthProviderResponse V3CreateDomainAuthProvider(ctx, domainId).CreateDomainAuthProviderBody(createDomainAuthProviderBody).Execute()

Create a new auth provider for a domain



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
	domainId := "c29762d1-45d7-489d-a3a2-9dadc43978ba" // string | Domain identifier.
	createDomainAuthProviderBody := *openapiclient.NewCreateDomainAuthProviderBody("open-id-connect", true) // CreateDomainAuthProviderBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainAuthProvidersAPI.V3CreateDomainAuthProvider(context.Background(), domainId).CreateDomainAuthProviderBody(createDomainAuthProviderBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAuthProvidersAPI.V3CreateDomainAuthProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateDomainAuthProvider`: CreateDomainAuthProviderResponse
	fmt.Fprintf(os.Stdout, "Response from `DomainAuthProvidersAPI.V3CreateDomainAuthProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | Domain identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateDomainAuthProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createDomainAuthProviderBody** | [**CreateDomainAuthProviderBody**](CreateDomainAuthProviderBody.md) |  | 

### Return type

[**CreateDomainAuthProviderResponse**](CreateDomainAuthProviderResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteDomainAuthProvider

> V3DeleteDomainAuthProvider(ctx, domainId, providerId).Execute()

Delete an auth provider from a domain



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
	domainId := "c29762d1-45d7-489d-a3a2-9dadc43978ba" // string | Domain identifier.
	providerId := "sso.example.com" // string | Provider identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DomainAuthProvidersAPI.V3DeleteDomainAuthProvider(context.Background(), domainId, providerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAuthProvidersAPI.V3DeleteDomainAuthProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | Domain identifier. | 
**providerId** | **string** | Provider identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteDomainAuthProviderRequest struct via the builder pattern


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


## V3ListDomainAuthProviders

> DomainAuthProvidersList V3ListDomainAuthProviders(ctx, domainId).Limit(limit).Offset(offset).Execute()

Return all configured auth providers for a domain (including globally configured providers)



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
	domainId := "c29762d1-45d7-489d-a3a2-9dadc43978ba" // string | Domain identifier.
	limit := float32(56) // float32 | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. (optional) (default to 100)
	offset := float32(56) // float32 | How many results to skip before this page starts; defaults to 0. To get the next page, add `limit` to the previous `offset`. (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainAuthProvidersAPI.V3ListDomainAuthProviders(context.Background(), domainId).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAuthProvidersAPI.V3ListDomainAuthProviders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListDomainAuthProviders`: DomainAuthProvidersList
	fmt.Fprintf(os.Stdout, "Response from `DomainAuthProvidersAPI.V3ListDomainAuthProviders`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | Domain identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListDomainAuthProvidersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**DomainAuthProvidersList**](DomainAuthProvidersList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchDomainAuthProvider

> DomainAuthProviderResponse V3PatchDomainAuthProvider(ctx, domainId, providerId).PatchDomainAuthProviderBody(patchDomainAuthProviderBody).Execute()

Partially update an auth provider for a domain



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
	domainId := "c29762d1-45d7-489d-a3a2-9dadc43978ba" // string | Domain identifier.
	providerId := "sso.example.com" // string | Provider identifier.
	patchDomainAuthProviderBody := *openapiclient.NewPatchDomainAuthProviderBody() // PatchDomainAuthProviderBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainAuthProvidersAPI.V3PatchDomainAuthProvider(context.Background(), domainId, providerId).PatchDomainAuthProviderBody(patchDomainAuthProviderBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAuthProvidersAPI.V3PatchDomainAuthProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PatchDomainAuthProvider`: DomainAuthProviderResponse
	fmt.Fprintf(os.Stdout, "Response from `DomainAuthProvidersAPI.V3PatchDomainAuthProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | Domain identifier. | 
**providerId** | **string** | Provider identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchDomainAuthProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **patchDomainAuthProviderBody** | [**PatchDomainAuthProviderBody**](PatchDomainAuthProviderBody.md) |  | 

### Return type

[**DomainAuthProviderResponse**](DomainAuthProviderResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3UpdateDomainAuthProvider

> DomainAuthProviderResponse V3UpdateDomainAuthProvider(ctx, domainId, providerId).CreateDomainAuthProviderBody(createDomainAuthProviderBody).Execute()

Update an auth provider for a domain



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
	domainId := "c29762d1-45d7-489d-a3a2-9dadc43978ba" // string | Domain identifier.
	providerId := "sso.example.com" // string | Provider identifier.
	createDomainAuthProviderBody := *openapiclient.NewCreateDomainAuthProviderBody("open-id-connect", true) // CreateDomainAuthProviderBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainAuthProvidersAPI.V3UpdateDomainAuthProvider(context.Background(), domainId, providerId).CreateDomainAuthProviderBody(createDomainAuthProviderBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainAuthProvidersAPI.V3UpdateDomainAuthProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3UpdateDomainAuthProvider`: DomainAuthProviderResponse
	fmt.Fprintf(os.Stdout, "Response from `DomainAuthProvidersAPI.V3UpdateDomainAuthProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | Domain identifier. | 
**providerId** | **string** | Provider identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UpdateDomainAuthProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createDomainAuthProviderBody** | [**CreateDomainAuthProviderBody**](CreateDomainAuthProviderBody.md) |  | 

### Return type

[**DomainAuthProviderResponse**](DomainAuthProviderResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

