# \AuthenticationAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3AuthLogin**](AuthenticationAPI.md#V3AuthLogin) | **Post** /v3/auth/login | Log in
[**V3AuthLogout**](AuthenticationAPI.md#V3AuthLogout) | **Post** /v3/auth/logout | Log out
[**V3DeleteApiToken**](AuthenticationAPI.md#V3DeleteApiToken) | **Delete** /v3/auth/apitoken | Delete API token
[**V3FetchAuthProviderMetadata**](AuthenticationAPI.md#V3FetchAuthProviderMetadata) | **Get** /v3/auth/providers/fetch-metadata | Fetch SAML metadata
[**V3GenerateApiToken**](AuthenticationAPI.md#V3GenerateApiToken) | **Post** /v3/auth/apitoken | Generate API token
[**V3GetAuthProviderAuthorizationUrl**](AuthenticationAPI.md#V3GetAuthProviderAuthorizationUrl) | **Get** /v3/auth/providers/{providerId}/authorization_url | Get provider authorization URL
[**V3GetAuthProviderCallback**](AuthenticationAPI.md#V3GetAuthProviderCallback) | **Get** /v3/auth/providers/{providerId}/callback | Authentication provider callback (GET)
[**V3GetAuthProviderSpMetadata**](AuthenticationAPI.md#V3GetAuthProviderSpMetadata) | **Get** /v3/auth/providers/{providerId}/spmetadata | Get service provider metadata
[**V3ListAuthProviderTypes**](AuthenticationAPI.md#V3ListAuthProviderTypes) | **Get** /v3/auth/providers/types | List authentication provider types
[**V3ListAuthProviders**](AuthenticationAPI.md#V3ListAuthProviders) | **Get** /v3/auth/providers | List authentication providers
[**V3PostAuthProviderCallback**](AuthenticationAPI.md#V3PostAuthProviderCallback) | **Post** /v3/auth/providers/{providerId}/callback | Authentication provider callback (POST)



## V3AuthLogin

> LoginResult V3AuthLogin(ctx).LoginBody(loginBody).Execute()

Log in



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
	loginBody := *openapiclient.NewLoginBody() // LoginBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthenticationAPI.V3AuthLogin(context.Background()).LoginBody(loginBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3AuthLogin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3AuthLogin`: LoginResult
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.V3AuthLogin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3AuthLoginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **loginBody** | [**LoginBody**](LoginBody.md) |  | 

### Return type

[**LoginResult**](LoginResult.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3AuthLogout

> V3AuthLogout(ctx).Execute()

Log out



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
	r, err := apiClient.AuthenticationAPI.V3AuthLogout(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3AuthLogout``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3AuthLogoutRequest struct via the builder pattern


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


## V3DeleteApiToken

> V3DeleteApiToken(ctx).Execute()

Delete API token



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
	r, err := apiClient.AuthenticationAPI.V3DeleteApiToken(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3DeleteApiToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteApiTokenRequest struct via the builder pattern


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


## V3FetchAuthProviderMetadata

> string V3FetchAuthProviderMetadata(ctx).Url(url).Execute()

Fetch SAML metadata



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
	url := "https://sso.okta.com/app/exk1a2b3c4d5e6f7g8h9/sso/saml/metadata" // string | HTTPS URL of the SAML metadata endpoint to fetch.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthenticationAPI.V3FetchAuthProviderMetadata(context.Background()).Url(url).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3FetchAuthProviderMetadata``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3FetchAuthProviderMetadata`: string
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.V3FetchAuthProviderMetadata`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3FetchAuthProviderMetadataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **url** | **string** | HTTPS URL of the SAML metadata endpoint to fetch. | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/xml, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GenerateApiToken

> ApiTokenResult V3GenerateApiToken(ctx).Execute()

Generate API token



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
	resp, r, err := apiClient.AuthenticationAPI.V3GenerateApiToken(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3GenerateApiToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GenerateApiToken`: ApiTokenResult
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.V3GenerateApiToken`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GenerateApiTokenRequest struct via the builder pattern


### Return type

[**ApiTokenResult**](ApiTokenResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetAuthProviderAuthorizationUrl

> V3GetAuthProviderAuthorizationUrl(ctx, providerId).Type_(type_).Code(code).Email(email).Token(token).Execute()

Get provider authorization URL



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
	providerId := "sso.example.com" // string | Provider identifier.
	type_ := "type__example" // string | Sign-up flow type. (optional)
	code := "INVITE1234" // string | Sign-up code for subscriber invites and trial requests. (optional)
	email := "jane.doe@example.com" // string | Sign-up email (may differ from SSO email). (optional)
	token := "<token>" // string | Sign-up token for a team invite. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AuthenticationAPI.V3GetAuthProviderAuthorizationUrl(context.Background(), providerId).Type_(type_).Code(code).Email(email).Token(token).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3GetAuthProviderAuthorizationUrl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**providerId** | **string** | Provider identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetAuthProviderAuthorizationUrlRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **type_** | **string** | Sign-up flow type. | 
 **code** | **string** | Sign-up code for subscriber invites and trial requests. | 
 **email** | **string** | Sign-up email (may differ from SSO email). | 
 **token** | **string** | Sign-up token for a team invite. | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetAuthProviderCallback

> V3GetAuthProviderCallback(ctx, providerId).Error_(error_).ErrorDescription(errorDescription).Execute()

Authentication provider callback (GET)



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
	providerId := "sso.example.com" // string | Provider identifier.
	error_ := "access_denied" // string | Error code from the provider. (optional)
	errorDescription := "The user denied the request." // string | Error description from the provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AuthenticationAPI.V3GetAuthProviderCallback(context.Background(), providerId).Error_(error_).ErrorDescription(errorDescription).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3GetAuthProviderCallback``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**providerId** | **string** | Provider identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetAuthProviderCallbackRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **error_** | **string** | Error code from the provider. | 
 **errorDescription** | **string** | Error description from the provider. | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetAuthProviderSpMetadata

> string V3GetAuthProviderSpMetadata(ctx, providerId).Execute()

Get service provider metadata



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
	providerId := "sso.example.com" // string | Provider identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthenticationAPI.V3GetAuthProviderSpMetadata(context.Background(), providerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3GetAuthProviderSpMetadata``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetAuthProviderSpMetadata`: string
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.V3GetAuthProviderSpMetadata`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**providerId** | **string** | Provider identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetAuthProviderSpMetadataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/xml, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListAuthProviderTypes

> AuthProviderTypesListResponse V3ListAuthProviderTypes(ctx).Limit(limit).Offset(offset).Execute()

List authentication provider types



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
	resp, r, err := apiClient.AuthenticationAPI.V3ListAuthProviderTypes(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3ListAuthProviderTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListAuthProviderTypes`: AuthProviderTypesListResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.V3ListAuthProviderTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListAuthProviderTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**AuthProviderTypesListResponse**](AuthProviderTypesListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListAuthProviders

> AuthProvidersListResponse V3ListAuthProviders(ctx).Limit(limit).Offset(offset).Execute()

List authentication providers



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
	resp, r, err := apiClient.AuthenticationAPI.V3ListAuthProviders(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3ListAuthProviders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListAuthProviders`: AuthProvidersListResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthenticationAPI.V3ListAuthProviders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListAuthProvidersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**AuthProvidersListResponse**](AuthProvidersListResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PostAuthProviderCallback

> V3PostAuthProviderCallback(ctx, providerId).Execute()

Authentication provider callback (POST)



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
	providerId := "sso.example.com" // string | Provider identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AuthenticationAPI.V3PostAuthProviderCallback(context.Background(), providerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAPI.V3PostAuthProviderCallback``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**providerId** | **string** | Provider identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PostAuthProviderCallbackRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

