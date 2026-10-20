# \ClusterAdministrationConfigAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1GetClusterConfig**](ClusterAdministrationConfigAPI.md#V1GetClusterConfig) | **Get** /v1/cluster/config | Get cluster configuration
[**V1PatchClusterConfig**](ClusterAdministrationConfigAPI.md#V1PatchClusterConfig) | **Patch** /v1/cluster/config | Update cluster configuration



## V1GetClusterConfig

> map[string]interface{} V1GetClusterConfig(ctx).Execute()

Get cluster configuration

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
	resp, r, err := apiClient.ClusterAdministrationConfigAPI.V1GetClusterConfig(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationConfigAPI.V1GetClusterConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetClusterConfig`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ClusterAdministrationConfigAPI.V1GetClusterConfig`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetClusterConfigRequest struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PatchClusterConfig

> V1PatchClusterConfig(ctx).PatchClusterConfigBody(patchClusterConfigBody).Execute()

Update cluster configuration

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
	patchClusterConfigBody := *openapiclient.NewPatchClusterConfigBody() // PatchClusterConfigBody | Cluster Configuration Payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ClusterAdministrationConfigAPI.V1PatchClusterConfig(context.Background()).PatchClusterConfigBody(patchClusterConfigBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClusterAdministrationConfigAPI.V1PatchClusterConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1PatchClusterConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **patchClusterConfigBody** | [**PatchClusterConfigBody**](PatchClusterConfigBody.md) | Cluster Configuration Payload | 

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

