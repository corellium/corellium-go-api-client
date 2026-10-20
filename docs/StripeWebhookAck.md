# StripeWebhookAck

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Received** | **bool** | Whether the event was received. | 
**Ignored** | Pointer to **string** | Reason the event was ignored, when applicable. | [optional] 

## Methods

### NewStripeWebhookAck

`func NewStripeWebhookAck(received bool, ) *StripeWebhookAck`

NewStripeWebhookAck instantiates a new StripeWebhookAck object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStripeWebhookAckWithDefaults

`func NewStripeWebhookAckWithDefaults() *StripeWebhookAck`

NewStripeWebhookAckWithDefaults instantiates a new StripeWebhookAck object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReceived

`func (o *StripeWebhookAck) GetReceived() bool`

GetReceived returns the Received field if non-nil, zero value otherwise.

### GetReceivedOk

`func (o *StripeWebhookAck) GetReceivedOk() (*bool, bool)`

GetReceivedOk returns a tuple with the Received field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceived

`func (o *StripeWebhookAck) SetReceived(v bool)`

SetReceived sets Received field to given value.


### GetIgnored

`func (o *StripeWebhookAck) GetIgnored() string`

GetIgnored returns the Ignored field if non-nil, zero value otherwise.

### GetIgnoredOk

`func (o *StripeWebhookAck) GetIgnoredOk() (*string, bool)`

GetIgnoredOk returns a tuple with the Ignored field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnored

`func (o *StripeWebhookAck) SetIgnored(v string)`

SetIgnored sets Ignored field to given value.

### HasIgnored

`func (o *StripeWebhookAck) HasIgnored() bool`

HasIgnored returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


