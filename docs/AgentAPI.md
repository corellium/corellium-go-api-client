# \AgentAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3DeleteFileAgent**](AgentAPI.md#V3DeleteFileAgent) | **Delete** /v3/instances/{instanceId}/agent/v1/file/device/{filePath} | Delete a file on VM
[**V3GetAdbAuthAgent**](AgentAPI.md#V3GetAdbAuthAgent) | **Get** /v3/instances/{instanceId}/agent/v1/system/adbauth | Get ADB auth setting
[**V3GetAppReadyAgent**](AgentAPI.md#V3GetAppReadyAgent) | **Get** /v3/instances/{instanceId}/agent/v1/app/ready | Check if app subsystem is ready
[**V3GetContainerHealthAgent**](AgentAPI.md#V3GetContainerHealthAgent) | **Get** /v3/instances/{instanceId}/agent/v1/container/containers/{containerId}/is-healthy | Get container health
[**V3GetFileAgent**](AgentAPI.md#V3GetFileAgent) | **Get** /v3/instances/{instanceId}/agent/v1/file/device/{filePath} | Download a file from VM
[**V3GetNetworkAgent**](AgentAPI.md#V3GetNetworkAgent) | **Get** /v3/instances/{instanceId}/agent/v1/system/network | Get eth0 IP address
[**V3GetPropAgent**](AgentAPI.md#V3GetPropAgent) | **Post** /v3/instances/{instanceId}/agent/v1/system/getprop | Get a system property
[**V3GetRemoteItStatusAgent**](AgentAPI.md#V3GetRemoteItStatusAgent) | **Get** /v3/instances/{instanceId}/agent/v1/remoteit/status | Get Remote.It status
[**V3GetTempFileAgent**](AgentAPI.md#V3GetTempFileAgent) | **Post** /v3/instances/{instanceId}/agent/v1/file/temp | Get a temp file path on VM
[**V3InstallAgent**](AgentAPI.md#V3InstallAgent) | **Post** /v3/instances/{instanceId}/agent/v1/app/install | Install app at path
[**V3InstallOpenGappsAgent**](AgentAPI.md#V3InstallOpenGappsAgent) | **Post** /v3/instances/{instanceId}/agent/v1/system/install-opengapps | Install OpenGApps
[**V3InstallProfileAgent**](AgentAPI.md#V3InstallProfileAgent) | **Post** /v3/instances/{instanceId}/agent/v1/profile/install | Install a profile
[**V3InstallRemoteItAgent**](AgentAPI.md#V3InstallRemoteItAgent) | **Post** /v3/instances/{instanceId}/agent/v1/remoteit/install | Install Remote.It
[**V3KillAppAgent**](AgentAPI.md#V3KillAppAgent) | **Post** /v3/instances/{instanceId}/agent/v1/app/apps/{bundleId}/kill | Kill an app
[**V3KillFridaAgent**](AgentAPI.md#V3KillFridaAgent) | **Post** /v3/instances/{instanceId}/agent/v1/frida/run-frida-kill | Kill Frida
[**V3ListAppIconsAgent**](AgentAPI.md#V3ListAppIconsAgent) | **Get** /v3/instances/{instanceId}/agent/v1/app/icons | List app icons
[**V3ListAppsAgent**](AgentAPI.md#V3ListAppsAgent) | **Get** /v3/instances/{instanceId}/agent/v1/app/apps | List apps
[**V3ListAppsStatusAgent**](AgentAPI.md#V3ListAppsStatusAgent) | **Get** /v3/instances/{instanceId}/agent/v1/app/apps/update | List apps status
[**V3ListContainersAgent**](AgentAPI.md#V3ListContainersAgent) | **Get** /v3/instances/{instanceId}/agent/v1/container/containers | List containers
[**V3ListFridaProcessesAgent**](AgentAPI.md#V3ListFridaProcessesAgent) | **Post** /v3/instances/{instanceId}/agent/v1/frida/run-frida-ps | List Frida processes
[**V3ListProfilesAgent**](AgentAPI.md#V3ListProfilesAgent) | **Get** /v3/instances/{instanceId}/agent/v1/profile/profiles | List profiles
[**V3LockAgent**](AgentAPI.md#V3LockAgent) | **Post** /v3/instances/{instanceId}/agent/v1/system/lock | Lock device
[**V3PreauthorizeFileArchiveDownloadAgent**](AgentAPI.md#V3PreauthorizeFileArchiveDownloadAgent) | **Post** /v3/instances/{instanceId}/agent-authorize/v1/file/download | Pre-authorize an archive download from VM
[**V3PreauthorizeFileDownloadAgent**](AgentAPI.md#V3PreauthorizeFileDownloadAgent) | **Post** /v3/instances/{instanceId}/agent-authorize/v1/file/device/{filePath} | Pre-authorize a file download from VM
[**V3RunAppAgent**](AgentAPI.md#V3RunAppAgent) | **Post** /v3/instances/{instanceId}/agent/v1/app/apps/{bundleId}/run | Run an app
[**V3RunFridaAgent**](AgentAPI.md#V3RunFridaAgent) | **Post** /v3/instances/{instanceId}/agent/v1/frida/run-frida | Run Frida
[**V3SetAdbAuthAgent**](AgentAPI.md#V3SetAdbAuthAgent) | **Put** /v3/instances/{instanceId}/agent/v1/system/adbauth | Set ADB auth setting
[**V3SetDevicePropertiesAgent**](AgentAPI.md#V3SetDevicePropertiesAgent) | **Post** /v3/instances/{instanceId}/agent/v1/system/setDeviceProperties | Set device properties
[**V3SetFileAttributesAgent**](AgentAPI.md#V3SetFileAttributesAgent) | **Patch** /v3/instances/{instanceId}/agent/v1/file/device/{filePath} | Change attributes of a file on VM
[**V3SetHostnameAgent**](AgentAPI.md#V3SetHostnameAgent) | **Post** /v3/instances/{instanceId}/agent/v1/system/setHostname | Set instance hostname
[**V3ShutdownAgent**](AgentAPI.md#V3ShutdownAgent) | **Post** /v3/instances/{instanceId}/agent/v1/system/shutdown | Shut down instance
[**V3StartContainerAgent**](AgentAPI.md#V3StartContainerAgent) | **Post** /v3/instances/{instanceId}/agent/v1/container/containers/{containerId}/start | Start a container
[**V3StartContainerAppAgent**](AgentAPI.md#V3StartContainerAppAgent) | **Post** /v3/instances/{instanceId}/agent/v1/container/containers/{containerId}/start-application/{packageName}/{activityName} | Start an app in a container
[**V3StartContainerAppMonitoredAgent**](AgentAPI.md#V3StartContainerAppMonitoredAgent) | **Post** /v3/instances/{instanceId}/agent/v1/container/containers/{containerId}/start-application-and-monitor/{packageName}/{activityName} | Start and monitor an app in a container
[**V3StopContainerAgent**](AgentAPI.md#V3StopContainerAgent) | **Post** /v3/instances/{instanceId}/agent/v1/container/containers/{containerId}/stop | Stop a container
[**V3StopContainerAppAgent**](AgentAPI.md#V3StopContainerAppAgent) | **Post** /v3/instances/{instanceId}/agent/v1/container/containers/{containerId}/stop-application-if-monitored | Stop a monitored app in a container
[**V3UninstallAppAgent**](AgentAPI.md#V3UninstallAppAgent) | **Post** /v3/instances/{instanceId}/agent/v1/app/apps/{bundleId}/uninstall | Uninstall an app
[**V3UninstallProfileAgent**](AgentAPI.md#V3UninstallProfileAgent) | **Delete** /v3/instances/{instanceId}/agent/v1/profile/profiles/{profileId} | Uninstall a profile
[**V3UninstallRemoteItAgent**](AgentAPI.md#V3UninstallRemoteItAgent) | **Post** /v3/instances/{instanceId}/agent/v1/remoteit/uninstall | Uninstall Remote.It
[**V3UnlockAgent**](AgentAPI.md#V3UnlockAgent) | **Post** /v3/instances/{instanceId}/agent/v1/system/unlock | Unlock device
[**V3UploadFileAgent**](AgentAPI.md#V3UploadFileAgent) | **Put** /v3/instances/{instanceId}/agent/v1/file/device/{filePath} | Upload a file to VM



## V3DeleteFileAgent

> V3DeleteFileAgent(ctx, instanceId, filePath).Execute()

Delete a file on VM



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	filePath := "/var/tmp/agent.log" // string | Path to the file on the VM filesystem.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3DeleteFileAgent(context.Background(), instanceId, filePath).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3DeleteFileAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**filePath** | **string** | Path to the file on the VM filesystem. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteFileAgentRequest struct via the builder pattern


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


## V3GetAdbAuthAgent

> AgentSystemAdbAuth V3GetAdbAuthAgent(ctx, instanceId).Execute()

Get ADB auth setting



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3GetAdbAuthAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3GetAdbAuthAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetAdbAuthAgent`: AgentSystemAdbAuth
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3GetAdbAuthAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetAdbAuthAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentSystemAdbAuth**](AgentSystemAdbAuth.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetAppReadyAgent

> AgentAppReadyResponse V3GetAppReadyAgent(ctx, instanceId).Execute()

Check if app subsystem is ready



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3GetAppReadyAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3GetAppReadyAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetAppReadyAgent`: AgentAppReadyResponse
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3GetAppReadyAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetAppReadyAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentAppReadyResponse**](AgentAppReadyResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetContainerHealthAgent

> AgentContainerHealth V3GetContainerHealthAgent(ctx, instanceId, containerId).Execute()

Get container health



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	containerId := "1" // string | Container identifier (the numeric suffix of the container name, e.g. \"1\" for container1).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3GetContainerHealthAgent(context.Background(), instanceId, containerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3GetContainerHealthAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetContainerHealthAgent`: AgentContainerHealth
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3GetContainerHealthAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**containerId** | **string** | Container identifier (the numeric suffix of the container name, e.g. \&quot;1\&quot; for container1). | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetContainerHealthAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**AgentContainerHealth**](AgentContainerHealth.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetFileAgent

> *os.File V3GetFileAgent(ctx, instanceId, filePath).Execute()

Download a file from VM



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	filePath := "/var/tmp/agent.log" // string | Path to the file on the VM filesystem.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3GetFileAgent(context.Background(), instanceId, filePath).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3GetFileAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetFileAgent`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3GetFileAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**filePath** | **string** | Path to the file on the VM filesystem. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetFileAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[***os.File**](*os.File.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetNetworkAgent

> AgentSystemNetworkResponse V3GetNetworkAgent(ctx, instanceId).Execute()

Get eth0 IP address



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3GetNetworkAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3GetNetworkAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetNetworkAgent`: AgentSystemNetworkResponse
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3GetNetworkAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetNetworkAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentSystemNetworkResponse**](AgentSystemNetworkResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetPropAgent

> AgentSystemGetPropResponse V3GetPropAgent(ctx, instanceId).AgentSystemGetPropBody(agentSystemGetPropBody).Execute()

Get a system property



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	agentSystemGetPropBody := *openapiclient.NewAgentSystemGetPropBody("ro.build.version.sdk") // AgentSystemGetPropBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3GetPropAgent(context.Background(), instanceId).AgentSystemGetPropBody(agentSystemGetPropBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3GetPropAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetPropAgent`: AgentSystemGetPropResponse
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3GetPropAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetPropAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentSystemGetPropBody** | [**AgentSystemGetPropBody**](AgentSystemGetPropBody.md) |  | 

### Return type

[**AgentSystemGetPropResponse**](AgentSystemGetPropResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetRemoteItStatusAgent

> AgentRemoteItStatus V3GetRemoteItStatusAgent(ctx, instanceId).Execute()

Get Remote.It status



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3GetRemoteItStatusAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3GetRemoteItStatusAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetRemoteItStatusAgent`: AgentRemoteItStatus
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3GetRemoteItStatusAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetRemoteItStatusAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentRemoteItStatus**](AgentRemoteItStatus.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetTempFileAgent

> AgentTempFileResponse V3GetTempFileAgent(ctx, instanceId).Execute()

Get a temp file path on VM



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3GetTempFileAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3GetTempFileAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetTempFileAgent`: AgentTempFileResponse
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3GetTempFileAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetTempFileAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentTempFileResponse**](AgentTempFileResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3InstallAgent

> V3InstallAgent(ctx, instanceId).AgentInstallBody(agentInstallBody).Execute()

Install app at path



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	agentInstallBody := *openapiclient.NewAgentInstallBody("/var/tmp/Cafe.ipa") // AgentInstallBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3InstallAgent(context.Background(), instanceId).AgentInstallBody(agentInstallBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3InstallAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3InstallAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentInstallBody** | [**AgentInstallBody**](AgentInstallBody.md) |  | 

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


## V3InstallOpenGappsAgent

> V3InstallOpenGappsAgent(ctx, instanceId).AgentSystemInstallOpenGappsBody(agentSystemInstallOpenGappsBody).Execute()

Install OpenGApps



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	agentSystemInstallOpenGappsBody := *openapiclient.NewAgentSystemInstallOpenGappsBody("http://downloads.sourceforge.net/project/opengapps/arm64/20220119/open_gapps-arm64-11.0-pico-20220119.zip", "58398bf7628f38ef07eaeb3abe26f3ebf0474f4d5ecdac0852bd5de3c15cc828", "google/flame/flame:11/RP1A.200720.009/6720564:user/release-keys__2020-09-05") // AgentSystemInstallOpenGappsBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3InstallOpenGappsAgent(context.Background(), instanceId).AgentSystemInstallOpenGappsBody(agentSystemInstallOpenGappsBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3InstallOpenGappsAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3InstallOpenGappsAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentSystemInstallOpenGappsBody** | [**AgentSystemInstallOpenGappsBody**](AgentSystemInstallOpenGappsBody.md) |  | 

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


## V3InstallProfileAgent

> V3InstallProfileAgent(ctx, instanceId).Body(body).Execute()

Install a profile



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	body := os.NewFile(1234, "some_file") // *os.File | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3InstallProfileAgent(context.Background(), instanceId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3InstallProfileAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3InstallProfileAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | ***os.File** |  | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3InstallRemoteItAgent

> AgentRemoteItStatus V3InstallRemoteItAgent(ctx, instanceId).Execute()

Install Remote.It



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3InstallRemoteItAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3InstallRemoteItAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3InstallRemoteItAgent`: AgentRemoteItStatus
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3InstallRemoteItAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3InstallRemoteItAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentRemoteItStatus**](AgentRemoteItStatus.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3KillAppAgent

> V3KillAppAgent(ctx, instanceId, bundleId).Execute()

Kill an app



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	bundleId := "com.corellium.cafe" // string | App bundle ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3KillAppAgent(context.Background(), instanceId, bundleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3KillAppAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**bundleId** | **string** | App bundle ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3KillAppAgentRequest struct via the builder pattern


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


## V3KillFridaAgent

> AgentFridaResponse V3KillFridaAgent(ctx, instanceId).Execute()

Kill Frida



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3KillFridaAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3KillFridaAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3KillFridaAgent`: AgentFridaResponse
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3KillFridaAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3KillFridaAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentFridaResponse**](AgentFridaResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListAppIconsAgent

> AgentIconsResponse V3ListAppIconsAgent(ctx, instanceId).BundleId(bundleId).Execute()

List app icons



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	bundleId := []string{"Inner_example"} // []string | One or more app bundle IDs to fetch icons for.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3ListAppIconsAgent(context.Background(), instanceId).BundleId(bundleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3ListAppIconsAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListAppIconsAgent`: AgentIconsResponse
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3ListAppIconsAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListAppIconsAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **bundleId** | **[]string** | One or more app bundle IDs to fetch icons for. | 

### Return type

[**AgentIconsResponse**](AgentIconsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListAppsAgent

> AgentAppsList V3ListAppsAgent(ctx, instanceId).LoadIcons(loadIcons).Execute()

List apps



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	loadIcons := "loadIcons_example" // string | Whether to include each app icon in the response. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3ListAppsAgent(context.Background(), instanceId).LoadIcons(loadIcons).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3ListAppsAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListAppsAgent`: AgentAppsList
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3ListAppsAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListAppsAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **loadIcons** | **string** | Whether to include each app icon in the response. | 

### Return type

[**AgentAppsList**](AgentAppsList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListAppsStatusAgent

> AgentAppsStatusList V3ListAppsStatusAgent(ctx, instanceId).Execute()

List apps status



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3ListAppsStatusAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3ListAppsStatusAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListAppsStatusAgent`: AgentAppsStatusList
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3ListAppsStatusAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListAppsStatusAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentAppsStatusList**](AgentAppsStatusList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListContainersAgent

> AgentContainerList V3ListContainersAgent(ctx, instanceId).Execute()

List containers



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3ListContainersAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3ListContainersAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListContainersAgent`: AgentContainerList
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3ListContainersAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListContainersAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentContainerList**](AgentContainerList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListFridaProcessesAgent

> AgentFridaProcessList V3ListFridaProcessesAgent(ctx, instanceId).Execute()

List Frida processes



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3ListFridaProcessesAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3ListFridaProcessesAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListFridaProcessesAgent`: AgentFridaProcessList
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3ListFridaProcessesAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListFridaProcessesAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentFridaProcessList**](AgentFridaProcessList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListProfilesAgent

> AgentProfileListResponse V3ListProfilesAgent(ctx, instanceId).Execute()

List profiles



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3ListProfilesAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3ListProfilesAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListProfilesAgent`: AgentProfileListResponse
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3ListProfilesAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ListProfilesAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentProfileListResponse**](AgentProfileListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3LockAgent

> V3LockAgent(ctx, instanceId).Execute()

Lock device



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3LockAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3LockAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3LockAgentRequest struct via the builder pattern


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


## V3PreauthorizeFileArchiveDownloadAgent

> AgentFileDownloadToken V3PreauthorizeFileArchiveDownloadAgent(ctx, instanceId).AgentFileArchiveDownloadBody(agentFileArchiveDownloadBody).Execute()

Pre-authorize an archive download from VM



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	agentFileArchiveDownloadBody := *openapiclient.NewAgentFileArchiveDownloadBody([]string{"Paths_example"}) // AgentFileArchiveDownloadBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3PreauthorizeFileArchiveDownloadAgent(context.Background(), instanceId).AgentFileArchiveDownloadBody(agentFileArchiveDownloadBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3PreauthorizeFileArchiveDownloadAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PreauthorizeFileArchiveDownloadAgent`: AgentFileDownloadToken
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3PreauthorizeFileArchiveDownloadAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PreauthorizeFileArchiveDownloadAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentFileArchiveDownloadBody** | [**AgentFileArchiveDownloadBody**](AgentFileArchiveDownloadBody.md) |  | 

### Return type

[**AgentFileDownloadToken**](AgentFileDownloadToken.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PreauthorizeFileDownloadAgent

> AgentFileDownloadToken V3PreauthorizeFileDownloadAgent(ctx, instanceId, filePath).Execute()

Pre-authorize a file download from VM



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	filePath := "/var/tmp/agent.log" // string | Path to the file on the VM filesystem.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3PreauthorizeFileDownloadAgent(context.Background(), instanceId, filePath).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3PreauthorizeFileDownloadAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PreauthorizeFileDownloadAgent`: AgentFileDownloadToken
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3PreauthorizeFileDownloadAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**filePath** | **string** | Path to the file on the VM filesystem. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PreauthorizeFileDownloadAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**AgentFileDownloadToken**](AgentFileDownloadToken.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3RunAppAgent

> V3RunAppAgent(ctx, instanceId, bundleId).Execute()

Run an app



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	bundleId := "com.corellium.cafe" // string | App bundle ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3RunAppAgent(context.Background(), instanceId, bundleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3RunAppAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**bundleId** | **string** | App bundle ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RunAppAgentRequest struct via the builder pattern


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


## V3RunFridaAgent

> AgentFridaResponse V3RunFridaAgent(ctx, instanceId).AgentFridaRunBody(agentFridaRunBody).Execute()

Run Frida



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	agentFridaRunBody := *openapiclient.NewAgentFridaRunBody("1234", "com.corellium.cafe") // AgentFridaRunBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3RunFridaAgent(context.Background(), instanceId).AgentFridaRunBody(agentFridaRunBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3RunFridaAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3RunFridaAgent`: AgentFridaResponse
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3RunFridaAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RunFridaAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentFridaRunBody** | [**AgentFridaRunBody**](AgentFridaRunBody.md) |  | 

### Return type

[**AgentFridaResponse**](AgentFridaResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3SetAdbAuthAgent

> V3SetAdbAuthAgent(ctx, instanceId).AgentSystemAdbAuth(agentSystemAdbAuth).Execute()

Set ADB auth setting



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	agentSystemAdbAuth := *openapiclient.NewAgentSystemAdbAuth(true) // AgentSystemAdbAuth | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3SetAdbAuthAgent(context.Background(), instanceId).AgentSystemAdbAuth(agentSystemAdbAuth).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3SetAdbAuthAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3SetAdbAuthAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentSystemAdbAuth** | [**AgentSystemAdbAuth**](AgentSystemAdbAuth.md) |  | 

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


## V3SetDevicePropertiesAgent

> AgentSystemResult V3SetDevicePropertiesAgent(ctx, instanceId).AgentSystemSetDevicePropertiesBody(agentSystemSetDevicePropertiesBody).Execute()

Set device properties



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	agentSystemSetDevicePropertiesBody := *openapiclient.NewAgentSystemSetDevicePropertiesBody() // AgentSystemSetDevicePropertiesBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3SetDevicePropertiesAgent(context.Background(), instanceId).AgentSystemSetDevicePropertiesBody(agentSystemSetDevicePropertiesBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3SetDevicePropertiesAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3SetDevicePropertiesAgent`: AgentSystemResult
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3SetDevicePropertiesAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3SetDevicePropertiesAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentSystemSetDevicePropertiesBody** | [**AgentSystemSetDevicePropertiesBody**](AgentSystemSetDevicePropertiesBody.md) |  | 

### Return type

[**AgentSystemResult**](AgentSystemResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3SetFileAttributesAgent

> V3SetFileAttributesAgent(ctx, instanceId, filePath).AgentFileAttributesBody(agentFileAttributesBody).Execute()

Change attributes of a file on VM



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	filePath := "/var/tmp/agent.log" // string | Path to the file on the VM filesystem.
	agentFileAttributesBody := *openapiclient.NewAgentFileAttributesBody() // AgentFileAttributesBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3SetFileAttributesAgent(context.Background(), instanceId, filePath).AgentFileAttributesBody(agentFileAttributesBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3SetFileAttributesAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**filePath** | **string** | Path to the file on the VM filesystem. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3SetFileAttributesAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **agentFileAttributesBody** | [**AgentFileAttributesBody**](AgentFileAttributesBody.md) |  | 

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


## V3SetHostnameAgent

> AgentSystemResult V3SetHostnameAgent(ctx, instanceId).AgentSystemSetHostnameBody(agentSystemSetHostnameBody).Execute()

Set instance hostname



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	agentSystemSetHostnameBody := *openapiclient.NewAgentSystemSetHostnameBody("corellium-device-01") // AgentSystemSetHostnameBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3SetHostnameAgent(context.Background(), instanceId).AgentSystemSetHostnameBody(agentSystemSetHostnameBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3SetHostnameAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3SetHostnameAgent`: AgentSystemResult
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3SetHostnameAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3SetHostnameAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentSystemSetHostnameBody** | [**AgentSystemSetHostnameBody**](AgentSystemSetHostnameBody.md) |  | 

### Return type

[**AgentSystemResult**](AgentSystemResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ShutdownAgent

> V3ShutdownAgent(ctx, instanceId).Execute()

Shut down instance



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3ShutdownAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3ShutdownAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3ShutdownAgentRequest struct via the builder pattern


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


## V3StartContainerAgent

> V3StartContainerAgent(ctx, instanceId, containerId).Execute()

Start a container



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	containerId := "1" // string | Container identifier (the numeric suffix of the container name, e.g. \"1\" for container1).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3StartContainerAgent(context.Background(), instanceId, containerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3StartContainerAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**containerId** | **string** | Container identifier (the numeric suffix of the container name, e.g. \&quot;1\&quot; for container1). | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3StartContainerAgentRequest struct via the builder pattern


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


## V3StartContainerAppAgent

> V3StartContainerAppAgent(ctx, instanceId, containerId, packageName, activityName).Execute()

Start an app in a container



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	containerId := "1" // string | Container identifier (the numeric suffix of the container name, e.g. \"1\" for container1).
	packageName := "com.corellium.cafe" // string | Android package name of the application.
	activityName := "com.corellium.cafe.MainActivity" // string | Android activity name to launch.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3StartContainerAppAgent(context.Background(), instanceId, containerId, packageName, activityName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3StartContainerAppAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**containerId** | **string** | Container identifier (the numeric suffix of the container name, e.g. \&quot;1\&quot; for container1). | 
**packageName** | **string** | Android package name of the application. | 
**activityName** | **string** | Android activity name to launch. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3StartContainerAppAgentRequest struct via the builder pattern


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


## V3StartContainerAppMonitoredAgent

> V3StartContainerAppMonitoredAgent(ctx, instanceId, containerId, packageName, activityName).Execute()

Start and monitor an app in a container



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	containerId := "1" // string | Container identifier (the numeric suffix of the container name, e.g. \"1\" for container1).
	packageName := "com.corellium.cafe" // string | Android package name of the application.
	activityName := "com.corellium.cafe.MainActivity" // string | Android activity name to launch.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3StartContainerAppMonitoredAgent(context.Background(), instanceId, containerId, packageName, activityName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3StartContainerAppMonitoredAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**containerId** | **string** | Container identifier (the numeric suffix of the container name, e.g. \&quot;1\&quot; for container1). | 
**packageName** | **string** | Android package name of the application. | 
**activityName** | **string** | Android activity name to launch. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3StartContainerAppMonitoredAgentRequest struct via the builder pattern


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


## V3StopContainerAgent

> V3StopContainerAgent(ctx, instanceId, containerId).Execute()

Stop a container



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	containerId := "1" // string | Container identifier (the numeric suffix of the container name, e.g. \"1\" for container1).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3StopContainerAgent(context.Background(), instanceId, containerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3StopContainerAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**containerId** | **string** | Container identifier (the numeric suffix of the container name, e.g. \&quot;1\&quot; for container1). | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3StopContainerAgentRequest struct via the builder pattern


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


## V3StopContainerAppAgent

> V3StopContainerAppAgent(ctx, instanceId, containerId).Execute()

Stop a monitored app in a container



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	containerId := "1" // string | Container identifier (the numeric suffix of the container name, e.g. \"1\" for container1).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3StopContainerAppAgent(context.Background(), instanceId, containerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3StopContainerAppAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**containerId** | **string** | Container identifier (the numeric suffix of the container name, e.g. \&quot;1\&quot; for container1). | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3StopContainerAppAgentRequest struct via the builder pattern


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


## V3UninstallAppAgent

> V3UninstallAppAgent(ctx, instanceId, bundleId).Execute()

Uninstall an app



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	bundleId := "com.corellium.cafe" // string | App bundle ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3UninstallAppAgent(context.Background(), instanceId, bundleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3UninstallAppAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**bundleId** | **string** | App bundle ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UninstallAppAgentRequest struct via the builder pattern


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


## V3UninstallProfileAgent

> V3UninstallProfileAgent(ctx, instanceId, profileId).Execute()

Uninstall a profile



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	profileId := "com.apple.wifi.managed" // string | The profile identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3UninstallProfileAgent(context.Background(), instanceId, profileId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3UninstallProfileAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**profileId** | **string** | The profile identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UninstallProfileAgentRequest struct via the builder pattern


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


## V3UninstallRemoteItAgent

> AgentRemoteItStatus V3UninstallRemoteItAgent(ctx, instanceId).Execute()

Uninstall Remote.It



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentAPI.V3UninstallRemoteItAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3UninstallRemoteItAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3UninstallRemoteItAgent`: AgentRemoteItStatus
	fmt.Fprintf(os.Stdout, "Response from `AgentAPI.V3UninstallRemoteItAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UninstallRemoteItAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentRemoteItStatus**](AgentRemoteItStatus.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3UnlockAgent

> V3UnlockAgent(ctx, instanceId).Execute()

Unlock device



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3UnlockAgent(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3UnlockAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UnlockAgentRequest struct via the builder pattern


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


## V3UploadFileAgent

> V3UploadFileAgent(ctx, instanceId, filePath).Body(body).Execute()

Upload a file to VM



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
	instanceId := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	filePath := "/var/tmp/agent.log" // string | Path to the file on the VM filesystem.
	body := os.NewFile(1234, "some_file") // *os.File | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentAPI.V3UploadFileAgent(context.Background(), instanceId, filePath).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentAPI.V3UploadFileAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**filePath** | **string** | Path to the file on the VM filesystem. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UploadFileAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **body** | ***os.File** |  | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

