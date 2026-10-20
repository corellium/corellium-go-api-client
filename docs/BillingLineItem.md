# BillingLineItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Usage category name. | 
**Name** | **string** | Line item name. | 
**ShortName** | **string** | Short line item name. | 
**Description** | **string** | Line item description. May be empty. | 
**Quantity** | **float32** | Units used. | 
**UnitCost** | **float32** | Cost per unit. | 

## Methods

### NewBillingLineItem

`func NewBillingLineItem(type_ string, name string, shortName string, description string, quantity float32, unitCost float32, ) *BillingLineItem`

NewBillingLineItem instantiates a new BillingLineItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBillingLineItemWithDefaults

`func NewBillingLineItemWithDefaults() *BillingLineItem`

NewBillingLineItemWithDefaults instantiates a new BillingLineItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *BillingLineItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *BillingLineItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *BillingLineItem) SetType(v string)`

SetType sets Type field to given value.


### GetName

`func (o *BillingLineItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BillingLineItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BillingLineItem) SetName(v string)`

SetName sets Name field to given value.


### GetShortName

`func (o *BillingLineItem) GetShortName() string`

GetShortName returns the ShortName field if non-nil, zero value otherwise.

### GetShortNameOk

`func (o *BillingLineItem) GetShortNameOk() (*string, bool)`

GetShortNameOk returns a tuple with the ShortName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortName

`func (o *BillingLineItem) SetShortName(v string)`

SetShortName sets ShortName field to given value.


### GetDescription

`func (o *BillingLineItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *BillingLineItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *BillingLineItem) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetQuantity

`func (o *BillingLineItem) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *BillingLineItem) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *BillingLineItem) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.


### GetUnitCost

`func (o *BillingLineItem) GetUnitCost() float32`

GetUnitCost returns the UnitCost field if non-nil, zero value otherwise.

### GetUnitCostOk

`func (o *BillingLineItem) GetUnitCostOk() (*float32, bool)`

GetUnitCostOk returns a tuple with the UnitCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitCost

`func (o *BillingLineItem) SetUnitCost(v float32)`

SetUnitCost sets UnitCost field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


