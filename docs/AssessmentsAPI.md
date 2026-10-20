# \AssessmentsAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateAssessment**](AssessmentsAPI.md#V3CreateAssessment) | **Post** /v3/services/matrix/{instanceId}/assessments | Create an assessment.
[**V3CreateReportModification**](AssessmentsAPI.md#V3CreateReportModification) | **Post** /v3/services/matrix/{instanceId}/assessments/{assessmentId}/report-modification | Create report modifications.
[**V3DeleteAssessment**](AssessmentsAPI.md#V3DeleteAssessment) | **Delete** /v3/services/matrix/{instanceId}/assessments/{assessmentId} | Delete an assessment.
[**V3DeleteReportModification**](AssessmentsAPI.md#V3DeleteReportModification) | **Delete** /v3/services/matrix/{instanceId}/assessments/{assessmentId}/report-modification | Delete report modifications.
[**V3DownloadReport**](AssessmentsAPI.md#V3DownloadReport) | **Get** /v3/services/matrix/{instanceId}/assessments/{assessmentId}/download | Download an assessment report.
[**V3GetAssessmentById**](AssessmentsAPI.md#V3GetAssessmentById) | **Get** /v3/services/matrix/{instanceId}/assessments/{assessmentId} | Get an assessment by ID.
[**V3GetAssessmentsByInstanceId**](AssessmentsAPI.md#V3GetAssessmentsByInstanceId) | **Get** /v3/services/matrix/{instanceId}/instances/{targetInstanceId}/assessments | List assessments for an instance.
[**V3PatchAssessment**](AssessmentsAPI.md#V3PatchAssessment) | **Patch** /v3/services/matrix/{instanceId}/assessments/{assessmentId} | Update an assessment status.
[**V3RunTests**](AssessmentsAPI.md#V3RunTests) | **Post** /v3/services/matrix/{instanceId}/assessments/{assessmentId}/test | Run assessment tests.
[**V3StartMonitoring**](AssessmentsAPI.md#V3StartMonitoring) | **Post** /v3/services/matrix/{instanceId}/assessments/{assessmentId}/start | Start assessment monitoring.
[**V3StopMonitoring**](AssessmentsAPI.md#V3StopMonitoring) | **Post** /v3/services/matrix/{instanceId}/assessments/{assessmentId}/stop | Stop assessment monitoring.



## V3CreateAssessment

> AssessmentIdStatus V3CreateAssessment(ctx, instanceId).CreateAssessmentInput(createAssessmentInput).Execute()

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
	resp, r, err := apiClient.AssessmentsAPI.V3CreateAssessment(context.Background(), instanceId).CreateAssessmentInput(createAssessmentInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3CreateAssessment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateAssessment`: AssessmentIdStatus
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsAPI.V3CreateAssessment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateAssessmentRequest struct via the builder pattern


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


## V3CreateReportModification

> []ReportModificationResult V3CreateReportModification(ctx, instanceId, assessmentId).ReportModificationInput(reportModificationInput).Execute()

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
	resp, r, err := apiClient.AssessmentsAPI.V3CreateReportModification(context.Background(), instanceId, assessmentId).ReportModificationInput(reportModificationInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3CreateReportModification``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateReportModification`: []ReportModificationResult
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsAPI.V3CreateReportModification`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateReportModificationRequest struct via the builder pattern


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


## V3DeleteAssessment

> V3DeleteAssessment(ctx, instanceId, assessmentId).Execute()

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
	r, err := apiClient.AssessmentsAPI.V3DeleteAssessment(context.Background(), instanceId, assessmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3DeleteAssessment``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3DeleteAssessmentRequest struct via the builder pattern


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


## V3DeleteReportModification

> []ReportModificationResult V3DeleteReportModification(ctx, instanceId, assessmentId).DeleteModificationInput(deleteModificationInput).Execute()

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
	resp, r, err := apiClient.AssessmentsAPI.V3DeleteReportModification(context.Background(), instanceId, assessmentId).DeleteModificationInput(deleteModificationInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3DeleteReportModification``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3DeleteReportModification`: []ReportModificationResult
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsAPI.V3DeleteReportModification`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteReportModificationRequest struct via the builder pattern


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


## V3DownloadReport

> string V3DownloadReport(ctx, instanceId, assessmentId).Format(format).Execute()

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
	resp, r, err := apiClient.AssessmentsAPI.V3DownloadReport(context.Background(), instanceId, assessmentId).Format(format).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3DownloadReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3DownloadReport`: string
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsAPI.V3DownloadReport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DownloadReportRequest struct via the builder pattern


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


## V3GetAssessmentById

> Assessment V3GetAssessmentById(ctx, instanceId, assessmentId).Execute()

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
	resp, r, err := apiClient.AssessmentsAPI.V3GetAssessmentById(context.Background(), instanceId, assessmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3GetAssessmentById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetAssessmentById`: Assessment
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsAPI.V3GetAssessmentById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetAssessmentByIdRequest struct via the builder pattern


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


## V3GetAssessmentsByInstanceId

> PaginatedAssessments V3GetAssessmentsByInstanceId(ctx, instanceId, targetInstanceId).Limit(limit).Offset(offset).Sort(sort).Name(name).Version(version).Status(status).CreatedBy(createdBy).Wordlist(wordlist).Frida(frida).CorelliumVersion(corelliumVersion).CreatedAt(createdAt).Execute()

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
	limit := float32(56) // float32 | Maximum number of assessments to return. Defaults to 100. (optional) (default to 100)
	offset := float32(56) // float32 | Number of assessments to skip before returning results. Defaults to 0. (optional) (default to 0)
	sort := "-createdAt" // string | Comma-separated fields to order by; prefix a field with \"-\" for descending. Allowed fields: createdAt, status, name, version, score, wordlist, frida, corelliumVersion. Defaults to \"-createdAt\". (optional)
	name := "name_example" // string | Filter by app name (exact match). (optional)
	version := "version_example" // string | Filter by app version (exact match). (optional)
	status := "status_example" // string | Filter by assessment status. (optional)
	createdBy := "createdBy_example" // string | Filter by the user ID that created the assessment. (optional)
	wordlist := "wordlist_example" // string | Filter by wordlist name. Use \"None\" to return assessments without a wordlist. (optional)
	frida := "frida_example" // string | Filter by Frida script name. Use \"None\" to return assessments without a Frida script. (optional)
	corelliumVersion := "corelliumVersion_example" // string | Filter by Corellium version (exact match). (optional)
	createdAt := "9/1/2026-9/2/2026" // string | Filter by test date. Accepts a single date (MM/DD/YYYY), a range (MM/DD/YYYY-MM/DD/YYYY), or a comma-separated list of dates and ranges. Dates are matched inclusive of the full day in UTC. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssessmentsAPI.V3GetAssessmentsByInstanceId(context.Background(), instanceId, targetInstanceId).Limit(limit).Offset(offset).Sort(sort).Name(name).Version(version).Status(status).CreatedBy(createdBy).Wordlist(wordlist).Frida(frida).CorelliumVersion(corelliumVersion).CreatedAt(createdAt).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3GetAssessmentsByInstanceId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetAssessmentsByInstanceId`: PaginatedAssessments
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsAPI.V3GetAssessmentsByInstanceId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**targetInstanceId** | **string** | ID of the instance whose assessments you want to list. Set this to the same value as &#x60;instanceId&#x60;; the path contains the ID twice only because of how the MATRIX service is routed. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetAssessmentsByInstanceIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **limit** | **float32** | Maximum number of assessments to return. Defaults to 100. | [default to 100]
 **offset** | **float32** | Number of assessments to skip before returning results. Defaults to 0. | [default to 0]
 **sort** | **string** | Comma-separated fields to order by; prefix a field with \&quot;-\&quot; for descending. Allowed fields: createdAt, status, name, version, score, wordlist, frida, corelliumVersion. Defaults to \&quot;-createdAt\&quot;. | 
 **name** | **string** | Filter by app name (exact match). | 
 **version** | **string** | Filter by app version (exact match). | 
 **status** | **string** | Filter by assessment status. | 
 **createdBy** | **string** | Filter by the user ID that created the assessment. | 
 **wordlist** | **string** | Filter by wordlist name. Use \&quot;None\&quot; to return assessments without a wordlist. | 
 **frida** | **string** | Filter by Frida script name. Use \&quot;None\&quot; to return assessments without a Frida script. | 
 **corelliumVersion** | **string** | Filter by Corellium version (exact match). | 
 **createdAt** | **string** | Filter by test date. Accepts a single date (MM/DD/YYYY), a range (MM/DD/YYYY-MM/DD/YYYY), or a comma-separated list of dates and ranges. Dates are matched inclusive of the full day in UTC. | 

### Return type

[**PaginatedAssessments**](PaginatedAssessments.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchAssessment

> Assessment V3PatchAssessment(ctx, instanceId, assessmentId).UpdateAssessmentInput(updateAssessmentInput).Execute()

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
	resp, r, err := apiClient.AssessmentsAPI.V3PatchAssessment(context.Background(), instanceId, assessmentId).UpdateAssessmentInput(updateAssessmentInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3PatchAssessment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3PatchAssessment`: Assessment
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsAPI.V3PatchAssessment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchAssessmentRequest struct via the builder pattern


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


## V3RunTests

> AssessmentIdStatus V3RunTests(ctx, instanceId, assessmentId).TestAssessmentInput(testAssessmentInput).Execute()

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
	resp, r, err := apiClient.AssessmentsAPI.V3RunTests(context.Background(), instanceId, assessmentId).TestAssessmentInput(testAssessmentInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3RunTests``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3RunTests`: AssessmentIdStatus
	fmt.Fprintf(os.Stdout, "Response from `AssessmentsAPI.V3RunTests`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | ID of the instance (virtual device) the assessment belongs to. The platform checks that you have access to this instance before the request reaches MATRIX, so use the ID of an instance in one of your projects. | 
**assessmentId** | **string** | Identifier of the assessment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3RunTestsRequest struct via the builder pattern


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


## V3StartMonitoring

> V3StartMonitoring(ctx, instanceId, assessmentId).Execute()

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
	r, err := apiClient.AssessmentsAPI.V3StartMonitoring(context.Background(), instanceId, assessmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3StartMonitoring``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StartMonitoringRequest struct via the builder pattern


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


## V3StopMonitoring

> V3StopMonitoring(ctx, instanceId, assessmentId).Execute()

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
	r, err := apiClient.AssessmentsAPI.V3StopMonitoring(context.Background(), instanceId, assessmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssessmentsAPI.V3StopMonitoring``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV3StopMonitoringRequest struct via the builder pattern


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

