# LoginResultDomainDisabled

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Reason the domain is disabled. | [optional] 
**CancelDate** | Pointer to **time.Time** | When the subscription was canceled. | [optional] 

## Methods

### NewLoginResultDomainDisabled

`func NewLoginResultDomainDisabled() *LoginResultDomainDisabled`

NewLoginResultDomainDisabled instantiates a new LoginResultDomainDisabled object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginResultDomainDisabledWithDefaults

`func NewLoginResultDomainDisabledWithDefaults() *LoginResultDomainDisabled`

NewLoginResultDomainDisabledWithDefaults instantiates a new LoginResultDomainDisabled object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *LoginResultDomainDisabled) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *LoginResultDomainDisabled) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *LoginResultDomainDisabled) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *LoginResultDomainDisabled) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCancelDate

`func (o *LoginResultDomainDisabled) GetCancelDate() time.Time`

GetCancelDate returns the CancelDate field if non-nil, zero value otherwise.

### GetCancelDateOk

`func (o *LoginResultDomainDisabled) GetCancelDateOk() (*time.Time, bool)`

GetCancelDateOk returns a tuple with the CancelDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelDate

`func (o *LoginResultDomainDisabled) SetCancelDate(v time.Time)`

SetCancelDate sets CancelDate field to given value.

### HasCancelDate

`func (o *LoginResultDomainDisabled) HasCancelDate() bool`

HasCancelDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


