# \AssessmentsV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1CreateAssessment**](AssessmentsV1API.md#V1CreateAssessment) | **Post** /v1/services/matrix/{instanceId}/assessments | Create an assessment.
[**V1CreateReportModification**](AssessmentsV1API.md#V1CreateReportModification) | **Post** /v1/services/matrix/{instanceId}/assessments/{assessmentId}/report-modification | Create report modifications.
[**V1DeleteAssessment**](AssessmentsV1API.md#V1DeleteAssessment) | **Delete** /v1/services/matrix/{instanceId}/assessments/{assessmentId} | Delete an assessment.
[**V1DeleteReportModification**](AssessmentsV1API.md#V1DeleteReportModification) | **Delete** /v1/services/matrix/{instanceId}/assessments/{assessmentId}/report-modification | Delete report modifications.
[**V1DownloadReport**](AssessmentsV1API.md#V1DownloadReport) | **Get** /v1/services/matrix/{instanceId}/assessments/{assessmentId}/download | Download an assessment report.
[**V1GetAssessmentById**](AssessmentsV1API.md#V1GetAssessmentById) | **Get** /v1/services/matrix/{instanceId}/assessments/{assessmentId} | Get an assessment by ID.
[**V1GetAssessmentsByInstanceId**](AssessmentsV1API.md#V1GetAssessmentsByInstanceId) | **Get** /v1/services/matrix/{instanceId}/instances/{targetInstanceId}/assessments | List assessments for an instance.
[**V1PatchAssessment**](AssessmentsV1API.md#V1PatchAssessment) | **Patch** /v1/services/matrix/{instanceId}/assessments/{assessmentId} | Update an assessment status.
[**V1RunTests**](AssessmentsV1API.md#V1RunTests) | **Post** /v1/services/matrix/{instanceId}/assessments/{assessmentId}/test | Run assessment tests.
[**V1StartMonitoring**](AssessmentsV1API.md#V1StartMonitoring) | **Post** /v1/services/matrix/{instanceId}/assessments/{assessmentId}/start | Start assessment monitoring.
[**V1StopMonitoring**](AssessmentsV1API.md#V1StopMonitoring) | **Post** /v1/services/matrix/{instanceId}/assessments/{assessmentId}/stop | Stop assessment monitoring.



## V1CreateAssessment

> AssessmentIdStatus V1CreateAssessment(ctx, instanceId).CreateAssessmentInput(createAssessmentInput).Execute()

Create an assessment.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	createAssessmentInput := *openapiclient.NewCreateAssessmentInput("InstanceId_example", "com.android.egg") // CreateAssessmentInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssessmentsV1API.V1CreateAssessment(context.Background(), instanceId).CreateAssessmentInput(createAssessmentInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1CreateAssessment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateAssessment`: AssessmentIdStatus
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsV1API.V1CreateAssessment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateAssessmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createAssessmentInput** | [**CreateAssessmentInput**](CreateAssessmentInput.md) |  | 

### Return type

[**AssessmentIdStatus**](AssessmentIdStatus.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1CreateReportModification

> []ReportModificationResult V1CreateReportModification(ctx, instanceId, assessmentId).ReportModificationInput(reportModificationInput).Execute()

Create report modifications.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	assessmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Identifier of the assessment.
	reportModificationInput := []openapiclient.ReportModificationInput{*openapiclient.NewReportModificationInput("masvs-storage-2-android-8", "severity")} // []ReportModificationInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssessmentsV1API.V1CreateReportModification(context.Background(), instanceId, assessmentId).ReportModificationInput(reportModificationInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1CreateReportModification``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateReportModification`: []ReportModificationResult
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsV1API.V1CreateReportModification`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateReportModificationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **reportModificationInput** | [**[]ReportModificationInput**](ReportModificationInput.md) |  | 

### Return type

[**[]ReportModificationResult**](ReportModificationResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteAssessment

> V1DeleteAssessment(ctx, instanceId, assessmentId).Execute()

Delete an assessment.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	assessmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Identifier of the assessment.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AssessmentsV1API.V1DeleteAssessment(context.Background(), instanceId, assessmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1DeleteAssessment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteAssessmentRequest struct via the builder pattern


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


## V1DeleteReportModification

> []ReportModificationResult V1DeleteReportModification(ctx, instanceId, assessmentId).DeleteModificationInput(deleteModificationInput).Execute()

Delete report modifications.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	assessmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Identifier of the assessment.
	deleteModificationInput := []openapiclient.DeleteModificationInput{*openapiclient.NewDeleteModificationInput("masvs-storage-2-android-8", "severity")} // []DeleteModificationInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssessmentsV1API.V1DeleteReportModification(context.Background(), instanceId, assessmentId).DeleteModificationInput(deleteModificationInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1DeleteReportModification``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DeleteReportModification`: []ReportModificationResult
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsV1API.V1DeleteReportModification`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteReportModificationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **deleteModificationInput** | [**[]DeleteModificationInput**](DeleteModificationInput.md) |  | 

### Return type

[**[]ReportModificationResult**](ReportModificationResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DownloadReport

> string V1DownloadReport(ctx, instanceId, assessmentId).Format(format).Execute()

Download an assessment report.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	assessmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Identifier of the assessment.
	format := openapiclient.AssessmentFormat("json") // AssessmentFormat | Report download format. Defaults to \"html\". (optional) (default to "html")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssessmentsV1API.V1DownloadReport(context.Background(), instanceId, assessmentId).Format(format).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1DownloadReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DownloadReport`: string
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsV1API.V1DownloadReport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DownloadReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **format** | [**AssessmentFormat**](AssessmentFormat.md) | Report download format. Defaults to \&quot;html\&quot;. | [default to &quot;html&quot;]

### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/html, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetAssessmentById

> Assessment V1GetAssessmentById(ctx, instanceId, assessmentId).Execute()

Get an assessment by ID.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	assessmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Identifier of the assessment.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssessmentsV1API.V1GetAssessmentById(context.Background(), instanceId, assessmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1GetAssessmentById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetAssessmentById`: Assessment
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsV1API.V1GetAssessmentById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetAssessmentByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Assessment**](Assessment.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1GetAssessmentsByInstanceId

> []Assessment V1GetAssessmentsByInstanceId(ctx, instanceId, targetInstanceId).Execute()

List assessments for an instance.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	targetInstanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance whose assessments you want to list. Set this to the same value as `instanceId`; the path contains the ID twice only because of how the MATRIX service is routed.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssessmentsV1API.V1GetAssessmentsByInstanceId(context.Background(), instanceId, targetInstanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1GetAssessmentsByInstanceId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetAssessmentsByInstanceId`: []Assessment
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsV1API.V1GetAssessmentsByInstanceId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**targetInstanceId** | **string** | ID of the instance whose assessments you want to list. Set this to the same value as &#x60;instanceId&#x60;; the path contains the ID twice only because of how the MATRIX service is routed. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1GetAssessmentsByInstanceIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**[]Assessment**](Assessment.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PatchAssessment

> Assessment V1PatchAssessment(ctx, instanceId, assessmentId).UpdateAssessmentInput(updateAssessmentInput).Execute()

Update an assessment status.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	assessmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Identifier of the assessment.
	updateAssessmentInput := *openapiclient.NewUpdateAssessmentInput("testing") // UpdateAssessmentInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssessmentsV1API.V1PatchAssessment(context.Background(), instanceId, assessmentId).UpdateAssessmentInput(updateAssessmentInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1PatchAssessment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1PatchAssessment`: Assessment
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsV1API.V1PatchAssessment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PatchAssessmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateAssessmentInput** | [**UpdateAssessmentInput**](UpdateAssessmentInput.md) |  | 

### Return type

[**Assessment**](Assessment.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1RunTests

> AssessmentIdStatus V1RunTests(ctx, instanceId, assessmentId).TestAssessmentInput(testAssessmentInput).Execute()

Run assessment tests.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	assessmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Identifier of the assessment.
	testAssessmentInput := *openapiclient.NewTestAssessmentInput() // TestAssessmentInput |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssessmentsV1API.V1RunTests(context.Background(), instanceId, assessmentId).TestAssessmentInput(testAssessmentInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1RunTests``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1RunTests`: AssessmentIdStatus
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsV1API.V1RunTests`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1RunTestsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **testAssessmentInput** | [**TestAssessmentInput**](TestAssessmentInput.md) |  | 

### Return type

[**AssessmentIdStatus**](AssessmentIdStatus.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StartMonitoring

> V1StartMonitoring(ctx, instanceId, assessmentId).Execute()

Start assessment monitoring.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	assessmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Identifier of the assessment.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AssessmentsV1API.V1StartMonitoring(context.Background(), instanceId, assessmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1StartMonitoring``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StartMonitoringRequest struct via the builder pattern


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


## V1StopMonitoring

> V1StopMonitoring(ctx, instanceId, assessmentId).Execute()

Stop assessment monitoring.



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects.
	assessmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Identifier of the assessment.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AssessmentsV1API.V1StopMonitoring(context.Background(), instanceId, assessmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsV1API.V1StopMonitoring``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StopMonitoringRequest struct via the builder pattern


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

