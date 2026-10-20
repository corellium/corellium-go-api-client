# \TOTPAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3DisableTotp**](TOTPAPI.md#V3DisableTotp) | **Post** /v3/totp/disable | Disable TOTP for this user
[**V3EnableTotp**](TOTPAPI.md#V3EnableTotp) | **Post** /v3/totp/enable | Enable TOTP for this user
[**V3GenerateTotp**](TOTPAPI.md#V3GenerateTotp) | **Post** /v3/totp/generate | Generate a TOTP secret



## V3DisableTotp

> LoginResult V3DisableTotp(ctx).TotpDisableBody(totpDisableBody).Execute()

Disable TOTP for this user



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
	totpDisableBody := *openapiclient.NewTotpDisableBody("123456", "<redacted>") // TotpDisableBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TOTPAPI.V3DisableTotp(context.Background()).TotpDisableBody(totpDisableBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TOTPAPI.V3DisableTotp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3DisableTotp`: LoginResult
	fmt.Fprintf(os.Stdout, "Response from `TOTPAPI.V3DisableTotp`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3DisableTotpRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **totpDisableBody** | [**TotpDisableBody**](TotpDisableBody.md) |  | 

### Return type

[**LoginResult**](LoginResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3EnableTotp

> LoginResult V3EnableTotp(ctx).TotpEnableBody(totpEnableBody).Execute()

Enable TOTP for this user



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
	totpEnableBody := *openapiclient.NewTotpEnableBody("<totp-secret>", "123456", "<redacted>") // TotpEnableBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TOTPAPI.V3EnableTotp(context.Background()).TotpEnableBody(totpEnableBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TOTPAPI.V3EnableTotp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3EnableTotp`: LoginResult
	fmt.Fprintf(os.Stdout, "Response from `TOTPAPI.V3EnableTotp`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3EnableTotpRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **totpEnableBody** | [**TotpEnableBody**](TotpEnableBody.md) |  | 

### Return type

[**LoginResult**](LoginResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GenerateTotp

> TotpGenerateResponse V3GenerateTotp(ctx).Execute()

Generate a TOTP secret



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
	resp, r, err := apiClient.TOTPAPI.V3GenerateTotp(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TOTPAPI.V3GenerateTotp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GenerateTotp`: TotpGenerateResponse
	fmt.Fprintf(os.Stdout, "Response from `TOTPAPI.V3GenerateTotp`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3GenerateTotpRequest struct via the builder pattern


### Return type

[**TotpGenerateResponse**](TotpGenerateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

