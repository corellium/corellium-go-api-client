# \InstancesV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1AttachInstanceInterface**](InstancesV1API.md#V1AttachInstanceInterface) | **Post** /v1/instances/{instanceId}/interfaces | Attach I/O Interface
[**V1ClearInstancePanics**](InstancesV1API.md#V1ClearInstancePanics) | **Delete** /v1/instances/{instanceId}/panics | Clear Panics
[**V1CreateInstance**](InstancesV1API.md#V1CreateInstance) | **Post** /v1/instances | Create Instance
[**V1DeleteInstance**](InstancesV1API.md#V1DeleteInstance) | **Delete** /v1/instances/{instanceId} | Remove Instance
[**V1DetachInstanceInterface**](InstancesV1API.md#V1DetachInstanceInterface) | **Delete** /v1/instances/{instanceId}/interfaces/{interfaceId} | Detach I/O Interface
[**V1DisableExposePort**](InstancesV1API.md#V1DisableExposePort) | **Post** /v1/instances/{instanceId}/exposeport/disable | Disable an exposed port on an instance for device access.
[**V1DownloadNetdumpPcapInstances**](InstancesV1API.md#V1DownloadNetdumpPcapInstances) | **Get** /v1/instances/{instanceId}/netdump.pcap | Download a netdump pcap file
[**V1DownloadNetworkMonitorPcapInstances**](InstancesV1API.md#V1DownloadNetworkMonitorPcapInstances) | **Get** /v1/instances/{instanceId}/networkMonitor.pcap | Download a Network Monitor pcap file
[**V1EnableExposePort**](InstancesV1API.md#V1EnableExposePort) | **Post** /v1/instances/{instanceId}/exposeport/enable | Enable an exposed port on an instance for device access.
[**V1GetInstance**](InstancesV1API.md#V1GetInstance) | **Get** /v1/instances/{instanceId} | Get Instance
[**V1GetInstanceConsole**](InstancesV1API.md#V1GetInstanceConsole) | **Get** /v1/instances/{instanceId}/console | Get console websocket URL
[**V1GetInstanceConsoleLog**](InstancesV1API.md#V1GetInstanceConsoleLog) | **Get** /v1/instances/{instanceId}/consoleLog | Get Console Log
[**V1GetInstanceGpios**](InstancesV1API.md#V1GetInstanceGpios) | **Get** /v1/instances/{instanceId}/gpios | Get Instance GPIOs
[**V1GetInstancePanics**](InstancesV1API.md#V1GetInstancePanics) | **Get** /v1/instances/{instanceId}/panics | Get Panics
[**V1GetInstancePeripherals**](InstancesV1API.md#V1GetInstancePeripherals) | **Get** /v1/instances/{instanceId}/peripherals | Get Instance Peripherals
[**V1GetInstanceScreenshot**](InstancesV1API.md#V1GetInstanceScreenshot) | **Get** /v1/instances/{instanceId}/screenshot.{format} | Get Instance Screenshot
[**V1GetInstances**](InstancesV1API.md#V1GetInstances) | **Get** /v1/instances | Get Instances
[**V1InjectMessageInstances**](InstancesV1API.md#V1InjectMessageInstances) | **Post** /v1/instances/{instanceId}/message | Inject a message into an iOS VM
[**V1MediaPlay**](InstancesV1API.md#V1MediaPlay) | **Post** /v1/instances/{instanceId}/media/play | Start playing media
[**V1MediaStop**](InstancesV1API.md#V1MediaStop) | **Post** /v1/instances/{instanceId}/media/stop | Stop playing media
[**V1PatchInstance**](InstancesV1API.md#V1PatchInstance) | **Patch** /v1/instances/{instanceId} | Update Instance
[**V1PatchInstanceReadOnly**](InstancesV1API.md#V1PatchInstanceReadOnly) | **Patch** /v1/instances/{instanceId}/read-only | Update Instance Read Only
[**V1PauseInstance**](InstancesV1API.md#V1PauseInstance) | **Post** /v1/instances/{instanceId}/pause | Pause an Instance
[**V1PostInstanceInput**](InstancesV1API.md#V1PostInstanceInput) | **Post** /v1/instances/{instanceId}/input | Provide Instance Input
[**V1RebootInstance**](InstancesV1API.md#V1RebootInstance) | **Post** /v1/instances/{instanceId}/reboot | Reboot an Instance
[**V1RestoreBackup**](InstancesV1API.md#V1RestoreBackup) | **Post** /v1/instances/{instanceId}/restoreBackup | Restore backup
[**V1RotateInstance**](InstancesV1API.md#V1RotateInstance) | **Post** /v1/instances/{instanceId}/rotate | Rotate device to specified orientation
[**V1SetInstanceGpios**](InstancesV1API.md#V1SetInstanceGpios) | **Put** /v1/instances/{instanceId}/gpios | Set Instance GPIOs
[**V1SetInstancePeripherals**](InstancesV1API.md#V1SetInstancePeripherals) | **Put** /v1/instances/{instanceId}/peripherals | Update Instance Peripherals
[**V1SetInstanceState**](InstancesV1API.md#V1SetInstanceState) | **Put** /v1/instances/{instanceId}/state | Set state of Instance
[**V1StartInstance**](InstancesV1API.md#V1StartInstance) | **Post** /v1/instances/{instanceId}/start | Start an Instance
[**V1StartNetdump**](InstancesV1API.md#V1StartNetdump) | **Post** /v1/instances/{instanceId}/netdump/enable | Start Enhanced Network Monitor on an instance.
[**V1StartNetworkMonitor**](InstancesV1API.md#V1StartNetworkMonitor) | **Post** /v1/instances/{instanceId}/sslsplit/enable | Start Network Monitor on an instance.
[**V1StopInstance**](InstancesV1API.md#V1StopInstance) | **Post** /v1/instances/{instanceId}/stop | Stop an Instance
[**V1StopNetdump**](InstancesV1API.md#V1StopNetdump) | **Post** /v1/instances/{instanceId}/netdump/disable | Stop Enhanced Network Monitor on an instance.
[**V1StopNetworkMonitor**](InstancesV1API.md#V1StopNetworkMonitor) | **Post** /v1/instances/{instanceId}/sslsplit/disable | Stop Network Monitor on an instance.
[**V1UnpauseInstance**](InstancesV1API.md#V1UnpauseInstance) | **Post** /v1/instances/{instanceId}/unpause | Unpause an Instance
[**V1UpgradeInstance**](InstancesV1API.md#V1UpgradeInstance) | **Post** /v1/instances/{instanceId}/upgrade | Upgrade iOS version



## V1AttachInstanceInterface

> V1AttachInstanceInterface(ctx, instanceId).AttachInterfaceRequest(attachInterfaceRequest).Execute()

Attach I/O Interface



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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	attachInterfaceRequest := *openapiclient.NewAttachInterfaceRequest("InterfaceId_example", "InterconnectId_example") // AttachInterfaceRequest | Interface attachment request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1AttachInstanceInterface(context.Background(), instanceId).AttachInterfaceRequest(attachInterfaceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1AttachInstanceInterface``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AttachInstanceInterfaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **attachInterfaceRequest** | [**AttachInterfaceRequest**](AttachInterfaceRequest.md) | Interface attachment request | 

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


## V1ClearInstancePanics

> V1ClearInstancePanics(ctx, instanceId).Execute()

Clear Panics

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1ClearInstancePanics(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1ClearInstancePanics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1ClearInstancePanicsRequest struct via the builder pattern


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


## V1CreateInstance

> InstanceReturn V1CreateInstance(ctx).InstanceCreateOptions(instanceCreateOptions).Execute()

Create Instance

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
	instanceCreateOptions := *openapiclient.NewInstanceCreateOptions("Flavor_example", "Project_example", "Os_example") // InstanceCreateOptions | The vm definition to create

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1CreateInstance(context.Background()).InstanceCreateOptions(instanceCreateOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1CreateInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateInstance`: InstanceReturn
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1CreateInstance`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **instanceCreateOptions** | [**InstanceCreateOptions**](InstanceCreateOptions.md) | The vm definition to create | 

### Return type

[**InstanceReturn**](InstanceReturn.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteInstance

> V1DeleteInstance(ctx, instanceId).Execute()

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
	instanceId := "instanceId_example" // string | Instance ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1DeleteInstance(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1DeleteInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteInstanceRequest struct via the builder pattern


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


## V1DetachInstanceInterface

> V1DetachInstanceInterface(ctx, instanceId, interfaceId).DetachInterfaceRequest(detachInterfaceRequest).Execute()

Detach I/O Interface



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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	interfaceId := "interfaceId_example" // string | Interface ID
	detachInterfaceRequest := *openapiclient.NewDetachInterfaceRequest("InterconnectId_example") // DetachInterfaceRequest | Interface detachment request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1DetachInstanceInterface(context.Background(), instanceId, interfaceId).DetachInterfaceRequest(detachInterfaceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1DetachInstanceInterface``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**interfaceId** | **string** | Interface ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DetachInstanceInterfaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **detachInterfaceRequest** | [**DetachInterfaceRequest**](DetachInterfaceRequest.md) | Interface detachment request | 

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


## V1DisableExposePort

> V1DisableExposePort(ctx, instanceId).Execute()

Disable an exposed port on an instance for device access.

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1DisableExposePort(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1DisableExposePort``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DisableExposePortRequest struct via the builder pattern


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


## V1DownloadNetdumpPcapInstances

> *os.File V1DownloadNetdumpPcapInstances(ctx, instanceId).Execute()

Download a netdump pcap file

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1DownloadNetdumpPcapInstances(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1DownloadNetdumpPcapInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DownloadNetdumpPcapInstances`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1DownloadNetdumpPcapInstances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DownloadNetdumpPcapInstancesRequest struct via the builder pattern


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


## V1DownloadNetworkMonitorPcapInstances

> *os.File V1DownloadNetworkMonitorPcapInstances(ctx, instanceId).Execute()

Download a Network Monitor pcap file

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1DownloadNetworkMonitorPcapInstances(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1DownloadNetworkMonitorPcapInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DownloadNetworkMonitorPcapInstances`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1DownloadNetworkMonitorPcapInstances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DownloadNetworkMonitorPcapInstancesRequest struct via the builder pattern


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


## V1EnableExposePort

> V1EnableExposePort(ctx, instanceId).Execute()

Enable an exposed port on an instance for device access.

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1EnableExposePort(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1EnableExposePort``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1EnableExposePortRequest struct via the builder pattern


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


## V1GetInstance

> InstanceV1 V1GetInstance(ctx, instanceId).ReturnAttr(returnAttr).Execute()

Get Instance

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
	instanceId := "instanceId_example" // string | Instance ID
	returnAttr := []string{"Inner_example"} // []string | Attributes to include in instance return (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1GetInstance(context.Background(), instanceId).ReturnAttr(returnAttr).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1GetInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstance`: InstanceV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1GetInstance`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **returnAttr** | **[]string** | Attributes to include in instance return | 

### Return type

[**InstanceV1**](InstanceV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetInstanceConsole

> InstanceConsoleEndpointV1 V1GetInstanceConsole(ctx, instanceId).Execute()

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1GetInstanceConsole(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1GetInstanceConsole``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstanceConsole`: InstanceConsoleEndpointV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1GetInstanceConsole`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstanceConsoleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InstanceConsoleEndpointV1**](InstanceConsoleEndpointV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetInstanceConsoleLog

> string V1GetInstanceConsoleLog(ctx, instanceId).Execute()

Get Console Log

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1GetInstanceConsoleLog(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1GetInstanceConsoleLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstanceConsoleLog`: string
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1GetInstanceConsoleLog`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstanceConsoleLogRequest struct via the builder pattern


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


## V1GetInstanceGpios

> GpiosStateV1 V1GetInstanceGpios(ctx, instanceId).Execute()

Get Instance GPIOs

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1GetInstanceGpios(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1GetInstanceGpios``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstanceGpios`: GpiosStateV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1GetInstanceGpios`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstanceGpiosRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GpiosStateV1**](GpiosStateV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetInstancePanics

> []map[string]interface{} V1GetInstancePanics(ctx, instanceId).Execute()

Get Panics

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1GetInstancePanics(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1GetInstancePanics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstancePanics`: []map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1GetInstancePanics`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstancePanicsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**[]map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetInstancePeripherals

> PeripheralsDataV1 V1GetInstancePeripherals(ctx, instanceId).Execute()

Get Instance Peripherals

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1GetInstancePeripherals(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1GetInstancePeripherals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstancePeripherals`: PeripheralsDataV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1GetInstancePeripherals`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstancePeripheralsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PeripheralsDataV1**](PeripheralsDataV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetInstanceScreenshot

> *os.File V1GetInstanceScreenshot(ctx, instanceId, format).Scale(scale).Execute()

Get Instance Screenshot

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	format := "format_example" // string | New peripherals state
	scale := float32(56) // float32 | Screenshot scale 1:N (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1GetInstanceScreenshot(context.Background(), instanceId, format).Scale(scale).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1GetInstanceScreenshot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstanceScreenshot`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1GetInstanceScreenshot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**format** | **string** | New peripherals state | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstanceScreenshotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **scale** | **float32** | Screenshot scale 1:N | 

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


## V1GetInstances

> []InstanceV1 V1GetInstances(ctx).Name(name).ReturnAttr(returnAttr).Execute()

Get Instances

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
	name := "name_example" // string | Optionally filter by instance name (optional)
	returnAttr := []string{"Inner_example"} // []string | Attributes to include in instance return (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1GetInstances(context.Background()).Name(name).ReturnAttr(returnAttr).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1GetInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetInstances`: []InstanceV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1GetInstances`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1GetInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Optionally filter by instance name | 
 **returnAttr** | **[]string** | Attributes to include in instance return | 

### Return type

[**[]InstanceV1**](InstanceV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1InjectMessageInstances

> V1InjectMessageInstances(ctx, instanceId).Body(body).Execute()

Inject a message into an iOS VM



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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	body := map[string]interface{}{ ... } // map[string]interface{} | Message data

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1InjectMessageInstances(context.Background(), instanceId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1InjectMessageInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1InjectMessageInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** | Message data | 

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


## V1MediaPlay

> V1MediaPlay(ctx, instanceId).MediaPlayBodyV1(mediaPlayBodyV1).Execute()

Start playing media

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	mediaPlayBodyV1 := *openapiclient.NewMediaPlayBodyV1() // MediaPlayBodyV1 | Request Body

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1MediaPlay(context.Background(), instanceId).MediaPlayBodyV1(mediaPlayBodyV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1MediaPlay``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1MediaPlayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mediaPlayBodyV1** | [**MediaPlayBodyV1**](MediaPlayBodyV1.md) | Request Body | 

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


## V1MediaStop

> V1MediaStop(ctx, instanceId).Execute()

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1MediaStop(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1MediaStop``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1MediaStopRequest struct via the builder pattern


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


## V1PatchInstance

> InstanceV1 V1PatchInstance(ctx, instanceId).PatchInstanceOptions(patchInstanceOptions).Execute()

Update Instance

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
	instanceId := "instanceId_example" // string | Instance ID
	patchInstanceOptions := *openapiclient.NewPatchInstanceOptions() // PatchInstanceOptions | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1PatchInstance(context.Background(), instanceId).PatchInstanceOptions(patchInstanceOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1PatchInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1PatchInstance`: InstanceV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1PatchInstance`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PatchInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchInstanceOptions** | [**PatchInstanceOptions**](PatchInstanceOptions.md) |  | 

### Return type

[**InstanceV1**](InstanceV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PatchInstanceReadOnly

> InstanceV1 V1PatchInstanceReadOnly(ctx, instanceId).PatchInstanceReadOnly(patchInstanceReadOnly).Execute()

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
	instanceId := "instanceId_example" // string | Instance ID
	patchInstanceReadOnly := *openapiclient.NewPatchInstanceReadOnly() // PatchInstanceReadOnly | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1PatchInstanceReadOnly(context.Background(), instanceId).PatchInstanceReadOnly(patchInstanceReadOnly).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1PatchInstanceReadOnly``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1PatchInstanceReadOnly`: InstanceV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1PatchInstanceReadOnly`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PatchInstanceReadOnlyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchInstanceReadOnly** | [**PatchInstanceReadOnly**](PatchInstanceReadOnly.md) |  | 

### Return type

[**InstanceV1**](InstanceV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PauseInstance

> V1PauseInstance(ctx, instanceId).Execute()

Pause an Instance

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1PauseInstance(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1PauseInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PauseInstanceRequest struct via the builder pattern


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


## V1PostInstanceInput

> InputResponseV1 V1PostInstanceInput(ctx, instanceId).InstanceInputRequest(instanceInputRequest).Execute()

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	instanceInputRequest := []openapiclient.InstanceInputRequest{openapiclient.InstanceInputRequest{TextInputRequestV1: openapiclient.NewTextInputRequestV1("Required_example")}} // []InstanceInputRequest | The input to send to the VM

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1PostInstanceInput(context.Background(), instanceId).InstanceInputRequest(instanceInputRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1PostInstanceInput``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1PostInstanceInput`: InputResponseV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1PostInstanceInput`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PostInstanceInputRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **instanceInputRequest** | [**[]InstanceInputRequest**](InstanceInputRequest.md) | The input to send to the VM | 

### Return type

[**InputResponseV1**](InputResponseV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1RebootInstance

> V1RebootInstance(ctx, instanceId).Execute()

Reboot an Instance

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1RebootInstance(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1RebootInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1RebootInstanceRequest struct via the builder pattern


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


## V1RestoreBackup

> V1RestoreBackup(ctx, instanceId).RestoreBackupData(restoreBackupData).Execute()

Restore backup

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	restoreBackupData := *openapiclient.NewRestoreBackupData() // RestoreBackupData | Restore backup data (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1RestoreBackup(context.Background(), instanceId).RestoreBackupData(restoreBackupData).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1RestoreBackup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1RestoreBackupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **restoreBackupData** | [**RestoreBackupData**](RestoreBackupData.md) | Restore backup data | 

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


## V1RotateInstance

> V1RotateInstance(ctx, instanceId).RotateBodyV1(rotateBodyV1).Execute()

Rotate device to specified orientation



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
	instanceId := "instanceId_example" // string | 
	rotateBodyV1 := *openapiclient.NewRotateBodyV1(float32(123)) // RotateBodyV1 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1RotateInstance(context.Background(), instanceId).RotateBodyV1(rotateBodyV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1RotateInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1RotateInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **rotateBodyV1** | [**RotateBodyV1**](RotateBodyV1.md) |  | 

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


## V1SetInstanceGpios

> GpiosStateV1 V1SetInstanceGpios(ctx, instanceId).GpiosStateV1(gpiosStateV1).Execute()

Set Instance GPIOs

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	gpiosStateV1 := *openapiclient.NewGpiosStateV1() // GpiosStateV1 | New GPIO state

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1SetInstanceGpios(context.Background(), instanceId).GpiosStateV1(gpiosStateV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1SetInstanceGpios``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1SetInstanceGpios`: GpiosStateV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1SetInstanceGpios`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1SetInstanceGpiosRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **gpiosStateV1** | [**GpiosStateV1**](GpiosStateV1.md) | New GPIO state | 

### Return type

[**GpiosStateV1**](GpiosStateV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1SetInstancePeripherals

> PeripheralsDataV1 V1SetInstancePeripherals(ctx, instanceId).PeripheralsDataV1(peripheralsDataV1).Execute()

Update Instance Peripherals

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	peripheralsDataV1 := *openapiclient.NewPeripheralsDataV1() // PeripheralsDataV1 | New peripherals state

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InstancesV1API.V1SetInstancePeripherals(context.Background(), instanceId).PeripheralsDataV1(peripheralsDataV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1SetInstancePeripherals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1SetInstancePeripherals`: PeripheralsDataV1
	fmt.Fprintf(os.Stdout, "Response from `InstancesV1API.V1SetInstancePeripherals`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1SetInstancePeripheralsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **peripheralsDataV1** | [**PeripheralsDataV1**](PeripheralsDataV1.md) | New peripherals state | 

### Return type

[**PeripheralsDataV1**](PeripheralsDataV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1SetInstanceState

> V1SetInstanceState(ctx, instanceId).V1SetStateBody(v1SetStateBody).Execute()

Set state of Instance

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	v1SetStateBody := *openapiclient.NewV1SetStateBody(openapiclient.InstanceStateV1("on")) // V1SetStateBody | Desired State

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1SetInstanceState(context.Background(), instanceId).V1SetStateBody(v1SetStateBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1SetInstanceState``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1SetInstanceStateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v1SetStateBody** | [**V1SetStateBody**](V1SetStateBody.md) | Desired State | 

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


## V1StartInstance

> V1StartInstance(ctx, instanceId).InstanceStartOptions(instanceStartOptions).Execute()

Start an Instance

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	instanceStartOptions := *openapiclient.NewInstanceStartOptions() // InstanceStartOptions | Start options (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1StartInstance(context.Background(), instanceId).InstanceStartOptions(instanceStartOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1StartInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StartInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **instanceStartOptions** | [**InstanceStartOptions**](InstanceStartOptions.md) | Start options | 

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


## V1StartNetdump

> V1StartNetdump(ctx, instanceId).NetdumpFilter(netdumpFilter).Execute()

Start Enhanced Network Monitor on an instance.

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	netdumpFilter := *openapiclient.NewNetdumpFilter() // NetdumpFilter |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1StartNetdump(context.Background(), instanceId).NetdumpFilter(netdumpFilter).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1StartNetdump``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StartNetdumpRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **netdumpFilter** | [**NetdumpFilter**](NetdumpFilter.md) |  | 

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


## V1StartNetworkMonitor

> V1StartNetworkMonitor(ctx, instanceId).SslsplitFilter(sslsplitFilter).Execute()

Start Network Monitor on an instance.

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	sslsplitFilter := *openapiclient.NewSslsplitFilter() // SslsplitFilter |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1StartNetworkMonitor(context.Background(), instanceId).SslsplitFilter(sslsplitFilter).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1StartNetworkMonitor``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StartNetworkMonitorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **sslsplitFilter** | [**SslsplitFilter**](SslsplitFilter.md) |  | 

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


## V1StopInstance

> V1StopInstance(ctx, instanceId).InstanceStopOptions(instanceStopOptions).Execute()

Stop an Instance

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	instanceStopOptions := *openapiclient.NewInstanceStopOptions() // InstanceStopOptions | Stop options (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1StopInstance(context.Background(), instanceId).InstanceStopOptions(instanceStopOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1StopInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StopInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **instanceStopOptions** | [**InstanceStopOptions**](InstanceStopOptions.md) | Stop options | 

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


## V1StopNetdump

> V1StopNetdump(ctx, instanceId).Execute()

Stop Enhanced Network Monitor on an instance.

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1StopNetdump(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1StopNetdump``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StopNetdumpRequest struct via the builder pattern


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


## V1StopNetworkMonitor

> V1StopNetworkMonitor(ctx, instanceId).Execute()

Stop Network Monitor on an instance.

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1StopNetworkMonitor(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1StopNetworkMonitor``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StopNetworkMonitorRequest struct via the builder pattern


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


## V1UnpauseInstance

> V1UnpauseInstance(ctx, instanceId).Execute()

Unpause an Instance

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
	instanceId := "instanceId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1UnpauseInstance(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1UnpauseInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UnpauseInstanceRequest struct via the builder pattern


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


## V1UpgradeInstance

> V1UpgradeInstance(ctx, instanceId).InstanceUpgradeBodyV1(instanceUpgradeBodyV1).Execute()

Upgrade iOS version

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
	instanceId := "instanceId_example" // string | 
	instanceUpgradeBodyV1 := *openapiclient.NewInstanceUpgradeBodyV1("Os_example") // InstanceUpgradeBodyV1 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InstancesV1API.V1UpgradeInstance(context.Background(), instanceId).InstanceUpgradeBodyV1(instanceUpgradeBodyV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InstancesV1API.V1UpgradeInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UpgradeInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **instanceUpgradeBodyV1** | [**InstanceUpgradeBodyV1**](InstanceUpgradeBodyV1.md) |  | 

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

