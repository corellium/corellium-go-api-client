# AvailableTrialPlan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | **string** | Stripe product identifier. | 
**Name** | **string** | Trial plan name. | 
**License** | **string** | License type. | 
**Workspace** | **bool** | Whether the trial includes a workspace. | 
**Cores** | **float32** | Number of cores included. | 
**Devices** | **float32** | Number of devices included. | 
**TrialDuration** | **float32** | Trial duration in days. | 

## Methods

### NewAvailableTrialPlan

`func NewAvailableTrialPlan(productId string, name string, license string, workspace bool, cores float32, devices float32, trialDuration float32, ) *AvailableTrialPlan`

NewAvailableTrialPlan instantiates a new AvailableTrialPlan object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAvailableTrialPlanWithDefaults

`func NewAvailableTrialPlanWithDefaults() *AvailableTrialPlan`

NewAvailableTrialPlanWithDefaults instantiates a new AvailableTrialPlan object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *AvailableTrialPlan) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *AvailableTrialPlan) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *AvailableTrialPlan) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetName

`func (o *AvailableTrialPlan) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AvailableTrialPlan) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AvailableTrialPlan) SetName(v string)`

SetName sets Name field to given value.


### GetLicense

`func (o *AvailableTrialPlan) GetLicense() string`

GetLicense returns the License field if non-nil, zero value otherwise.

### GetLicenseOk

`func (o *AvailableTrialPlan) GetLicenseOk() (*string, bool)`

GetLicenseOk returns a tuple with the License field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicense

`func (o *AvailableTrialPlan) SetLicense(v string)`

SetLicense sets License field to given value.


### GetWorkspace

`func (o *AvailableTrialPlan) GetWorkspace() bool`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *AvailableTrialPlan) GetWorkspaceOk() (*bool, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *AvailableTrialPlan) SetWorkspace(v bool)`

SetWorkspace sets Workspace field to given value.


### GetCores

`func (o *AvailableTrialPlan) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *AvailableTrialPlan) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *AvailableTrialPlan) SetCores(v float32)`

SetCores sets Cores field to given value.


### GetDevices

`func (o *AvailableTrialPlan) GetDevices() float32`

GetDevices returns the Devices field if non-nil, zero value otherwise.

### GetDevicesOk

`func (o *AvailableTrialPlan) GetDevicesOk() (*float32, bool)`

GetDevicesOk returns a tuple with the Devices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevices

`func (o *AvailableTrialPlan) SetDevices(v float32)`

SetDevices sets Devices field to given value.


### GetTrialDuration

`func (o *AvailableTrialPlan) GetTrialDuration() float32`

GetTrialDuration returns the TrialDuration field if non-nil, zero value otherwise.

### GetTrialDurationOk

`func (o *AvailableTrialPlan) GetTrialDurationOk() (*float32, bool)`

GetTrialDurationOk returns a tuple with the TrialDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialDuration

`func (o *AvailableTrialPlan) SetTrialDuration(v float32)`

SetTrialDuration sets TrialDuration field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


