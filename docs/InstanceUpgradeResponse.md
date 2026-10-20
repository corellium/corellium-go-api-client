# InstanceUpgradeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Instance ID. | 
**State** | **string** | Instance state. Always \&quot;updating\&quot; once an upgrade has been accepted. | 

## Methods

### NewInstanceUpgradeResponse

`func NewInstanceUpgradeResponse(id string, state string, ) *InstanceUpgradeResponse`

NewInstanceUpgradeResponse instantiates a new InstanceUpgradeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceUpgradeResponseWithDefaults

`func NewInstanceUpgradeResponseWithDefaults() *InstanceUpgradeResponse`

NewInstanceUpgradeResponseWithDefaults instantiates a new InstanceUpgradeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InstanceUpgradeResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InstanceUpgradeResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InstanceUpgradeResponse) SetId(v string)`

SetId sets Id field to given value.


### GetState

`func (o *InstanceUpgradeResponse) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *InstanceUpgradeResponse) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *InstanceUpgradeResponse) SetState(v string)`

SetState sets State field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


