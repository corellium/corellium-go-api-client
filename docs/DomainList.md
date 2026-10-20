# DomainList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **float32** | Total number of domains. | 
**Page** | **float32** | Current page number. | 
**PerPage** | **float32** | Items per page. | 
**Items** | [**[]DomainListItem**](DomainListItem.md) | Domain items. | 
**Usage** | [**DomainListUsage**](DomainListUsage.md) |  | 

## Methods

### NewDomainList

`func NewDomainList(count float32, page float32, perPage float32, items []DomainListItem, usage DomainListUsage, ) *DomainList`

NewDomainList instantiates a new DomainList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListWithDefaults

`func NewDomainListWithDefaults() *DomainList`

NewDomainListWithDefaults instantiates a new DomainList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *DomainList) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *DomainList) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *DomainList) SetCount(v float32)`

SetCount sets Count field to given value.


### GetPage

`func (o *DomainList) GetPage() float32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *DomainList) GetPageOk() (*float32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *DomainList) SetPage(v float32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *DomainList) GetPerPage() float32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *DomainList) GetPerPageOk() (*float32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *DomainList) SetPerPage(v float32)`

SetPerPage sets PerPage field to given value.


### GetItems

`func (o *DomainList) GetItems() []DomainListItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *DomainList) GetItemsOk() (*[]DomainListItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *DomainList) SetItems(v []DomainListItem)`

SetItems sets Items field to given value.


### GetUsage

`func (o *DomainList) GetUsage() DomainListUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *DomainList) GetUsageOk() (*DomainListUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *DomainList) SetUsage(v DomainListUsage)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


