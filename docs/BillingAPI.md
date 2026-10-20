# \BillingAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CancelSubscription**](BillingAPI.md#V3CancelSubscription) | **Post** /v3/billing/cancel | Cancel a subscription
[**V3GetBillingSummary**](BillingAPI.md#V3GetBillingSummary) | **Get** /v3/billing/summary | Get billing summary
[**V3GetDeviceUsage**](BillingAPI.md#V3GetDeviceUsage) | **Get** /v3/billing/usage | Get device usage
[**V3GetMeteredSubscriptionUsage**](BillingAPI.md#V3GetMeteredSubscriptionUsage) | **Get** /v3/billing/subscription/metered/usage | Get metered subscription usage
[**V3GetSubscription**](BillingAPI.md#V3GetSubscription) | **Get** /v3/billing/subscription | Get the current subscription
[**V3SubscribeToTrial**](BillingAPI.md#V3SubscribeToTrial) | **Post** /v3/billing/trials/subscribe | Subscribe to a trial
[**V3UncancelSubscription**](BillingAPI.md#V3UncancelSubscription) | **Post** /v3/billing/uncancel | Uncancel a subscription



## V3CancelSubscription

> V3CancelSubscription(ctx).CancelSubscriptionBody(cancelSubscriptionBody).Execute()

Cancel a subscription



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
	cancelSubscriptionBody := *openapiclient.NewCancelSubscriptionBody() // CancelSubscriptionBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.BillingAPI.V3CancelSubscription(context.Background()).CancelSubscriptionBody(cancelSubscriptionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.V3CancelSubscription``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CancelSubscriptionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cancelSubscriptionBody** | [**CancelSubscriptionBody**](CancelSubscriptionBody.md) |  | 

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


## V3GetBillingSummary

> BillingSummary V3GetBillingSummary(ctx).Execute()

Get billing summary



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
	resp, r, err := apiClient.BillingAPI.V3GetBillingSummary(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.V3GetBillingSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetBillingSummary`: BillingSummary
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.V3GetBillingSummary`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetBillingSummaryRequest struct via the builder pattern


### Return type

[**BillingSummary**](BillingSummary.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetDeviceUsage

> DeviceUsage V3GetDeviceUsage(ctx).Execute()

Get device usage



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
	resp, r, err := apiClient.BillingAPI.V3GetDeviceUsage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.V3GetDeviceUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetDeviceUsage`: DeviceUsage
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.V3GetDeviceUsage`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetDeviceUsageRequest struct via the builder pattern


### Return type

[**DeviceUsage**](DeviceUsage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetMeteredSubscriptionUsage

> MeteredSubscriptionUsage V3GetMeteredSubscriptionUsage(ctx).Execute()

Get metered subscription usage



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
	resp, r, err := apiClient.BillingAPI.V3GetMeteredSubscriptionUsage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.V3GetMeteredSubscriptionUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetMeteredSubscriptionUsage`: MeteredSubscriptionUsage
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.V3GetMeteredSubscriptionUsage`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetMeteredSubscriptionUsageRequest struct via the builder pattern


### Return type

[**MeteredSubscriptionUsage**](MeteredSubscriptionUsage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetSubscription

> Subscription V3GetSubscription(ctx).Execute()

Get the current subscription



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
	resp, r, err := apiClient.BillingAPI.V3GetSubscription(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.V3GetSubscription``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetSubscription`: Subscription
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.V3GetSubscription`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GetSubscriptionRequest struct via the builder pattern


### Return type

[**Subscription**](Subscription.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3SubscribeToTrial

> map[string]interface{} V3SubscribeToTrial(ctx).SubscribeToTrialBody(subscribeToTrialBody).Execute()

Subscribe to a trial



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
	subscribeToTrialBody := *openapiclient.NewSubscribeToTrialBody() // SubscribeToTrialBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.V3SubscribeToTrial(context.Background()).SubscribeToTrialBody(subscribeToTrialBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.V3SubscribeToTrial``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3SubscribeToTrial`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.V3SubscribeToTrial`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3SubscribeToTrialRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subscribeToTrialBody** | [**SubscribeToTrialBody**](SubscribeToTrialBody.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3UncancelSubscription

> V3UncancelSubscription(ctx).UncancelSubscriptionBody(uncancelSubscriptionBody).Execute()

Uncancel a subscription



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
	uncancelSubscriptionBody := *openapiclient.NewUncancelSubscriptionBody() // UncancelSubscriptionBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.BillingAPI.V3UncancelSubscription(context.Background()).UncancelSubscriptionBody(uncancelSubscriptionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.V3UncancelSubscription``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3UncancelSubscriptionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **uncancelSubscriptionBody** | [**UncancelSubscriptionBody**](UncancelSubscriptionBody.md) |  | 

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

