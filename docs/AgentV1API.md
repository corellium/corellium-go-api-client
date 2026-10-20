# \AgentV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1AgentAppReady**](AgentV1API.md#V1AgentAppReady) | **Get** /v1/instances/{instanceId}/agent/v1/app/ready | Check if App subsystem is ready
[**V1AgentDeleteFile**](AgentV1API.md#V1AgentDeleteFile) | **Delete** /v1/instances/{instanceId}/agent/v1/file/device/{filePath} | Delete a File on VM
[**V1AgentGetFile**](AgentV1API.md#V1AgentGetFile) | **Get** /v1/instances/{instanceId}/agent/v1/file/device/{filePath} | Download a File from VM
[**V1AgentGetTempFilename**](AgentV1API.md#V1AgentGetTempFilename) | **Post** /v1/instances/{instanceId}/agent/v1/file/temp | Get the path for a new temp file
[**V1AgentInstallApp**](AgentV1API.md#V1AgentInstallApp) | **Post** /v1/instances/{instanceId}/agent/v1/app/install | Install App at path
[**V1AgentInstallProfile**](AgentV1API.md#V1AgentInstallProfile) | **Post** /v1/instances/{instanceId}/agent/v1/profile/install | Install a Profile to VM
[**V1AgentKillApp**](AgentV1API.md#V1AgentKillApp) | **Post** /v1/instances/{instanceId}/agent/v1/app/apps/{bundleId}/kill | Kill an App
[**V1AgentListAppIcons**](AgentV1API.md#V1AgentListAppIcons) | **Get** /v1/instances/{instanceId}/agent/v1/app/icons | List App Icons
[**V1AgentListApps**](AgentV1API.md#V1AgentListApps) | **Get** /v1/instances/{instanceId}/agent/v1/app/apps | List Apps
[**V1AgentListAppsStatus**](AgentV1API.md#V1AgentListAppsStatus) | **Get** /v1/instances/{instanceId}/agent/v1/app/apps/update | List Apps Status
[**V1AgentListProfiles**](AgentV1API.md#V1AgentListProfiles) | **Get** /v1/instances/{instanceId}/agent/v1/profile/profiles | List Profiles
[**V1AgentRunApp**](AgentV1API.md#V1AgentRunApp) | **Post** /v1/instances/{instanceId}/agent/v1/app/apps/{bundleId}/run | Run an App
[**V1AgentSetFileAttributes**](AgentV1API.md#V1AgentSetFileAttributes) | **Patch** /v1/instances/{instanceId}/agent/v1/file/device/{filePath} | Change Attrs of a File on VM
[**V1AgentSystemGetAdbAuth**](AgentV1API.md#V1AgentSystemGetAdbAuth) | **Get** /v1/instances/{instanceId}/agent/v1/system/adbauth | Get ADB Auth Setting (AOSP only)
[**V1AgentSystemGetNetwork**](AgentV1API.md#V1AgentSystemGetNetwork) | **Get** /v1/instances/{instanceId}/agent/v1/system/network | Get IP of eth0 (AOSP only)
[**V1AgentSystemGetProp**](AgentV1API.md#V1AgentSystemGetProp) | **Post** /v1/instances/{instanceId}/agent/v1/system/getprop | Get System Property (AOSP only)
[**V1AgentSystemInstallOpenGApps**](AgentV1API.md#V1AgentSystemInstallOpenGApps) | **Post** /v1/instances/{instanceId}/agent/v1/system/install-opengapps | Install OpenGApps (AOSP only)
[**V1AgentSystemLock**](AgentV1API.md#V1AgentSystemLock) | **Post** /v1/instances/{instanceId}/agent/v1/system/lock | Lock Device (iOS Only)
[**V1AgentSystemSetAdbAuth**](AgentV1API.md#V1AgentSystemSetAdbAuth) | **Put** /v1/instances/{instanceId}/agent/v1/system/adbauth | Set ADB Auth Setting (AOSP only)
[**V1AgentSystemSetHostname**](AgentV1API.md#V1AgentSystemSetHostname) | **Post** /v1/instances/{instanceId}/agent/v1/system/setHostname | Set Hostname of instance
[**V1AgentSystemShutdown**](AgentV1API.md#V1AgentSystemShutdown) | **Post** /v1/instances/{instanceId}/agent/v1/system/shutdown | Instruct VM to halt
[**V1AgentSystemUnlock**](AgentV1API.md#V1AgentSystemUnlock) | **Post** /v1/instances/{instanceId}/agent/v1/system/unlock | Unlock Device (iOS Only)
[**V1AgentUninstallApp**](AgentV1API.md#V1AgentUninstallApp) | **Post** /v1/instances/{instanceId}/agent/v1/app/apps/{bundleId}/uninstall | Uninstall an App
[**V1AgentUninstallProfile**](AgentV1API.md#V1AgentUninstallProfile) | **Delete** /v1/instances/{instanceId}/agent/v1/profile/profiles/{profileId} | Uninstall a Profile from VM
[**V1AgentUploadFile**](AgentV1API.md#V1AgentUploadFile) | **Put** /v1/instances/{instanceId}/agent/v1/file/device/{filePath} | Upload a file to VM



## V1AgentAppReady

> AgentAppReadyResponseV1 V1AgentAppReady(ctx, instanceId).Execute()

Check if App subsystem is ready

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
	resp, r, err := apiClient.AgentV1API.V1AgentAppReady(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentAppReady``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentAppReady`: AgentAppReadyResponseV1
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentAppReady`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentAppReadyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentAppReadyResponseV1**](AgentAppReadyResponseV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AgentDeleteFile

> V1AgentDeleteFile(ctx, instanceId, filePath).Execute()

Delete a File on VM

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
	filePath := "filePath_example" // string | File Path on VM

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentV1API.V1AgentDeleteFile(context.Background(), instanceId, filePath).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentDeleteFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**filePath** | **string** | File Path on VM | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentDeleteFileRequest struct via the builder pattern


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


## V1AgentGetFile

> *os.File V1AgentGetFile(ctx, instanceId, filePath).Execute()

Download a File from VM

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
	filePath := "filePath_example" // string | File Path on VM

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentV1API.V1AgentGetFile(context.Background(), instanceId, filePath).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentGetFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentGetFile`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentGetFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**filePath** | **string** | File Path on VM | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentGetFileRequest struct via the builder pattern


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


## V1AgentGetTempFilename

> string V1AgentGetTempFilename(ctx, instanceId).Execute()

Get the path for a new temp file



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
	resp, r, err := apiClient.AgentV1API.V1AgentGetTempFilename(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentGetTempFilename``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentGetTempFilename`: string
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentGetTempFilename`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentGetTempFilenameRequest struct via the builder pattern


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


## V1AgentInstallApp

> V1AgentInstallApp(ctx, instanceId).AgentInstallBodyV1(agentInstallBodyV1).Execute()

Install App at path



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
	agentInstallBodyV1 := *openapiclient.NewAgentInstallBodyV1() // AgentInstallBodyV1 | App parameters

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentV1API.V1AgentInstallApp(context.Background(), instanceId).AgentInstallBodyV1(agentInstallBodyV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentInstallApp``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AgentInstallAppRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentInstallBodyV1** | [**AgentInstallBodyV1**](AgentInstallBodyV1.md) | App parameters | 

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


## V1AgentInstallProfile

> V1AgentInstallProfile(ctx, instanceId).Body(body).Execute()

Install a Profile to VM

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
	body := os.NewFile(1234, "some_file") // *os.File | Profile to Install

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentV1API.V1AgentInstallProfile(context.Background(), instanceId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentInstallProfile``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AgentInstallProfileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | ***os.File** | Profile to Install | 

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


## V1AgentKillApp

> map[string]interface{} V1AgentKillApp(ctx, instanceId, bundleId).Execute()

Kill an App

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
	bundleId := "bundleId_example" // string | App Bundle ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentV1API.V1AgentKillApp(context.Background(), instanceId, bundleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentKillApp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentKillApp`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentKillApp`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**bundleId** | **string** | App Bundle ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentKillAppRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



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


## V1AgentListAppIcons

> []AgentIcons V1AgentListAppIcons(ctx, instanceId).BundleID(bundleID).Execute()

List App Icons



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
	bundleID := []string{"Inner_example"} // []string | App Bundle ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentV1API.V1AgentListAppIcons(context.Background(), instanceId).BundleID(bundleID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentListAppIcons``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentListAppIcons`: []AgentIcons
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentListAppIcons`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentListAppIconsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **bundleID** | **[]string** | App Bundle ID | 

### Return type

[**[]AgentIcons**](AgentIcons.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AgentListApps

> AgentAppsListV1 V1AgentListApps(ctx, instanceId).Execute()

List Apps

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
	resp, r, err := apiClient.AgentV1API.V1AgentListApps(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentListApps``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentListApps`: AgentAppsListV1
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentListApps`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentListAppsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentAppsListV1**](AgentAppsListV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AgentListAppsStatus

> AgentAppsListV1 V1AgentListAppsStatus(ctx, instanceId).Execute()

List Apps Status

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
	resp, r, err := apiClient.AgentV1API.V1AgentListAppsStatus(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentListAppsStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentListAppsStatus`: AgentAppsListV1
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentListAppsStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentListAppsStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentAppsListV1**](AgentAppsListV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AgentListProfiles

> AgentProfilesReturn V1AgentListProfiles(ctx, instanceId).Execute()

List Profiles

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
	resp, r, err := apiClient.AgentV1API.V1AgentListProfiles(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentListProfiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentListProfiles`: AgentProfilesReturn
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentListProfiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentListProfilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentProfilesReturn**](AgentProfilesReturn.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AgentRunApp

> map[string]interface{} V1AgentRunApp(ctx, instanceId, bundleId).Execute()

Run an App

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
	bundleId := "bundleId_example" // string | App Bundle ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentV1API.V1AgentRunApp(context.Background(), instanceId, bundleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentRunApp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentRunApp`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentRunApp`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**bundleId** | **string** | App Bundle ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentRunAppRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



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


## V1AgentSetFileAttributes

> V1AgentSetFileAttributes(ctx, instanceId, filePath).FileChanges(fileChanges).Execute()

Change Attrs of a File on VM

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
	filePath := "filePath_example" // string | File Path on VM
	fileChanges := *openapiclient.NewFileChanges() // FileChanges | New attrs

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentV1API.V1AgentSetFileAttributes(context.Background(), instanceId, filePath).FileChanges(fileChanges).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSetFileAttributes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**filePath** | **string** | File Path on VM | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentSetFileAttributesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **fileChanges** | [**FileChanges**](FileChanges.md) | New attrs | 

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


## V1AgentSystemGetAdbAuth

> AgentSystemAdbAuthV1 V1AgentSystemGetAdbAuth(ctx, instanceId).Execute()

Get ADB Auth Setting (AOSP only)

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
	resp, r, err := apiClient.AgentV1API.V1AgentSystemGetAdbAuth(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSystemGetAdbAuth``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentSystemGetAdbAuth`: AgentSystemAdbAuthV1
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentSystemGetAdbAuth`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentSystemGetAdbAuthRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentSystemAdbAuthV1**](AgentSystemAdbAuthV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AgentSystemGetNetwork

> AgentValueReturn V1AgentSystemGetNetwork(ctx, instanceId).Execute()

Get IP of eth0 (AOSP only)

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
	resp, r, err := apiClient.AgentV1API.V1AgentSystemGetNetwork(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSystemGetNetwork``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentSystemGetNetwork`: AgentValueReturn
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentSystemGetNetwork`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentSystemGetNetworkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AgentValueReturn**](AgentValueReturn.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AgentSystemGetProp

> AgentValueReturn V1AgentSystemGetProp(ctx, instanceId).AgentSystemGetPropBodyV1(agentSystemGetPropBodyV1).Execute()

Get System Property (AOSP only)

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
	agentSystemGetPropBodyV1 := *openapiclient.NewAgentSystemGetPropBodyV1("Property_example") // AgentSystemGetPropBodyV1 | Parameters

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentV1API.V1AgentSystemGetProp(context.Background(), instanceId).AgentSystemGetPropBodyV1(agentSystemGetPropBodyV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSystemGetProp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentSystemGetProp`: AgentValueReturn
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentSystemGetProp`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentSystemGetPropRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentSystemGetPropBodyV1** | [**AgentSystemGetPropBodyV1**](AgentSystemGetPropBodyV1.md) | Parameters | 

### Return type

[**AgentValueReturn**](AgentValueReturn.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AgentSystemInstallOpenGApps

> V1AgentSystemInstallOpenGApps(ctx, instanceId).Body(body).Execute()

Install OpenGApps (AOSP only)

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
	body := map[string]interface{}{ ... } // map[string]interface{} | Installation parameters

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentV1API.V1AgentSystemInstallOpenGApps(context.Background(), instanceId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSystemInstallOpenGApps``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AgentSystemInstallOpenGAppsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** | Installation parameters | 

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


## V1AgentSystemLock

> V1AgentSystemLock(ctx, instanceId).Execute()

Lock Device (iOS Only)

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
	r, err := apiClient.AgentV1API.V1AgentSystemLock(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSystemLock``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AgentSystemLockRequest struct via the builder pattern


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


## V1AgentSystemSetAdbAuth

> V1AgentSystemSetAdbAuth(ctx, instanceId).AgentSystemAdbAuthV1(agentSystemAdbAuthV1).Execute()

Set ADB Auth Setting (AOSP only)

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
	agentSystemAdbAuthV1 := *openapiclient.NewAgentSystemAdbAuthV1() // AgentSystemAdbAuthV1 | Desired ADB Auth Setting

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentV1API.V1AgentSystemSetAdbAuth(context.Background(), instanceId).AgentSystemAdbAuthV1(agentSystemAdbAuthV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSystemSetAdbAuth``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AgentSystemSetAdbAuthRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentSystemAdbAuthV1** | [**AgentSystemAdbAuthV1**](AgentSystemAdbAuthV1.md) | Desired ADB Auth Setting | 

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


## V1AgentSystemSetHostname

> V1AgentSystemSetHostname(ctx, instanceId).AgentSystemSetHostnameBodyV1(agentSystemSetHostnameBodyV1).Execute()

Set Hostname of instance

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
	agentSystemSetHostnameBodyV1 := *openapiclient.NewAgentSystemSetHostnameBodyV1("Hostname_example") // AgentSystemSetHostnameBodyV1 | New hostname

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentV1API.V1AgentSystemSetHostname(context.Background(), instanceId).AgentSystemSetHostnameBodyV1(agentSystemSetHostnameBodyV1).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSystemSetHostname``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AgentSystemSetHostnameRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentSystemSetHostnameBodyV1** | [**AgentSystemSetHostnameBodyV1**](AgentSystemSetHostnameBodyV1.md) | New hostname | 

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


## V1AgentSystemShutdown

> V1AgentSystemShutdown(ctx, instanceId).Execute()

Instruct VM to halt

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
	r, err := apiClient.AgentV1API.V1AgentSystemShutdown(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSystemShutdown``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AgentSystemShutdownRequest struct via the builder pattern


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


## V1AgentSystemUnlock

> V1AgentSystemUnlock(ctx, instanceId).Execute()

Unlock Device (iOS Only)

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
	r, err := apiClient.AgentV1API.V1AgentSystemUnlock(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentSystemUnlock``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AgentSystemUnlockRequest struct via the builder pattern


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


## V1AgentUninstallApp

> map[string]interface{} V1AgentUninstallApp(ctx, instanceId, bundleId).Execute()

Uninstall an App

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
	bundleId := "bundleId_example" // string | App Bundle ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentV1API.V1AgentUninstallApp(context.Background(), instanceId, bundleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentUninstallApp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AgentUninstallApp`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AgentV1API.V1AgentUninstallApp`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**bundleId** | **string** | App Bundle ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentUninstallAppRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



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


## V1AgentUninstallProfile

> V1AgentUninstallProfile(ctx, instanceId, profileId).Execute()

Uninstall a Profile from VM

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
	profileId := "profileId_example" // string | Instance ID - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentV1API.V1AgentUninstallProfile(context.Background(), instanceId, profileId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentUninstallProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**profileId** | **string** | Instance ID - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentUninstallProfileRequest struct via the builder pattern


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


## V1AgentUploadFile

> V1AgentUploadFile(ctx, instanceId, filePath).Body(body).Execute()

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
	instanceId := "instanceId_example" // string | Instance ID - uuid
	filePath := "filePath_example" // string | File Path on VM to write to
	body := os.NewFile(1234, "some_file") // *os.File | Uploaded File Contents

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AgentV1API.V1AgentUploadFile(context.Background(), instanceId, filePath).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentV1API.V1AgentUploadFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | Instance ID - uuid | 
**filePath** | **string** | File Path on VM to write to | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AgentUploadFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **body** | ***os.File** | Uploaded File Contents | 

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

