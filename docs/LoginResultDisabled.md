# LoginResultDisabled

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Reason the domain is disabled. | 
**DisabledAt** | Pointer to **time.Time** | When the domain was disabled. Present for AllocatedHoursExpended. | [optional] 
**DeleteInstancesAt** | Pointer to **time.Time** | When the domain&#39;s instances will be deleted. | [optional] 
**CancelDate** | Pointer to **time.Time** | When the subscription was canceled. Present for SubscriptionCanceled. | [optional] 

## Methods

### NewLoginResultDisabled

`func NewLoginResultDisabled(type_ string, ) *LoginResultDisabled`

NewLoginResultDisabled instantiates a new LoginResultDisabled object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginResultDisabledWithDefaults

`func NewLoginResultDisabledWithDefaults() *LoginResultDisabled`

NewLoginResultDisabledWithDefaults instantiates a new LoginResultDisabled object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *LoginResultDisabled) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *LoginResultDisabled) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *LoginResultDisabled) SetType(v string)`

SetType sets Type field to given value.


### GetDisabledAt

`func (o *LoginResultDisabled) GetDisabledAt() time.Time`

GetDisabledAt returns the DisabledAt field if non-nil, zero value otherwise.

### GetDisabledAtOk

`func (o *LoginResultDisabled) GetDisabledAtOk() (*time.Time, bool)`

GetDisabledAtOk returns a tuple with the DisabledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabledAt

`func (o *LoginResultDisabled) SetDisabledAt(v time.Time)`

SetDisabledAt sets DisabledAt field to given value.

### HasDisabledAt

`func (o *LoginResultDisabled) HasDisabledAt() bool`

HasDisabledAt returns a boolean if a field has been set.

### GetDeleteInstancesAt

`func (o *LoginResultDisabled) GetDeleteInstancesAt() time.Time`

GetDeleteInstancesAt returns the DeleteInstancesAt field if non-nil, zero value otherwise.

### GetDeleteInstancesAtOk

`func (o *LoginResultDisabled) GetDeleteInstancesAtOk() (*time.Time, bool)`

GetDeleteInstancesAtOk returns a tuple with the DeleteInstancesAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleteInstancesAt

`func (o *LoginResultDisabled) SetDeleteInstancesAt(v time.Time)`

SetDeleteInstancesAt sets DeleteInstancesAt field to given value.

### HasDeleteInstancesAt

`func (o *LoginResultDisabled) HasDeleteInstancesAt() bool`

HasDeleteInstancesAt returns a boolean if a field has been set.

### GetCancelDate

`func (o *LoginResultDisabled) GetCancelDate() time.Time`

GetCancelDate returns the CancelDate field if non-nil, zero value otherwise.

### GetCancelDateOk

`func (o *LoginResultDisabled) GetCancelDateOk() (*time.Time, bool)`

GetCancelDateOk returns a tuple with the CancelDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelDate

`func (o *LoginResultDisabled) SetCancelDate(v time.Time)`

SetCancelDate sets CancelDate field to given value.

### HasCancelDate

`func (o *LoginResultDisabled) HasCancelDate() bool`

HasCancelDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


