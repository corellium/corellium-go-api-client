# ApiTokenResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiToken** | **string** | The generated API token. Returned only once and cannot be retrieved later, so store it securely. Use it wherever an API token is accepted, such as the &#x60;apiToken&#x60; field of POST /v3/auth/login. | 

## Methods

### NewApiTokenResult

`func NewApiTokenResult(apiToken string, ) *ApiTokenResult`

NewApiTokenResult instantiates a new ApiTokenResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiTokenResultWithDefaults

`func NewApiTokenResultWithDefaults() *ApiTokenResult`

NewApiTokenResultWithDefaults instantiates a new ApiTokenResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiToken

`func (o *ApiTokenResult) GetApiToken() string`

GetApiToken returns the ApiToken field if non-nil, zero value otherwise.

### GetApiTokenOk

`func (o *ApiTokenResult) GetApiTokenOk() (*string, bool)`

GetApiTokenOk returns a tuple with the ApiToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiToken

`func (o *ApiTokenResult) SetApiToken(v string)`

SetApiToken sets ApiToken field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


