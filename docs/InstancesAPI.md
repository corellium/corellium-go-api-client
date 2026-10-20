# \InstancesAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3AttachInstanceInterface**](InstancesAPI.md#V3AttachInstanceInterface) | **Post** /v3/instances/{instanceId}/interfaces | Connect an I/O interface
[**V3ClearInstancePanics**](InstancesAPI.md#V3ClearInstancePanics) | **Delete** /v3/instances/{instanceId}/panics | Clear kernel panics
[**V3CreateInstance**](InstancesAPI.md#V3CreateInstance) | **Post** /v3/instances | Create a device
[**V3DeleteInstance**](InstancesAPI.md#V3DeleteInstance) | **Delete** /v3/instances/{instanceId} | Remove Instance
[**V3DetachInstanceInterface**](InstancesAPI.md#V3DetachInstanceInterface) | **Delete** /v3/instances/{instanceId}/interfaces/{interfaceId} | Disconnect an I/O interface
[**V3DisableExposePort**](InstancesAPI.md#V3DisableExposePort) | **Post** /v3/instances/{instanceId}/exposeport/disable | Stop exposing the device port
[**V3DownloadNetdumpPcap**](InstancesAPI.md#V3DownloadNetdumpPcap) | **Get** /v3/instances/{instanceId}/netdump.pcap | Download the Enhanced Network Monitor capture
[**V3DownloadNetworkMonitorPcap**](InstancesAPI.md#V3DownloadNetworkMonitorPcap) | **Get** /v3/instances/{instanceId}/networkMonitor.pcap | Download the Network Monitor capture
[**V3EnableExposePort**](InstancesAPI.md#V3EnableExposePort) | **Post** /v3/instances/{instanceId}/exposeport/enable | Expose the device port
[**V3GetInstance**](InstancesAPI.md#V3GetInstance) | **Get** /v3/instances/{instanceId} | Get a device
[**V3GetInstanceConsole**](InstancesAPI.md#V3GetInstanceConsole) | **Get** /v3/instances/{instanceId}/console | Get console websocket URL
[**V3GetInstanceConsoleLog**](InstancesAPI.md#V3GetInstanceConsoleLog) | **Get** /v3/instances/{instanceId}/consoleLog | Read the console log
[**V3GetInstanceGpios**](InstancesAPI.md#V3GetInstanceGpios) | **Get** /v3/instances/{instanceId}/gpios | Read board LEDs, buttons and switches
[**V3GetInstanceImageUpload**](InstancesAPI.md#V3GetInstanceImageUpload) | **Get** /v3/instances/{instance}/image-upload/{type}/{imageId}/{name} | Get image upload status
[**V3GetInstancePanics**](InstancesAPI.md#V3GetInstancePanics) | **Get** /v3/instances/{instanceId}/panics | List kernel panics
[**V3GetInstancePeripherals**](InstancesAPI.md#V3GetInstancePeripherals) | **Get** /v3/instances/{instanceId}/peripherals | Read simulated sensors
[**V3GetInstanceQuickConnectCommand**](InstancesAPI.md#V3GetInstanceQuickConnectCommand) | **Get** /v3/instances/{instanceId}/quickConnectCommand | Get the SSH quick-connect command
[**V3GetInstanceScreenshot**](InstancesAPI.md#V3GetInstanceScreenshot) | **Get** /v3/instances/{instanceId}/screenshot.{format} | Take a screenshot
[**V3GetInstanceState**](InstancesAPI.md#V3GetInstanceState) | **Get** /v3/instances/{instanceId}/state | Get a device&#39;s state
[**V3InjectMessage**](InstancesAPI.md#V3InjectMessage) | **Post** /v3/instances/{instanceId}/message | Send an SMS message to an iOS device
[**V3KernelPreauthorize**](InstancesAPI.md#V3KernelPreauthorize) | **Get** /v3/instances/{instanceId}/kernel-authorize | Get a kernel download token
[**V3ListInstances**](InstancesAPI.md#V3ListInstances) | **Get** /v3/instances | List Instances
[**V3MediaPlay**](InstancesAPI.md#V3MediaPlay) | **Post** /v3/instances/{instanceId}/media/play | Play a video or audio file into the device
[**V3MediaStop**](InstancesAPI.md#V3MediaStop) | **Post** /v3/instances/{instanceId}/media/stop | Stop playing media
[**V3PatchInstance**](InstancesAPI.md#V3PatchInstance) | **Patch** /v3/instances/{instanceId} | Change device settings
[**V3PatchInstanceReadOnly**](InstancesAPI.md#V3PatchInstanceReadOnly) | **Patch** /v3/instances/{instanceId}/read-only | Update Instance Read Only
[**V3PauseInstance**](InstancesAPI.md#V3PauseInstance) | **Post** /v3/instances/{instanceId}/pause | Pause a device
[**V3PostInstanceInput**](InstancesAPI.md#V3PostInstanceInput) | **Post** /v3/instances/{instanceId}/input | Provide Instance Input
[**V3PutInstanceImageUpload**](InstancesAPI.md#V3PutInstanceImageUpload) | **Put** /v3/instances/{instance}/image-upload/{type}/{imageId}/{name} | Upload image chunk
[**V3RebootInstance**](InstancesAPI.md#V3RebootInstance) | **Post** /v3/instances/{instanceId}/reboot | Restart a device
[**V3RestoreBackup**](InstancesAPI.md#V3RestoreBackup) | **Post** /v3/instances/{instanceId}/restoreBackup | Restore a backup onto a device
[**V3RotateInstance**](InstancesAPI.md#V3RotateInstance) | **Post** /v3/instances/{instanceId}/rotate | Rotate the device
[**V3SetInstanceGpios**](InstancesAPI.md#V3SetInstanceGpios) | **Put** /v3/instances/{instanceId}/gpios | Press board buttons or flip switches
[**V3SetInstancePeripherals**](InstancesAPI.md#V3SetInstancePeripherals) | **Put** /v3/instances/{instanceId}/peripherals | Change simulated sensors
[**V3StartInstance**](InstancesAPI.md#V3StartInstance) | **Post** /v3/instances/{instanceId}/start | Turn a device on
[**V3StartNetdump**](InstancesAPI.md#V3StartNetdump) | **Post** /v3/instances/{instanceId}/netdump/enable | Start Enhanced Network Monitor
[**V3StartNetworkMonitor**](InstancesAPI.md#V3StartNetworkMonitor) | **Post** /v3/instances/{instanceId}/sslsplit/enable | Start Network Monitor
[**V3StopInstance**](InstancesAPI.md#V3StopInstance) | **Post** /v3/instances/{instanceId}/stop | Turn a device off
[**V3StopNetdump**](InstancesAPI.md#V3StopNetdump) | **Post** /v3/instances/{instanceId}/netdump/disable | Stop Enhanced Network Monitor
[**V3StopNetworkMonitor**](InstancesAPI.md#V3StopNetworkMonitor) | **Post** /v3/instances/{instanceId}/sslsplit/disable | Stop Network Monitor
[**V3UnpauseInstance**](InstancesAPI.md#V3UnpauseInstance) | **Post** /v3/instances/{instanceId}/unpause | Resume a paused device
[**V3UpgradeInstance**](InstancesAPI.md#V3UpgradeInstance) | **Post** /v3/instances/{instanceId}/upgrade | Upgrade the iOS version
[**V3ValidateInstanceToken**](InstancesAPI.md#V3ValidateInstanceToken) | **Post** /v3/instances/{instanceId}/token/validate | Check a device connection token



## V3AttachInstanceInterface

> V3AttachInstanceInterface(ctx, instanceId).AttachInterfaceBody(attachInterfaceBody).Execute()

Connect an I/O interface



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
	attachInterfaceBody := *openapiclient.NewAttachInterfaceBody("gpio/0", "56494514-33f7-4fc2-9fdc-865e3957e6d3") // AttachInterfaceBody | Interface attachment request.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3AttachInstanceInterface(context.Background(), instanceId).AttachInterfaceBody(attachInterfaceBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3AttachInstanceInterface``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3AttachInstanceInterfaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **attachInterfaceBody** | [**AttachInterfaceBody**](AttachInterfaceBody.md) | Interface attachment request. | 

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


## V3ClearInstancePanics

> V3ClearInstancePanics(ctx, instanceId).Execute()

Clear kernel panics



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
	r, err := apiClient.InstancesAPI.V3ClearInstancePanics(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3ClearInstancePanics``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3ClearInstancePanicsRequest struct via the builder pattern


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


## V3CreateInstance

> CreateInstanceResponse V3CreateInstance(ctx).CreateInstanceBody(createInstanceBody).Execute()

Create a device



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
	createInstanceBody := *openapiclient.NewCreateInstanceBody("1c41b1bc-4f53-48a8-b690-ad30611e1960") // CreateInstanceBody | The VM definition to create.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3CreateInstance(context.Background()).CreateInstanceBody(createInstanceBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3CreateInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateInstance`: CreateInstanceResponse
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3CreateInstance`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createInstanceBody** | [**CreateInstanceBody**](CreateInstanceBody.md) | The VM definition to create. | 

### Return type

[**CreateInstanceResponse**](CreateInstanceResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteInstance

> V3DeleteInstance(ctx, instanceId).Execute()

Remove Instance



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
	r, err := apiClient.InstancesAPI.V3DeleteInstance(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3DeleteInstance``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3DeleteInstanceRequest struct via the builder pattern


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


## V3DetachInstanceInterface

> V3DetachInstanceInterface(ctx, instanceId, interfaceId).DetachInterfaceBody(detachInterfaceBody).Execute()

Disconnect an I/O interface



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
	interfaceId := "gpio/0" // string | Interface ID.
	detachInterfaceBody := *openapiclient.NewDetachInterfaceBody("56494514-33f7-4fc2-9fdc-865e3957e6d3") // DetachInterfaceBody | Interface detachment request.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3DetachInstanceInterface(context.Background(), instanceId, interfaceId).DetachInterfaceBody(detachInterfaceBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3DetachInstanceInterface``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**interfaceId** | **string** | Interface ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DetachInstanceInterfaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **detachInterfaceBody** | [**DetachInterfaceBody**](DetachInterfaceBody.md) | Interface detachment request. | 

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


## V3DisableExposePort

> V3DisableExposePort(ctx, instanceId).Execute()

Stop exposing the device port



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
	r, err := apiClient.InstancesAPI.V3DisableExposePort(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3DisableExposePort``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3DisableExposePortRequest struct via the builder pattern


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


## V3DownloadNetdumpPcap

> *os.File V3DownloadNetdumpPcap(ctx, instanceId).Execute()

Download the Enhanced Network Monitor capture



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
	resp, r, err := apiClient.InstancesAPI.V3DownloadNetdumpPcap(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3DownloadNetdumpPcap``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3DownloadNetdumpPcap`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3DownloadNetdumpPcap`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DownloadNetdumpPcapRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[***os.File**](*os.File.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/vnd.tcpdump.pcap, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DownloadNetworkMonitorPcap

> *os.File V3DownloadNetworkMonitorPcap(ctx, instanceId).Execute()

Download the Network Monitor capture



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
	resp, r, err := apiClient.InstancesAPI.V3DownloadNetworkMonitorPcap(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3DownloadNetworkMonitorPcap``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3DownloadNetworkMonitorPcap`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3DownloadNetworkMonitorPcap`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DownloadNetworkMonitorPcapRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[***os.File**](*os.File.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/vnd.tcpdump.pcap, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3EnableExposePort

> V3EnableExposePort(ctx, instanceId).Execute()

Expose the device port



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
	r, err := apiClient.InstancesAPI.V3EnableExposePort(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3EnableExposePort``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3EnableExposePortRequest struct via the builder pattern


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


## V3GetInstance

> Instance V3GetInstance(ctx, instanceId).ReturnAttr(returnAttr).Execute()

Get a device



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
	returnAttr := []string{"Inner_example"} // []string | Attributes to include in instance return. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3GetInstance(context.Background(), instanceId).ReturnAttr(returnAttr).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstance`: Instance
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstance`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **returnAttr** | **[]string** | Attributes to include in instance return. | 

### Return type

[**Instance**](Instance.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInstanceConsole

> InstanceConsoleEndpoint V3GetInstanceConsole(ctx, instanceId).Type_(type_).Execute()

Get console websocket URL



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
	type_ := "uart7-cons" // string | Console to connect to: a `consoles[].id` from Get Instance with the `port-` prefix removed. Defaults to `cons`. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3GetInstanceConsole(context.Background(), instanceId).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstanceConsole``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstanceConsole`: InstanceConsoleEndpoint
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstanceConsole`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstanceConsoleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **type_** | **string** | Console to connect to: a &#x60;consoles[].id&#x60; from Get Instance with the &#x60;port-&#x60; prefix removed. Defaults to &#x60;cons&#x60;. | 

### Return type

[**InstanceConsoleEndpoint**](InstanceConsoleEndpoint.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInstanceConsoleLog

> string V3GetInstanceConsoleLog(ctx, instanceId).Execute()

Read the console log



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
	resp, r, err := apiClient.InstancesAPI.V3GetInstanceConsoleLog(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstanceConsoleLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstanceConsoleLog`: string
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstanceConsoleLog`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstanceConsoleLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInstanceGpios

> GpiosState V3GetInstanceGpios(ctx, instanceId).Execute()

Read board LEDs, buttons and switches



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
	resp, r, err := apiClient.InstancesAPI.V3GetInstanceGpios(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstanceGpios``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstanceGpios`: GpiosState
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstanceGpios`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstanceGpiosRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GpiosState**](GpiosState.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInstanceImageUpload

> *os.File V3GetInstanceImageUpload(ctx, instance, type_, imageId, name).ResumableChunkNumber(resumableChunkNumber).Execute()

Get image upload status



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
	instance := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	type_ := "type__example" // string | What kind of file this is, for example `fw` for firmware or `kernel`. Uses the same values as `type` on `POST /v3/images`; see `ImageType` for what each means. Types that need a license feature your license lacks are rejected with 403.
	imageId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload.
	name := "name_example" // string | The file name to store, URL-encoded (for example `my%20firmware.ipsw`). Becomes the image `name`.
	resumableChunkNumber := float32(56) // float32 | Chunk number. When present the response reports whether that chunk was already stored (200) or still needs to be uploaded (204) instead of returning the image file. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3GetInstanceImageUpload(context.Background(), instance, type_, imageId, name).ResumableChunkNumber(resumableChunkNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstanceImageUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstanceImageUpload`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstanceImageUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instance** | **string** | Instance ID. | 
**type_** | **string** | What kind of file this is, for example &#x60;fw&#x60; for firmware or &#x60;kernel&#x60;. Uses the same values as &#x60;type&#x60; on &#x60;POST /v3/images&#x60;; see &#x60;ImageType&#x60; for what each means. Types that need a license feature your license lacks are rejected with 403. | 
**imageId** | **string** | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload. | 
**name** | **string** | The file name to store, URL-encoded (for example &#x60;my%20firmware.ipsw&#x60;). Becomes the image &#x60;name&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstanceImageUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **resumableChunkNumber** | **float32** | Chunk number. When present the response reports whether that chunk was already stored (200) or still needs to be uploaded (204) instead of returning the image file. | 

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


## V3GetInstancePanics

> []map[string]interface{} V3GetInstancePanics(ctx, instanceId).Execute()

List kernel panics



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
	resp, r, err := apiClient.InstancesAPI.V3GetInstancePanics(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstancePanics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstancePanics`: []map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstancePanics`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstancePanicsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]map[string]interface{}**](map.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInstancePeripherals

> PeripheralsData V3GetInstancePeripherals(ctx, instanceId).Execute()

Read simulated sensors



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
	resp, r, err := apiClient.InstancesAPI.V3GetInstancePeripherals(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstancePeripherals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstancePeripherals`: PeripheralsData
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstancePeripherals`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstancePeripheralsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PeripheralsData**](PeripheralsData.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInstanceQuickConnectCommand

> string V3GetInstanceQuickConnectCommand(ctx, instanceId).Execute()

Get the SSH quick-connect command



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
	resp, r, err := apiClient.InstancesAPI.V3GetInstanceQuickConnectCommand(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstanceQuickConnectCommand``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstanceQuickConnectCommand`: string
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstanceQuickConnectCommand`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstanceQuickConnectCommandRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInstanceScreenshot

> *os.File V3GetInstanceScreenshot(ctx, instanceId, format).Scale(scale).Execute()

Take a screenshot



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
	format := "format_example" // string | Image file type: `png` (lossless, larger) or `jpeg` (smaller).
	scale := float32(2) // float32 | Shrink factor. The image is 1/N of full size in each direction. Whole number; defaults to 1 (full size). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3GetInstanceScreenshot(context.Background(), instanceId, format).Scale(scale).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstanceScreenshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstanceScreenshot`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstanceScreenshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 
**format** | **string** | Image file type: &#x60;png&#x60; (lossless, larger) or &#x60;jpeg&#x60; (smaller). | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstanceScreenshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **scale** | **float32** | Shrink factor. The image is 1/N of full size in each direction. Whole number; defaults to 1 (full size). | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: image/png, image/jpeg, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInstanceState

> InstanceState V3GetInstanceState(ctx, instanceId).ReturnAttr(returnAttr).Execute()

Get a device's state



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
	returnAttr := []string{"Inner_example"} // []string | The attributes to return. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3GetInstanceState(context.Background(), instanceId).ReturnAttr(returnAttr).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3GetInstanceState``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInstanceState`: InstanceState
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3GetInstanceState`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInstanceStateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **returnAttr** | **[]string** | The attributes to return. | 

### Return type

[**InstanceState**](InstanceState.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3InjectMessage

> V3InjectMessage(ctx, instanceId).MessageBody(messageBody).Execute()

Send an SMS message to an iOS device



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
	messageBody := *openapiclient.NewMessageBody("+15555550123", "Hello from Corellium!", "deadbeef") // MessageBody | Message data.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3InjectMessage(context.Background(), instanceId).MessageBody(messageBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3InjectMessage``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3InjectMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **messageBody** | [**MessageBody**](MessageBody.md) | Message data. | 

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


## V3KernelPreauthorize

> Token V3KernelPreauthorize(ctx, instanceId).Execute()

Get a kernel download token



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
	resp, r, err := apiClient.InstancesAPI.V3KernelPreauthorize(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3KernelPreauthorize``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3KernelPreauthorize`: Token
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3KernelPreauthorize`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3KernelPreauthorizeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Token**](Token.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListInstances

> InstanceList V3ListInstances(ctx).Limit(limit).Offset(offset).Name(name).ReturnAttr(returnAttr).Execute()

List Instances



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
	name := "My iPhone 13 Pro" // string | Optionally filter by instance name. (optional)
	returnAttr := []string{"Inner_example"} // []string | Attributes to include in instance return. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3ListInstances(context.Background()).Limit(limit).Offset(offset).Name(name).ReturnAttr(returnAttr).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3ListInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListInstances`: InstanceList
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3ListInstances`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]
 **name** | **string** | Optionally filter by instance name. | 
 **returnAttr** | **[]string** | Attributes to include in instance return. | 

### Return type

[**InstanceList**](InstanceList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3MediaPlay

> V3MediaPlay(ctx, instanceId).MediaPlayBody(mediaPlayBody).Execute()

Play a video or audio file into the device



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
	mediaPlayBody := openapiclient.MediaPlayBody{MediaPlayByImage: openapiclient.NewMediaPlayByImage("3e1354a3-fb10-46c0-8b05-56e28edbde69")} // MediaPlayBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3MediaPlay(context.Background(), instanceId).MediaPlayBody(mediaPlayBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3MediaPlay``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3MediaPlayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mediaPlayBody** | [**MediaPlayBody**](MediaPlayBody.md) |  | 

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


## V3MediaStop

> V3MediaStop(ctx, instanceId).Execute()

Stop playing media



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
	r, err := apiClient.InstancesAPI.V3MediaStop(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3MediaStop``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3MediaStopRequest struct via the builder pattern


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


## V3PatchInstance

> Instance V3PatchInstance(ctx, instanceId).PatchInstanceBody(patchInstanceBody).Execute()

Change device settings



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
	patchInstanceBody := *openapiclient.NewPatchInstanceBody() // PatchInstanceBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3PatchInstance(context.Background(), instanceId).PatchInstanceBody(patchInstanceBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3PatchInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PatchInstance`: Instance
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3PatchInstance`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchInstanceBody** | [**PatchInstanceBody**](PatchInstanceBody.md) |  | 

### Return type

[**Instance**](Instance.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchInstanceReadOnly

> Instance V3PatchInstanceReadOnly(ctx, instanceId).PatchInstanceReadOnlyBody(patchInstanceReadOnlyBody).Execute()

Update Instance Read Only



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
	patchInstanceReadOnlyBody := *openapiclient.NewPatchInstanceReadOnlyBody(true) // PatchInstanceReadOnlyBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3PatchInstanceReadOnly(context.Background(), instanceId).PatchInstanceReadOnlyBody(patchInstanceReadOnlyBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3PatchInstanceReadOnly``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PatchInstanceReadOnly`: Instance
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3PatchInstanceReadOnly`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchInstanceReadOnlyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchInstanceReadOnlyBody** | [**PatchInstanceReadOnlyBody**](PatchInstanceReadOnlyBody.md) |  | 

### Return type

[**Instance**](Instance.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PauseInstance

> V3PauseInstance(ctx, instanceId).Execute()

Pause a device



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
	r, err := apiClient.InstancesAPI.V3PauseInstance(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3PauseInstance``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3PauseInstanceRequest struct via the builder pattern


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


## V3PostInstanceInput

> InputResponse V3PostInstanceInput(ctx, instanceId).InstanceInputBody(instanceInputBody).Execute()

Provide Instance Input



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
	instanceInputBody := []openapiclient.InstanceInputBody{*openapiclient.NewInstanceInputBody([][]float32{[]float32{float32(123)}}, [][]float32{[]float32{float32(123)}}, []string{"StartButtons_example"}, float32(250), "Hello, world!")} // []InstanceInputBody | Array of input events to send to the VM.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3PostInstanceInput(context.Background(), instanceId).InstanceInputBody(instanceInputBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3PostInstanceInput``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PostInstanceInput`: InputResponse
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3PostInstanceInput`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PostInstanceInputRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **instanceInputBody** | [**[]InstanceInputBody**](InstanceInputBody.md) | Array of input events to send to the VM. | 

### Return type

[**InputResponse**](InputResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PutInstanceImageUpload

> map[string]interface{} V3PutInstanceImageUpload(ctx, instance, type_, imageId, name).Body(body).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).ResumableTotalSize(resumableTotalSize).ResumableTotalChunks(resumableTotalChunks).CorelliumChecksum(corelliumChecksum).Flavor(flavor).XCorelliumImageEncoding(xCorelliumImageEncoding).XCorelliumImageEncapsulated(xCorelliumImageEncapsulated).XCorelliumTotalFileSize(xCorelliumTotalFileSize).XCorelliumImagePassword(xCorelliumImagePassword).Execute()

Upload image chunk



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
	instance := "f7f9832a-f824-416f-a5ea-4adfe34754b5" // string | Instance ID.
	type_ := "type__example" // string | What kind of file this is, for example `fw` for firmware or `kernel`. Uses the same values as `type` on `POST /v3/images`; see `ImageType` for what each means. Types that need a license feature your license lacks are rejected with 403.
	imageId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload.
	name := "name_example" // string | The file name to store, URL-encoded (for example `my%20firmware.ipsw`). Becomes the image `name`.
	body := os.NewFile(1234, "some_file") // *os.File | 
	resumableChunkNumber := float32(56) // float32 | Which chunk this is, counting from 1. (optional)
	resumableChunkSize := float32(56) // float32 | The size, in bytes, you split the file into. Use the same value for every chunk; only the last chunk may be smaller. If you send `corelliumChecksum`, this must equal the block size inside it. (optional)
	resumableCurrentChunkSize := float32(56) // float32 | Actual size in bytes of this chunk's body. (optional)
	resumableTotalSize := float32(56) // float32 | Size of the whole file in bytes. (optional)
	resumableTotalChunks := float32(56) // float32 | How many chunks the whole file is split into. The upload completes when the last one arrives. (optional)
	corelliumChecksum := "corelliumChecksum_example" // string | Optional expected checksum of the whole file, formatted `algorithm$blockSize$hash`. When given, the finished upload is checked and rejected (and the image removed) if it does not match. Required for firmware (`fw`) uploads on air-gapped deployments. (optional)
	flavor := "flavor_example" // string | Device model (`flavor` from `GET /v3/models`) the image is for. Needed for `partition` uploads when the image is not attached to a device, so the partition name can be checked against that model. (optional)
	xCorelliumImageEncoding := "xCorelliumImageEncoding_example" // string | How the file is stored: `plain` (normal) or `encrypted`. Only read on the first chunk, when the image record is created; later chunks cannot change it. (optional)
	xCorelliumImageEncapsulated := true // bool | Whether the uploaded file is a ZIP wrapper the platform should unpack. Send false to store the file exactly as uploaded. Only read on the first chunk, when the image record is created. (optional)
	xCorelliumTotalFileSize := float32(56) // float32 | Size of the whole file in bytes. Send it on every chunk: the platform uses it to check up front that there is room for the entire file, and answers 507 if there is not, before storing any data. (optional)
	xCorelliumImagePassword := "xCorelliumImagePassword_example" // string | Password of a password-protected file (for example encrypted firmware), used to check the file after upload. Leave out for normal files. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3PutInstanceImageUpload(context.Background(), instance, type_, imageId, name).Body(body).ResumableChunkNumber(resumableChunkNumber).ResumableChunkSize(resumableChunkSize).ResumableCurrentChunkSize(resumableCurrentChunkSize).ResumableTotalSize(resumableTotalSize).ResumableTotalChunks(resumableTotalChunks).CorelliumChecksum(corelliumChecksum).Flavor(flavor).XCorelliumImageEncoding(xCorelliumImageEncoding).XCorelliumImageEncapsulated(xCorelliumImageEncapsulated).XCorelliumTotalFileSize(xCorelliumTotalFileSize).XCorelliumImagePassword(xCorelliumImagePassword).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3PutInstanceImageUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PutInstanceImageUpload`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3PutInstanceImageUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instance** | **string** | Instance ID. | 
**type_** | **string** | What kind of file this is, for example &#x60;fw&#x60; for firmware or &#x60;kernel&#x60;. Uses the same values as &#x60;type&#x60; on &#x60;POST /v3/images&#x60;; see &#x60;ImageType&#x60; for what each means. Types that need a license feature your license lacks are rejected with 403. | 
**imageId** | **string** | An ID you choose for the new image: generate a random UUID once per file and use the same value for every chunk of that file. The image record is created with this ID when the first chunk arrives. Use a new UUID for each new upload. | 
**name** | **string** | The file name to store, URL-encoded (for example &#x60;my%20firmware.ipsw&#x60;). Becomes the image &#x60;name&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PutInstanceImageUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **body** | ***os.File** |  | 
 **resumableChunkNumber** | **float32** | Which chunk this is, counting from 1. | 
 **resumableChunkSize** | **float32** | The size, in bytes, you split the file into. Use the same value for every chunk; only the last chunk may be smaller. If you send &#x60;corelliumChecksum&#x60;, this must equal the block size inside it. | 
 **resumableCurrentChunkSize** | **float32** | Actual size in bytes of this chunk&#39;s body. | 
 **resumableTotalSize** | **float32** | Size of the whole file in bytes. | 
 **resumableTotalChunks** | **float32** | How many chunks the whole file is split into. The upload completes when the last one arrives. | 
 **corelliumChecksum** | **string** | Optional expected checksum of the whole file, formatted &#x60;algorithm$blockSize$hash&#x60;. When given, the finished upload is checked and rejected (and the image removed) if it does not match. Required for firmware (&#x60;fw&#x60;) uploads on air-gapped deployments. | 
 **flavor** | **string** | Device model (&#x60;flavor&#x60; from &#x60;GET /v3/models&#x60;) the image is for. Needed for &#x60;partition&#x60; uploads when the image is not attached to a device, so the partition name can be checked against that model. | 
 **xCorelliumImageEncoding** | **string** | How the file is stored: &#x60;plain&#x60; (normal) or &#x60;encrypted&#x60;. Only read on the first chunk, when the image record is created; later chunks cannot change it. | 
 **xCorelliumImageEncapsulated** | **bool** | Whether the uploaded file is a ZIP wrapper the platform should unpack. Send false to store the file exactly as uploaded. Only read on the first chunk, when the image record is created. | 
 **xCorelliumTotalFileSize** | **float32** | Size of the whole file in bytes. Send it on every chunk: the platform uses it to check up front that there is room for the entire file, and answers 507 if there is not, before storing any data. | 
 **xCorelliumImagePassword** | **string** | Password of a password-protected file (for example encrypted firmware), used to check the file after upload. Leave out for normal files. | 

### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3RebootInstance

> V3RebootInstance(ctx, instanceId).Execute()

Restart a device



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
	r, err := apiClient.InstancesAPI.V3RebootInstance(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3RebootInstance``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3RebootInstanceRequest struct via the builder pattern


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


## V3RestoreBackup

> V3RestoreBackup(ctx, instanceId).RestoreBackupBody(restoreBackupBody).Execute()

Restore a backup onto a device



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
	restoreBackupBody := *openapiclient.NewRestoreBackupBody() // RestoreBackupBody | Restore backup data. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3RestoreBackup(context.Background(), instanceId).RestoreBackupBody(restoreBackupBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3RestoreBackup``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3RestoreBackupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **restoreBackupBody** | [**RestoreBackupBody**](RestoreBackupBody.md) | Restore backup data. | 

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


## V3RotateInstance

> V3RotateInstance(ctx, instanceId).RotateBody(rotateBody).Execute()

Rotate the device



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
	rotateBody := *openapiclient.NewRotateBody(float32(123)) // RotateBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3RotateInstance(context.Background(), instanceId).RotateBody(rotateBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3RotateInstance``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3RotateInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **rotateBody** | [**RotateBody**](RotateBody.md) |  | 

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


## V3SetInstanceGpios

> GpiosState V3SetInstanceGpios(ctx, instanceId).GpiosState(gpiosState).Execute()

Press board buttons or flip switches



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
	gpiosState := *openapiclient.NewGpiosState() // GpiosState | New GPIO state.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3SetInstanceGpios(context.Background(), instanceId).GpiosState(gpiosState).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3SetInstanceGpios``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3SetInstanceGpios`: GpiosState
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3SetInstanceGpios`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3SetInstanceGpiosRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **gpiosState** | [**GpiosState**](GpiosState.md) | New GPIO state. | 

### Return type

[**GpiosState**](GpiosState.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3SetInstancePeripherals

> PeripheralsData V3SetInstancePeripherals(ctx, instanceId).PeripheralsData(peripheralsData).Execute()

Change simulated sensors



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
	peripheralsData := *openapiclient.NewPeripheralsData() // PeripheralsData | New peripherals state.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3SetInstancePeripherals(context.Background(), instanceId).PeripheralsData(peripheralsData).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3SetInstancePeripherals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3SetInstancePeripherals`: PeripheralsData
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3SetInstancePeripherals`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3SetInstancePeripheralsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **peripheralsData** | [**PeripheralsData**](PeripheralsData.md) | New peripherals state. | 

### Return type

[**PeripheralsData**](PeripheralsData.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3StartInstance

> V3StartInstance(ctx, instanceId).StartInstanceBody(startInstanceBody).Execute()

Turn a device on



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
	startInstanceBody := *openapiclient.NewStartInstanceBody() // StartInstanceBody | Start options. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3StartInstance(context.Background(), instanceId).StartInstanceBody(startInstanceBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3StartInstance``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StartInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startInstanceBody** | [**StartInstanceBody**](StartInstanceBody.md) | Start options. | 

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


## V3StartNetdump

> V3StartNetdump(ctx, instanceId).EnableNetdumpBody(enableNetdumpBody).Execute()

Start Enhanced Network Monitor



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
	enableNetdumpBody := *openapiclient.NewEnableNetdumpBody() // EnableNetdumpBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3StartNetdump(context.Background(), instanceId).EnableNetdumpBody(enableNetdumpBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3StartNetdump``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StartNetdumpRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **enableNetdumpBody** | [**EnableNetdumpBody**](EnableNetdumpBody.md) |  | 

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


## V3StartNetworkMonitor

> V3StartNetworkMonitor(ctx, instanceId).EnableSslsplitBody(enableSslsplitBody).Execute()

Start Network Monitor



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
	enableSslsplitBody := *openapiclient.NewEnableSslsplitBody() // EnableSslsplitBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3StartNetworkMonitor(context.Background(), instanceId).EnableSslsplitBody(enableSslsplitBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3StartNetworkMonitor``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StartNetworkMonitorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **enableSslsplitBody** | [**EnableSslsplitBody**](EnableSslsplitBody.md) |  | 

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


## V3StopInstance

> V3StopInstance(ctx, instanceId).StopInstanceBody(stopInstanceBody).Execute()

Turn a device off



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
	stopInstanceBody := *openapiclient.NewStopInstanceBody() // StopInstanceBody | Stop options. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3StopInstance(context.Background(), instanceId).StopInstanceBody(stopInstanceBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3StopInstance``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StopInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **stopInstanceBody** | [**StopInstanceBody**](StopInstanceBody.md) | Stop options. | 

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


## V3StopNetdump

> V3StopNetdump(ctx, instanceId).Execute()

Stop Enhanced Network Monitor



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
	r, err := apiClient.InstancesAPI.V3StopNetdump(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3StopNetdump``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StopNetdumpRequest struct via the builder pattern


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


## V3StopNetworkMonitor

> V3StopNetworkMonitor(ctx, instanceId).Execute()

Stop Network Monitor



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
	r, err := apiClient.InstancesAPI.V3StopNetworkMonitor(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3StopNetworkMonitor``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StopNetworkMonitorRequest struct via the builder pattern


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


## V3UnpauseInstance

> V3UnpauseInstance(ctx, instanceId).Execute()

Resume a paused device



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
	r, err := apiClient.InstancesAPI.V3UnpauseInstance(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3UnpauseInstance``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3UnpauseInstanceRequest struct via the builder pattern


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


## V3UpgradeInstance

> InstanceUpgradeResponse V3UpgradeInstance(ctx, instanceId).InstanceUpgradeBody(instanceUpgradeBody).Execute()

Upgrade the iOS version



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
	instanceUpgradeBody := *openapiclient.NewInstanceUpgradeBody("17.5") // InstanceUpgradeBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesAPI.V3UpgradeInstance(context.Background(), instanceId).InstanceUpgradeBody(instanceUpgradeBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3UpgradeInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3UpgradeInstance`: InstanceUpgradeResponse
	fmt.Fprintf(os.Stdout, "Response from `InstancesAPI.V3UpgradeInstance`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3UpgradeInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **instanceUpgradeBody** | [**InstanceUpgradeBody**](InstanceUpgradeBody.md) |  | 

### Return type

[**InstanceUpgradeResponse**](InstanceUpgradeResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ValidateInstanceToken

> V3ValidateInstanceToken(ctx, instanceId).TokenValidateBody(tokenValidateBody).Execute()

Check a device connection token



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
	tokenValidateBody := *openapiclient.NewTokenValidateBody("<redacted>") // TokenValidateBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesAPI.V3ValidateInstanceToken(context.Background(), instanceId).TokenValidateBody(tokenValidateBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesAPI.V3ValidateInstanceToken``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3ValidateInstanceTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **tokenValidateBody** | [**TokenValidateBody**](TokenValidateBody.md) |  | 

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

