# BillingSummaryPendingUsageBased

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LastBillDate** | **float32** | Last bill unix timestamp (ms). | 
**NextBillDate** | **float32** | Next bill unix timestamp (ms). | 
**BillingThreshold** | **float32** | Dollar threshold that triggers a usage bill. | 
**Total** | **string** | Pending total in dollars, as a fixed two-decimal string. | 
**LineItems** | [**[]BillingLineItem**](BillingLineItem.md) | Pending usage line items. May be empty. | 

## Methods

### NewBillingSummaryPendingUsageBased

`func NewBillingSummaryPendingUsageBased(lastBillDate float32, nextBillDate float32, billingThreshold float32, total string, lineItems []BillingLineItem, ) *BillingSummaryPendingUsageBased`

NewBillingSummaryPendingUsageBased instantiates a new BillingSummaryPendingUsageBased object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBillingSummaryPendingUsageBasedWithDefaults

`func NewBillingSummaryPendingUsageBasedWithDefaults() *BillingSummaryPendingUsageBased`

NewBillingSummaryPendingUsageBasedWithDefaults instantiates a new BillingSummaryPendingUsageBased object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLastBillDate

`func (o *BillingSummaryPendingUsageBased) GetLastBillDate() float32`

GetLastBillDate returns the LastBillDate field if non-nil, zero value otherwise.

### GetLastBillDateOk

`func (o *BillingSummaryPendingUsageBased) GetLastBillDateOk() (*float32, bool)`

GetLastBillDateOk returns a tuple with the LastBillDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastBillDate

`func (o *BillingSummaryPendingUsageBased) SetLastBillDate(v float32)`

SetLastBillDate sets LastBillDate field to given value.


### GetNextBillDate

`func (o *BillingSummaryPendingUsageBased) GetNextBillDate() float32`

GetNextBillDate returns the NextBillDate field if non-nil, zero value otherwise.

### GetNextBillDateOk

`func (o *BillingSummaryPendingUsageBased) GetNextBillDateOk() (*float32, bool)`

GetNextBillDateOk returns a tuple with the NextBillDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextBillDate

`func (o *BillingSummaryPendingUsageBased) SetNextBillDate(v float32)`

SetNextBillDate sets NextBillDate field to given value.


### GetBillingThreshold

`func (o *BillingSummaryPendingUsageBased) GetBillingThreshold() float32`

GetBillingThreshold returns the BillingThreshold field if non-nil, zero value otherwise.

### GetBillingThresholdOk

`func (o *BillingSummaryPendingUsageBased) GetBillingThresholdOk() (*float32, bool)`

GetBillingThresholdOk returns a tuple with the BillingThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingThreshold

`func (o *BillingSummaryPendingUsageBased) SetBillingThreshold(v float32)`

SetBillingThreshold sets BillingThreshold field to given value.


### GetTotal

`func (o *BillingSummaryPendingUsageBased) GetTotal() string`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *BillingSummaryPendingUsageBased) GetTotalOk() (*string, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *BillingSummaryPendingUsageBased) SetTotal(v string)`

SetTotal sets Total field to given value.


### GetLineItems

`func (o *BillingSummaryPendingUsageBased) GetLineItems() []BillingLineItem`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *BillingSummaryPendingUsageBased) GetLineItemsOk() (*[]BillingLineItem, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *BillingSummaryPendingUsageBased) SetLineItems(v []BillingLineItem)`

SetLineItems sets LineItems field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


