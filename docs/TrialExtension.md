# TrialExtension

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Duration** | **float32** | Number of additional days requested. | 
**Reason** | Pointer to **string** | Reason for the extension request. | [optional] 
**Denied** | Pointer to **bool** | Whether the request was denied. | [optional] 
**DeniedReason** | Pointer to **string** | Explanation for why the request was denied. | [optional] 

## Methods

### NewTrialExtension

`func NewTrialExtension(duration float32, ) *TrialExtension`

NewTrialExtension instantiates a new TrialExtension object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrialExtensionWithDefaults

`func NewTrialExtensionWithDefaults() *TrialExtension`

NewTrialExtensionWithDefaults instantiates a new TrialExtension object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDuration

`func (o *TrialExtension) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TrialExtension) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TrialExtension) SetDuration(v float32)`

SetDuration sets Duration field to given value.


### GetReason

`func (o *TrialExtension) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *TrialExtension) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *TrialExtension) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *TrialExtension) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetDenied

`func (o *TrialExtension) GetDenied() bool`

GetDenied returns the Denied field if non-nil, zero value otherwise.

### GetDeniedOk

`func (o *TrialExtension) GetDeniedOk() (*bool, bool)`

GetDeniedOk returns a tuple with the Denied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDenied

`func (o *TrialExtension) SetDenied(v bool)`

SetDenied sets Denied field to given value.

### HasDenied

`func (o *TrialExtension) HasDenied() bool`

HasDenied returns a boolean if a field has been set.

### GetDeniedReason

`func (o *TrialExtension) GetDeniedReason() string`

GetDeniedReason returns the DeniedReason field if non-nil, zero value otherwise.

### GetDeniedReasonOk

`func (o *TrialExtension) GetDeniedReasonOk() (*string, bool)`

GetDeniedReasonOk returns a tuple with the DeniedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeniedReason

`func (o *TrialExtension) SetDeniedReason(v string)`

SetDeniedReason sets DeniedReason field to given value.

### HasDeniedReason

`func (o *TrialExtension) HasDeniedReason() bool`

HasDeniedReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


