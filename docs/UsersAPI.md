# \UsersAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3AgreeToTerms**](UsersAPI.md#V3AgreeToTerms) | **Post** /v3/users/agree | Agree to terms
[**V3ChangePassword**](UsersAPI.md#V3ChangePassword) | **Post** /v3/users/change-password | Change password
[**V3CreateUser**](UsersAPI.md#V3CreateUser) | **Post** /v3/users | Create a user
[**V3DeleteUser**](UsersAPI.md#V3DeleteUser) | **Delete** /v3/users/{userId} | Delete a user
[**V3GetResetLinkInfo**](UsersAPI.md#V3GetResetLinkInfo) | **Post** /v3/users/reset-link-info | Get reset link info
[**V3PatchUser**](UsersAPI.md#V3PatchUser) | **Patch** /v3/users/{userId} | Update a user
[**V3ResetPassword**](UsersAPI.md#V3ResetPassword) | **Post** /v3/users/reset-password | Reset password
[**V3SendResetLink**](UsersAPI.md#V3SendResetLink) | **Post** /v3/users/send-reset-link | Send a password reset link
[**V3UpdateOwnProfile**](UsersAPI.md#V3UpdateOwnProfile) | **Patch** /v3/users/me | Update your profile



## V3AgreeToTerms

> AgreedAck V3AgreeToTerms(ctx).Execute()

Agree to terms



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
	resp, r, err := apiClient.UsersAPI.V3AgreeToTerms(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.V3AgreeToTerms``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3AgreeToTerms`: AgreedAck
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.V3AgreeToTerms`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV3AgreeToTermsRequest struct via the builder pattern


### Return type

[**AgreedAck**](AgreedAck.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ChangePassword

> V3ChangePassword(ctx).ChangePasswordBody(changePasswordBody).Execute()

Change password



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
	changePasswordBody := *openapiclient.NewChangePasswordBody("e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320", "<redacted>", "<redacted>") // ChangePasswordBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersAPI.V3ChangePassword(context.Background()).ChangePasswordBody(changePasswordBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.V3ChangePassword``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ChangePasswordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **changePasswordBody** | [**ChangePasswordBody**](ChangePasswordBody.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3CreateUser

> UserCreated V3CreateUser(ctx).CreateUserBody(createUserBody).Execute()

Create a user



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
	createUserBody := *openapiclient.NewCreateUserBody("jane.doe", "Domain Administrator") // CreateUserBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.V3CreateUser(context.Background()).CreateUserBody(createUserBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.V3CreateUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateUser`: UserCreated
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.V3CreateUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUserBody** | [**CreateUserBody**](CreateUserBody.md) |  | 

### Return type

[**UserCreated**](UserCreated.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3DeleteUser

> V3DeleteUser(ctx, userId).Execute()

Delete a user



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
	userId := "e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320" // string | User identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersAPI.V3DeleteUser(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.V3DeleteUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | User identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3DeleteUserRequest struct via the builder pattern


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


## V3GetResetLinkInfo

> ResetLinkInfo V3GetResetLinkInfo(ctx).GetResetLinkInfoBody(getResetLinkInfoBody).Execute()

Get reset link info



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
	getResetLinkInfoBody := *openapiclient.NewGetResetLinkInfoBody("<token>") // GetResetLinkInfoBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.V3GetResetLinkInfo(context.Background()).GetResetLinkInfoBody(getResetLinkInfoBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.V3GetResetLinkInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetResetLinkInfo`: ResetLinkInfo
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.V3GetResetLinkInfo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3GetResetLinkInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getResetLinkInfoBody** | [**GetResetLinkInfoBody**](GetResetLinkInfoBody.md) |  | 

### Return type

[**ResetLinkInfo**](ResetLinkInfo.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3PatchUser

> V3PatchUser(ctx, userId).PatchUserBody(patchUserBody).Execute()

Update a user



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
	userId := "e8c5b7ea-aa5f-4a4a-bdca-0c67060b5320" // string | User identifier.
	patchUserBody := *openapiclient.NewPatchUserBody() // PatchUserBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersAPI.V3PatchUser(context.Background(), userId).PatchUserBody(patchUserBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.V3PatchUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | User identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiV3PatchUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchUserBody** | [**PatchUserBody**](PatchUserBody.md) |  | 

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


## V3ResetPassword

> V3ResetPassword(ctx).ResetPasswordBody(resetPasswordBody).Execute()

Reset password



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
	resetPasswordBody := *openapiclient.NewResetPasswordBody("<token>", "<redacted>") // ResetPasswordBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersAPI.V3ResetPassword(context.Background()).ResetPasswordBody(resetPasswordBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.V3ResetPassword``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ResetPasswordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **resetPasswordBody** | [**ResetPasswordBody**](ResetPasswordBody.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3SendResetLink

> V3SendResetLink(ctx).SendResetLinkBody(sendResetLinkBody).Execute()

Send a password reset link



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
	sendResetLinkBody := *openapiclient.NewSendResetLinkBody() // SendResetLinkBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersAPI.V3SendResetLink(context.Background()).SendResetLinkBody(sendResetLinkBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.V3SendResetLink``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3SendResetLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendResetLinkBody** | [**SendResetLinkBody**](SendResetLinkBody.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3UpdateOwnProfile

> V3UpdateOwnProfile(ctx).UpdateOwnProfileBody(updateOwnProfileBody).Execute()

Update your profile



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
	updateOwnProfileBody := *openapiclient.NewUpdateOwnProfileBody("Jane Doe") // UpdateOwnProfileBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersAPI.V3UpdateOwnProfile(context.Background()).UpdateOwnProfileBody(updateOwnProfileBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.V3UpdateOwnProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3UpdateOwnProfileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateOwnProfileBody** | [**UpdateOwnProfileBody**](UpdateOwnProfileBody.md) |  | 

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

