# StripeCheckoutCompleteBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SessionId** | **string** | Stripe checkout session identifier. | 

## Methods

### NewStripeCheckoutCompleteBody

`func NewStripeCheckoutCompleteBody(sessionId string, ) *StripeCheckoutCompleteBody`

NewStripeCheckoutCompleteBody instantiates a new StripeCheckoutCompleteBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStripeCheckoutCompleteBodyWithDefaults

`func NewStripeCheckoutCompleteBodyWithDefaults() *StripeCheckoutCompleteBody`

NewStripeCheckoutCompleteBodyWithDefaults instantiates a new StripeCheckoutCompleteBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSessionId

`func (o *StripeCheckoutCompleteBody) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *StripeCheckoutCompleteBody) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *StripeCheckoutCompleteBody) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


