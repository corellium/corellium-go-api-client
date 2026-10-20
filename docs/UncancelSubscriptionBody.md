# UncancelSubscriptionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DomainId** | Pointer to **string** | Domain to uncancel (defaults to the caller domain). | [optional] 

## Methods

### NewUncancelSubscriptionBody

`func NewUncancelSubscriptionBody() *UncancelSubscriptionBody`

NewUncancelSubscriptionBody instantiates a new UncancelSubscriptionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUncancelSubscriptionBodyWithDefaults

`func NewUncancelSubscriptionBodyWithDefaults() *UncancelSubscriptionBody`

NewUncancelSubscriptionBodyWithDefaults instantiates a new UncancelSubscriptionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomainId

`func (o *UncancelSubscriptionBody) GetDomainId() string`

GetDomainId returns the DomainId field if non-nil, zero value otherwise.

### GetDomainIdOk

`func (o *UncancelSubscriptionBody) GetDomainIdOk() (*string, bool)`

GetDomainIdOk returns a tuple with the DomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainId

`func (o *UncancelSubscriptionBody) SetDomainId(v string)`

SetDomainId sets DomainId field to given value.

### HasDomainId

`func (o *UncancelSubscriptionBody) HasDomainId() bool`

HasDomainId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


