# \DomainV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1CreateDomainWelcomeMessage**](DomainV1API.md#V1CreateDomainWelcomeMessage) | **Post** /v1/domain/welcome | Create a welcome message for a domain
[**V1DeleteDomainWelcomeMessage**](DomainV1API.md#V1DeleteDomainWelcomeMessage) | **Delete** /v1/domain/welcome | Delete the welcome message for the authenticated user&#39;s domain
[**V1GetDomainWelcomeMessage**](DomainV1API.md#V1GetDomainWelcomeMessage) | **Get** /v1/domain/welcome | Get the welcome message for the authenticated user&#39;s domain
[**V1UpdateDomainWelcomeMessage**](DomainV1API.md#V1UpdateDomainWelcomeMessage) | **Patch** /v1/domain/welcome | Update a welcome message for a domain



## V1CreateDomainWelcomeMessage

> DomainWelcomeMessageResponseV1 V1CreateDomainWelcomeMessage(ctx).CreateDomainWelcomeMessageBody(createDomainWelcomeMessageBody).Execute()

Create a welcome message for a domain



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
	createDomainWelcomeMessageBody := *openapiclient.NewCreateDomainWelcomeMessageBody("Message_example") // CreateDomainWelcomeMessageBody | application/json

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainV1API.V1CreateDomainWelcomeMessage(context.Background()).CreateDomainWelcomeMessageBody(createDomainWelcomeMessageBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainV1API.V1CreateDomainWelcomeMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateDomainWelcomeMessage`: DomainWelcomeMessageResponseV1
	fmt.Fprintf(os.Stdout, "Response from `DomainV1API.V1CreateDomainWelcomeMessage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateDomainWelcomeMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDomainWelcomeMessageBody** | [**CreateDomainWelcomeMessageBody**](CreateDomainWelcomeMessageBody.md) | application/json | 

### Return type

[**DomainWelcomeMessageResponseV1**](DomainWelcomeMessageResponseV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteDomainWelcomeMessage

> V1DeleteDomainWelcomeMessage(ctx).Execute()

Delete the welcome message for the authenticated user's domain

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
	r, err := apiClient.DomainV1API.V1DeleteDomainWelcomeMessage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainV1API.V1DeleteDomainWelcomeMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteDomainWelcomeMessageRequest struct via the builder pattern


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


## V1GetDomainWelcomeMessage

> DomainWelcomeMessageResponseV1 V1GetDomainWelcomeMessage(ctx).Execute()

Get the welcome message for the authenticated user's domain



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
	resp, r, err := apiClient.DomainV1API.V1GetDomainWelcomeMessage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainV1API.V1GetDomainWelcomeMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetDomainWelcomeMessage`: DomainWelcomeMessageResponseV1
	fmt.Fprintf(os.Stdout, "Response from `DomainV1API.V1GetDomainWelcomeMessage`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetDomainWelcomeMessageRequest struct via the builder pattern


### Return type

[**DomainWelcomeMessageResponseV1**](DomainWelcomeMessageResponseV1.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UpdateDomainWelcomeMessage

> DomainWelcomeMessageResponseV1 V1UpdateDomainWelcomeMessage(ctx).UpdateDomainWelcomeMessageRequest(updateDomainWelcomeMessageRequest).Execute()

Update a welcome message for a domain



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
	updateDomainWelcomeMessageRequest := *openapiclient.NewUpdateDomainWelcomeMessageRequest() // UpdateDomainWelcomeMessageRequest | application/json

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainV1API.V1UpdateDomainWelcomeMessage(context.Background()).UpdateDomainWelcomeMessageRequest(updateDomainWelcomeMessageRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainV1API.V1UpdateDomainWelcomeMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UpdateDomainWelcomeMessage`: DomainWelcomeMessageResponseV1
	fmt.Fprintf(os.Stdout, "Response from `DomainV1API.V1UpdateDomainWelcomeMessage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1UpdateDomainWelcomeMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateDomainWelcomeMessageRequest** | [**UpdateDomainWelcomeMessageRequest**](UpdateDomainWelcomeMessageRequest.md) | application/json | 

### Return type

[**DomainWelcomeMessageResponseV1**](DomainWelcomeMessageResponseV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

