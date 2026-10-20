# \InvitesAPI

All URIs are relative to *https://app.corellium.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V3CreateInvites**](InvitesAPI.md#V3CreateInvites) | **Post** /v3/invites | Create invites
[**V3EditInvites**](InvitesAPI.md#V3EditInvites) | **Post** /v3/invites/edit | Edit invites
[**V3GetInviteByToken**](InvitesAPI.md#V3GetInviteByToken) | **Post** /v3/invites-by-token | Get an invite by token
[**V3ListInvites**](InvitesAPI.md#V3ListInvites) | **Get** /v3/invites | List invites
[**V3RevokeInvites**](InvitesAPI.md#V3RevokeInvites) | **Post** /v3/invites/revoke | Revoke invites
[**V3SignupFromInvite**](InvitesAPI.md#V3SignupFromInvite) | **Post** /v3/invites/signup | Sign up from an invite



## V3CreateInvites

> map[string]InviteResult V3CreateInvites(ctx).CreateInvitesBody(createInvitesBody).Execute()

Create invites



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
	createInvitesBody := *openapiclient.NewCreateInvitesBody([]string{"Email_example"}) // CreateInvitesBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvitesAPI.V3CreateInvites(context.Background()).CreateInvitesBody(createInvitesBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvitesAPI.V3CreateInvites``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3CreateInvites`: map[string]InviteResult
	fmt.Fprintf(os.Stdout, "Response from `InvitesAPI.V3CreateInvites`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3CreateInvitesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createInvitesBody** | [**CreateInvitesBody**](CreateInvitesBody.md) |  | 

### Return type

[**map[string]InviteResult**](InviteResult.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3EditInvites

> Invitation V3EditInvites(ctx).EditInvitesBody(editInvitesBody).Execute()

Edit invites



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
	editInvitesBody := *openapiclient.NewEditInvitesBody([]string{"Ids_example"}, *openapiclient.NewEditInvitesBodyChanges()) // EditInvitesBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvitesAPI.V3EditInvites(context.Background()).EditInvitesBody(editInvitesBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvitesAPI.V3EditInvites``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3EditInvites`: Invitation
	fmt.Fprintf(os.Stdout, "Response from `InvitesAPI.V3EditInvites`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3EditInvitesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **editInvitesBody** | [**EditInvitesBody**](EditInvitesBody.md) |  | 

### Return type

[**Invitation**](Invitation.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3GetInviteByToken

> InvitationByToken V3GetInviteByToken(ctx).GetInviteByTokenBody(getInviteByTokenBody).Execute()

Get an invite by token



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
	getInviteByTokenBody := *openapiclient.NewGetInviteByTokenBody("<token>") // GetInviteByTokenBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvitesAPI.V3GetInviteByToken(context.Background()).GetInviteByTokenBody(getInviteByTokenBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvitesAPI.V3GetInviteByToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3GetInviteByToken`: InvitationByToken
	fmt.Fprintf(os.Stdout, "Response from `InvitesAPI.V3GetInviteByToken`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3GetInviteByTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getInviteByTokenBody** | [**GetInviteByTokenBody**](GetInviteByTokenBody.md) |  | 

### Return type

[**InvitationByToken**](InvitationByToken.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3ListInvites

> InvitesListResponse V3ListInvites(ctx).Limit(limit).Offset(offset).Execute()

List invites



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvitesAPI.V3ListInvites(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvitesAPI.V3ListInvites``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3ListInvites`: InvitesListResponse
	fmt.Fprintf(os.Stdout, "Response from `InvitesAPI.V3ListInvites`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3ListInvitesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Most results to return in one page. Whole number from 1 to 1000; defaults to 100. A value outside that range is rejected with 400. | [default to 100]
 **offset** | **float32** | How many results to skip before this page starts; defaults to 0. To get the next page, add &#x60;limit&#x60; to the previous &#x60;offset&#x60;. | [default to 0]

### Return type

[**InvitesListResponse**](InvitesListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3RevokeInvites

> RevokeInvitesResponse V3RevokeInvites(ctx).RevokeInvitesBody(revokeInvitesBody).Execute()

Revoke invites



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
	revokeInvitesBody := *openapiclient.NewRevokeInvitesBody([]string{"Ids_example"}) // RevokeInvitesBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvitesAPI.V3RevokeInvites(context.Background()).RevokeInvitesBody(revokeInvitesBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvitesAPI.V3RevokeInvites``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3RevokeInvites`: RevokeInvitesResponse
	fmt.Fprintf(os.Stdout, "Response from `InvitesAPI.V3RevokeInvites`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3RevokeInvitesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revokeInvitesBody** | [**RevokeInvitesBody**](RevokeInvitesBody.md) |  | 

### Return type

[**RevokeInvitesResponse**](RevokeInvitesResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V3SignupFromInvite

> InviteSignupResponse V3SignupFromInvite(ctx).InviteSignupBody(inviteSignupBody).Execute()

Sign up from an invite



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
	inviteSignupBody := *openapiclient.NewInviteSignupBody("<token>", *openapiclient.NewInviteSignupBodyParams("<redacted>", "Jane Doe", true)) // InviteSignupBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvitesAPI.V3SignupFromInvite(context.Background()).InviteSignupBody(inviteSignupBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvitesAPI.V3SignupFromInvite``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V3SignupFromInvite`: InviteSignupResponse
	fmt.Fprintf(os.Stdout, "Response from `InvitesAPI.V3SignupFromInvite`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV3SignupFromInviteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inviteSignupBody** | [**InviteSignupBody**](InviteSignupBody.md) |  | 

### Return type

[**InviteSignupResponse**](InviteSignupResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

