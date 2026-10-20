# \ExternalServicesAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteExternalService**](ExternalServicesAPI.md#DeleteExternalService) | **Delete** /{apiVersion}/external-services/{serviceName}/{path} | Proxy a DELETE request to an external service
[**GetExternalService**](ExternalServicesAPI.md#GetExternalService) | **Get** /{apiVersion}/external-services/{serviceName}/{path} | Proxy a GET request to an external service
[**PatchExternalService**](ExternalServicesAPI.md#PatchExternalService) | **Patch** /{apiVersion}/external-services/{serviceName}/{path} | Proxy a PATCH request to an external service
[**PostExternalService**](ExternalServicesAPI.md#PostExternalService) | **Post** /{apiVersion}/external-services/{serviceName}/{path} | Proxy a POST request to an external service
[**PutExternalService**](ExternalServicesAPI.md#PutExternalService) | **Put** /{apiVersion}/external-services/{serviceName}/{path} | Proxy a PUT request to an external service



## DeleteExternalService

> DeleteExternalService(ctx, apiVersion, serviceName, path).Execute()

Proxy a DELETE request to an external service



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
	apiVersion := "v1" // string | API version (e.g. v1, v3).
	serviceName := "apps" // string | Target service name.
	path := "apps/12345/download" // string | The path to call on the external service. Slashes are kept as path separators.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ExternalServicesAPI.DeleteExternalService(context.Background(), apiVersion, serviceName, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalServicesAPI.DeleteExternalService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**apiVersion** | **string** | API version (e.g. v1, v3). | 
**serviceName** | **string** | Target service name. | 
**path** | **string** | The path to call on the external service. Slashes are kept as path separators. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteExternalServiceRequest struct via the builder pattern


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


## GetExternalService

> GetExternalService(ctx, apiVersion, serviceName, path).Execute()

Proxy a GET request to an external service



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
	apiVersion := "v1" // string | API version (e.g. v1, v3).
	serviceName := "apps" // string | Target service name.
	path := "apps/12345/download" // string | The path to call on the external service. Slashes are kept as path separators.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ExternalServicesAPI.GetExternalService(context.Background(), apiVersion, serviceName, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalServicesAPI.GetExternalService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**apiVersion** | **string** | API version (e.g. v1, v3). | 
**serviceName** | **string** | Target service name. | 
**path** | **string** | The path to call on the external service. Slashes are kept as path separators. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetExternalServiceRequest struct via the builder pattern


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


## PatchExternalService

> PatchExternalService(ctx, apiVersion, serviceName, path).Execute()

Proxy a PATCH request to an external service



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
	apiVersion := "v1" // string | API version (e.g. v1, v3).
	serviceName := "apps" // string | Target service name.
	path := "apps/12345/download" // string | The path to call on the external service. Slashes are kept as path separators.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ExternalServicesAPI.PatchExternalService(context.Background(), apiVersion, serviceName, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalServicesAPI.PatchExternalService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**apiVersion** | **string** | API version (e.g. v1, v3). | 
**serviceName** | **string** | Target service name. | 
**path** | **string** | The path to call on the external service. Slashes are kept as path separators. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchExternalServiceRequest struct via the builder pattern


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


## PostExternalService

> PostExternalService(ctx, apiVersion, serviceName, path).Execute()

Proxy a POST request to an external service



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
	apiVersion := "v1" // string | API version (e.g. v1, v3).
	serviceName := "apps" // string | Target service name.
	path := "apps/12345/download" // string | The path to call on the external service. Slashes are kept as path separators.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ExternalServicesAPI.PostExternalService(context.Background(), apiVersion, serviceName, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalServicesAPI.PostExternalService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**apiVersion** | **string** | API version (e.g. v1, v3). | 
**serviceName** | **string** | Target service name. | 
**path** | **string** | The path to call on the external service. Slashes are kept as path separators. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPostExternalServiceRequest struct via the builder pattern


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


## PutExternalService

> PutExternalService(ctx, apiVersion, serviceName, path).Execute()

Proxy a PUT request to an external service



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
	apiVersion := "v1" // string | API version (e.g. v1, v3).
	serviceName := "apps" // string | Target service name.
	path := "apps/12345/download" // string | The path to call on the external service. Slashes are kept as path separators.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ExternalServicesAPI.PutExternalService(context.Background(), apiVersion, serviceName, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalServicesAPI.PutExternalService``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**apiVersion** | **string** | API version (e.g. v1, v3). | 
**serviceName** | **string** | Target service name. | 
**path** | **string** | The path to call on the external service. Slashes are kept as path separators. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPutExternalServiceRequest struct via the builder pattern


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

