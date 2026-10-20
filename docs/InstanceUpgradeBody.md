# InstanceUpgradeBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OsVersion** | **string** | iOS version to upgrade to, as listed by &#x60;GET /v3/models/{model}/software&#x60; for this device&#39;s model. | 
**OsBuild** | Pointer to **string** | Optional exact build of that version. Without it, the newest build of &#x60;osVersion&#x60; is used. | [optional] 

## Methods

### NewInstanceUpgradeBody

`func NewInstanceUpgradeBody(osVersion string, ) *InstanceUpgradeBody`

NewInstanceUpgradeBody instantiates a new InstanceUpgradeBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceUpgradeBodyWithDefaults

`func NewInstanceUpgradeBodyWithDefaults() *InstanceUpgradeBody`

NewInstanceUpgradeBodyWithDefaults instantiates a new InstanceUpgradeBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOsVersion

`func (o *InstanceUpgradeBody) GetOsVersion() string`

GetOsVersion returns the OsVersion field if non-nil, zero value otherwise.

### GetOsVersionOk

`func (o *InstanceUpgradeBody) GetOsVersionOk() (*string, bool)`

GetOsVersionOk returns a tuple with the OsVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsVersion

`func (o *InstanceUpgradeBody) SetOsVersion(v string)`

SetOsVersion sets OsVersion field to given value.


### GetOsBuild

`func (o *InstanceUpgradeBody) GetOsBuild() string`

GetOsBuild returns the OsBuild field if non-nil, zero value otherwise.

### GetOsBuildOk

`func (o *InstanceUpgradeBody) GetOsBuildOk() (*string, bool)`

GetOsBuildOk returns a tuple with the OsBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsBuild

`func (o *InstanceUpgradeBody) SetOsBuild(v string)`

SetOsBuild sets OsBuild field to given value.

### HasOsBuild

`func (o *InstanceUpgradeBody) HasOsBuild() bool`

HasOsBuild returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


