# CancelSubscriptionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DomainId** | Pointer to **string** | Domain to cancel (defaults to the caller domain). | [optional] 
**DeleteDomain** | Pointer to **bool** | Delete the domain as part of cancellation. | [optional] 

## Methods

### NewCancelSubscriptionBody

`func NewCancelSubscriptionBody() *CancelSubscriptionBody`

NewCancelSubscriptionBody instantiates a new CancelSubscriptionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCancelSubscriptionBodyWithDefaults

`func NewCancelSubscriptionBodyWithDefaults() *CancelSubscriptionBody`

NewCancelSubscriptionBodyWithDefaults instantiates a new CancelSubscriptionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomainId

`func (o *CancelSubscriptionBody) GetDomainId() string`

GetDomainId returns the DomainId field if non-nil, zero value otherwise.

### GetDomainIdOk

`func (o *CancelSubscriptionBody) GetDomainIdOk() (*string, bool)`

GetDomainIdOk returns a tuple with the DomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainId

`func (o *CancelSubscriptionBody) SetDomainId(v string)`

SetDomainId sets DomainId field to given value.

### HasDomainId

`func (o *CancelSubscriptionBody) HasDomainId() bool`

HasDomainId returns a boolean if a field has been set.

### GetDeleteDomain

`func (o *CancelSubscriptionBody) GetDeleteDomain() bool`

GetDeleteDomain returns the DeleteDomain field if non-nil, zero value otherwise.

### GetDeleteDomainOk

`func (o *CancelSubscriptionBody) GetDeleteDomainOk() (*bool, bool)`

GetDeleteDomainOk returns a tuple with the DeleteDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleteDomain

`func (o *CancelSubscriptionBody) SetDeleteDomain(v bool)`

SetDeleteDomain sets DeleteDomain field to given value.

### HasDeleteDomain

`func (o *CancelSubscriptionBody) HasDeleteDomain() bool`

HasDeleteDomain returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


