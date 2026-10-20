# DomainListItemDomainUsageInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **string** | Domain identifier. | 
**Month** | **string** | Month (YYYY-MM-DD format). | 
**Hours** | **float32** | Usage hours for the month. | 

## Methods

### NewDomainListItemDomainUsageInner

`func NewDomainListItemDomainUsageInner(domain string, month string, hours float32, ) *DomainListItemDomainUsageInner`

NewDomainListItemDomainUsageInner instantiates a new DomainListItemDomainUsageInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListItemDomainUsageInnerWithDefaults

`func NewDomainListItemDomainUsageInnerWithDefaults() *DomainListItemDomainUsageInner`

NewDomainListItemDomainUsageInnerWithDefaults instantiates a new DomainListItemDomainUsageInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *DomainListItemDomainUsageInner) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *DomainListItemDomainUsageInner) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *DomainListItemDomainUsageInner) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetMonth

`func (o *DomainListItemDomainUsageInner) GetMonth() string`

GetMonth returns the Month field if non-nil, zero value otherwise.

### GetMonthOk

`func (o *DomainListItemDomainUsageInner) GetMonthOk() (*string, bool)`

GetMonthOk returns a tuple with the Month field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonth

`func (o *DomainListItemDomainUsageInner) SetMonth(v string)`

SetMonth sets Month field to given value.


### GetHours

`func (o *DomainListItemDomainUsageInner) GetHours() float32`

GetHours returns the Hours field if non-nil, zero value otherwise.

### GetHoursOk

`func (o *DomainListItemDomainUsageInner) GetHoursOk() (*float32, bool)`

GetHoursOk returns a tuple with the Hours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHours

`func (o *DomainListItemDomainUsageInner) SetHours(v float32)`

SetHours sets Hours field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


