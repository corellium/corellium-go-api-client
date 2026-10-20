# DomainConfigTrial

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Start** | Pointer to **float32** | Trial start unix timestamp (ms). | [optional] 
**End** | Pointer to **float32** | Trial end unix timestamp (ms). | [optional] 
**EndAction** | Pointer to [**DomainConfigTrialEndAction**](DomainConfigTrialEndAction.md) |  | [optional] 
**SubscribeAction** | Pointer to [**DomainConfigTrialSubscribeAction**](DomainConfigTrialSubscribeAction.md) |  | [optional] 
**Extension** | Pointer to [**TrialExtension**](TrialExtension.md) | Requested trial extension. | [optional] 

## Methods

### NewDomainConfigTrial

`func NewDomainConfigTrial() *DomainConfigTrial`

NewDomainConfigTrial instantiates a new DomainConfigTrial object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainConfigTrialWithDefaults

`func NewDomainConfigTrialWithDefaults() *DomainConfigTrial`

NewDomainConfigTrialWithDefaults instantiates a new DomainConfigTrial object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStart

`func (o *DomainConfigTrial) GetStart() float32`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *DomainConfigTrial) GetStartOk() (*float32, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *DomainConfigTrial) SetStart(v float32)`

SetStart sets Start field to given value.

### HasStart

`func (o *DomainConfigTrial) HasStart() bool`

HasStart returns a boolean if a field has been set.

### GetEnd

`func (o *DomainConfigTrial) GetEnd() float32`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *DomainConfigTrial) GetEndOk() (*float32, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *DomainConfigTrial) SetEnd(v float32)`

SetEnd sets End field to given value.

### HasEnd

`func (o *DomainConfigTrial) HasEnd() bool`

HasEnd returns a boolean if a field has been set.

### GetEndAction

`func (o *DomainConfigTrial) GetEndAction() DomainConfigTrialEndAction`

GetEndAction returns the EndAction field if non-nil, zero value otherwise.

### GetEndActionOk

`func (o *DomainConfigTrial) GetEndActionOk() (*DomainConfigTrialEndAction, bool)`

GetEndActionOk returns a tuple with the EndAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndAction

`func (o *DomainConfigTrial) SetEndAction(v DomainConfigTrialEndAction)`

SetEndAction sets EndAction field to given value.

### HasEndAction

`func (o *DomainConfigTrial) HasEndAction() bool`

HasEndAction returns a boolean if a field has been set.

### GetSubscribeAction

`func (o *DomainConfigTrial) GetSubscribeAction() DomainConfigTrialSubscribeAction`

GetSubscribeAction returns the SubscribeAction field if non-nil, zero value otherwise.

### GetSubscribeActionOk

`func (o *DomainConfigTrial) GetSubscribeActionOk() (*DomainConfigTrialSubscribeAction, bool)`

GetSubscribeActionOk returns a tuple with the SubscribeAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscribeAction

`func (o *DomainConfigTrial) SetSubscribeAction(v DomainConfigTrialSubscribeAction)`

SetSubscribeAction sets SubscribeAction field to given value.

### HasSubscribeAction

`func (o *DomainConfigTrial) HasSubscribeAction() bool`

HasSubscribeAction returns a boolean if a field has been set.

### GetExtension

`func (o *DomainConfigTrial) GetExtension() TrialExtension`

GetExtension returns the Extension field if non-nil, zero value otherwise.

### GetExtensionOk

`func (o *DomainConfigTrial) GetExtensionOk() (*TrialExtension, bool)`

GetExtensionOk returns a tuple with the Extension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtension

`func (o *DomainConfigTrial) SetExtension(v TrialExtension)`

SetExtension sets Extension field to given value.

### HasExtension

`func (o *DomainConfigTrial) HasExtension() bool`

HasExtension returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


