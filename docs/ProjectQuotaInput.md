# ProjectQuotaInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cores** | **float32** | Allocated CPU cores. | 
**Instances** | Pointer to **float32** | Allocated instance count. Derived from cores when omitted. | [optional] 
**Ram** | Pointer to **float32** | Ignored on write: RAM in mebibytes is always recomputed as cores * 6144. | [optional] 

## Methods

### NewProjectQuotaInput

`func NewProjectQuotaInput(cores float32, ) *ProjectQuotaInput`

NewProjectQuotaInput instantiates a new ProjectQuotaInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectQuotaInputWithDefaults

`func NewProjectQuotaInputWithDefaults() *ProjectQuotaInput`

NewProjectQuotaInputWithDefaults instantiates a new ProjectQuotaInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCores

`func (o *ProjectQuotaInput) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *ProjectQuotaInput) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *ProjectQuotaInput) SetCores(v float32)`

SetCores sets Cores field to given value.


### GetInstances

`func (o *ProjectQuotaInput) GetInstances() float32`

GetInstances returns the Instances field if non-nil, zero value otherwise.

### GetInstancesOk

`func (o *ProjectQuotaInput) GetInstancesOk() (*float32, bool)`

GetInstancesOk returns a tuple with the Instances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstances

`func (o *ProjectQuotaInput) SetInstances(v float32)`

SetInstances sets Instances field to given value.

### HasInstances

`func (o *ProjectQuotaInput) HasInstances() bool`

HasInstances returns a boolean if a field has been set.

### GetRam

`func (o *ProjectQuotaInput) GetRam() float32`

GetRam returns the Ram field if non-nil, zero value otherwise.

### GetRamOk

`func (o *ProjectQuotaInput) GetRamOk() (*float32, bool)`

GetRamOk returns a tuple with the Ram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRam

`func (o *ProjectQuotaInput) SetRam(v float32)`

SetRam sets Ram field to given value.

### HasRam

`func (o *ProjectQuotaInput) HasRam() bool`

HasRam returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


