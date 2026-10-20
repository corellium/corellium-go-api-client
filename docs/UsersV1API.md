# \UsersV1API

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1ChangePasswordUsers**](UsersV1API.md#V1ChangePasswordUsers) | **Post** /v1/users/change-password | Change User Password
[**V1CreateUser**](UsersV1API.md#V1CreateUser) | **Post** /v1/users | Create User
[**V1DeleteUser**](UsersV1API.md#V1DeleteUser) | **Delete** /v1/users/{userId} | Delete User
[**V1GetResetLinkInfo**](UsersV1API.md#V1GetResetLinkInfo) | **Get** /v1/users/reset-link-info | Send Password Reset Link Info
[**V1ResetUserPassword**](UsersV1API.md#V1ResetUserPassword) | **Post** /v1/users/reset-password | Reset User Password
[**V1SendUserResetLink**](UsersV1API.md#V1SendUserResetLink) | **Post** /v1/users/send-reset-link | Send Password Reset Link
[**V1UpdateUser**](UsersV1API.md#V1UpdateUser) | **Patch** /v1/users/{userId} | Update User
[**V1UserAgreeTerms**](UsersV1API.md#V1UserAgreeTerms) | **Post** /v1/users/agree | Consent to the current terms and conditions
[**V1UsersLogin**](UsersV1API.md#V1UsersLogin) | **Post** /v1/users/login | Log In



## V1ChangePasswordUsers

> V1ChangePasswordUsers(ctx).PasswordChangeBody(passwordChangeBody).Execute()

Change User Password



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
	passwordChangeBody := *openapiclient.NewPasswordChangeBody("User_example", "OldPassword_example", "NewPassword_example") // PasswordChangeBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersV1API.V1ChangePasswordUsers(context.Background()).PasswordChangeBody(passwordChangeBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersV1API.V1ChangePasswordUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ChangePasswordUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **passwordChangeBody** | [**PasswordChangeBody**](PasswordChangeBody.md) |  | 

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


## V1CreateUser

> UserCreateReturn V1CreateUser(ctx).UserCreate(userCreate).Execute()

Create User

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
	userCreate := *openapiclient.NewUserCreate() // UserCreate | User data

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersV1API.V1CreateUser(context.Background()).UserCreate(userCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersV1API.V1CreateUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CreateUser`: UserCreateReturn
	fmt.Fprintf(os.Stdout, "Response from `UsersV1API.V1CreateUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CreateUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userCreate** | [**UserCreate**](UserCreate.md) | User data | 

### Return type

[**UserCreateReturn**](UserCreateReturn.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DeleteUser

> V1DeleteUser(ctx, userId).Execute()

Delete User

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
	userId := "userId_example" // string | userId - uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersV1API.V1DeleteUser(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersV1API.V1DeleteUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | userId - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DeleteUserRequest struct via the builder pattern


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


## V1GetResetLinkInfo

> ResetLinkInfoReturn V1GetResetLinkInfo(ctx).Token(token).Execute()

Send Password Reset Link Info

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
	token := "token_example" // string | Reset token

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersV1API.V1GetResetLinkInfo(context.Background()).Token(token).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersV1API.V1GetResetLinkInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1GetResetLinkInfo`: ResetLinkInfoReturn
	fmt.Fprintf(os.Stdout, "Response from `UsersV1API.V1GetResetLinkInfo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1GetResetLinkInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string** | Reset token | 

### Return type

[**ResetLinkInfoReturn**](ResetLinkInfoReturn.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1ResetUserPassword

> V1ResetUserPassword(ctx).PasswordResetBody(passwordResetBody).Execute()

Reset User Password

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
	passwordResetBody := *openapiclient.NewPasswordResetBody("Token_example", "TotpToken_example", "NewPassword_example") // PasswordResetBody | application/json

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersV1API.V1ResetUserPassword(context.Background()).PasswordResetBody(passwordResetBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersV1API.V1ResetUserPassword``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1ResetUserPasswordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **passwordResetBody** | [**PasswordResetBody**](PasswordResetBody.md) | application/json | 

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


## V1SendUserResetLink

> V1SendUserResetLink(ctx).ResetLinkBody(resetLinkBody).Execute()

Send Password Reset Link

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
	resetLinkBody := *openapiclient.NewResetLinkBody("Email_example") // ResetLinkBody | application/json

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersV1API.V1SendUserResetLink(context.Background()).ResetLinkBody(resetLinkBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersV1API.V1SendUserResetLink``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1SendUserResetLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **resetLinkBody** | [**ResetLinkBody**](ResetLinkBody.md) | application/json | 

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


## V1UpdateUser

> V1UpdateUser(ctx, userId).UserUpdate(userUpdate).Execute()

Update User



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
	userId := "userId_example" // string | userId - uuid
	userUpdate := *openapiclient.NewUserUpdate() // UserUpdate | User data

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersV1API.V1UpdateUser(context.Background(), userId).UserUpdate(userUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersV1API.V1UpdateUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | userId - uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1UpdateUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **userUpdate** | [**UserUpdate**](UserUpdate.md) | User data | 

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


## V1UserAgreeTerms

> AgreedAckV1 V1UserAgreeTerms(ctx).Execute()

Consent to the current terms and conditions

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
	resp, r, err := apiClient.UsersV1API.V1UserAgreeTerms(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersV1API.V1UserAgreeTerms``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UserAgreeTerms`: AgreedAckV1
	fmt.Fprintf(os.Stdout, "Response from `UsersV1API.V1UserAgreeTerms`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1UserAgreeTermsRequest struct via the builder pattern


### Return type

[**AgreedAckV1**](AgreedAckV1.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UsersLogin

> TokenV1 V1UsersLogin(ctx).Credentials(credentials).Execute()

Log In

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
	credentials := *openapiclient.NewCredentials("Username_example", "Password_example") // Credentials | Authorization data

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersV1API.V1UsersLogin(context.Background()).Credentials(credentials).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersV1API.V1UsersLogin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UsersLogin`: TokenV1
	fmt.Fprintf(os.Stdout, "Response from `UsersV1API.V1UsersLogin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1UsersLoginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **credentials** | [**Credentials**](Credentials.md) | Authorization data | 

### Return type

[**TokenV1**](TokenV1.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

