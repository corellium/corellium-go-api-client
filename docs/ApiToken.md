# ApiToken

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiToken** | **string** | Persistent API key created by the user (in the web UI or via POST /v3/auth/apitoken), used as an alternative to username/password. An opaque string, sent back verbatim. Also accepted as an Authorization Bearer credential and stored by the CLI as --token. Distinct from the session token. | 

## Methods

### NewApiToken

`func NewApiToken(apiToken string, ) *ApiToken`

NewApiToken instantiates a new ApiToken object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiTokenWithDefaults

`func NewApiTokenWithDefaults() *ApiToken`

NewApiTokenWithDefaults instantiates a new ApiToken object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiToken

`func (o *ApiToken) GetApiToken() string`

GetApiToken returns the ApiToken field if non-nil, zero value otherwise.

### GetApiTokenOk

`func (o *ApiToken) GetApiTokenOk() (*string, bool)`

GetApiTokenOk returns a tuple with the ApiToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiToken

`func (o *ApiToken) SetApiToken(v string)`

SetApiToken sets ApiToken field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


