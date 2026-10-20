# AgentApp

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | Pointer to **[]string** | App tags (iOS only). | [optional] 
**Running** | Pointer to **bool** | Whether the app is currently running. | [optional] 
**DiskUsage** | Pointer to **float32** | Disk usage in bytes. | [optional] 
**Date** | Pointer to **float32** | Unix timestamp (seconds) of when the app was installed. | [optional] 
**ApplicationType** | **string** | Application type. | 
**Name** | Pointer to **string** | App display name (not present for all Android apps). | [optional] 
**BundleId** | **string** | App bundle identifier. | 
**BundlePath** | Pointer to **string** | Path to the app bundle (iOS only). | [optional] 
**BundleDataPath** | Pointer to **string** | Path to the app bundle data (iOS only). | [optional] 
**IsLaunchable** | Pointer to **bool** | Whether the app is launchable (Android only). | [optional] 
**Icon** | Pointer to **string** | Base64-encoded app icon when loadIcons is enabled. | [optional] 

## Methods

### NewAgentApp

`func NewAgentApp(applicationType string, bundleId string, ) *AgentApp`

NewAgentApp instantiates a new AgentApp object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentAppWithDefaults

`func NewAgentAppWithDefaults() *AgentApp`

NewAgentAppWithDefaults instantiates a new AgentApp object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *AgentApp) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *AgentApp) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *AgentApp) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *AgentApp) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetRunning

`func (o *AgentApp) GetRunning() bool`

GetRunning returns the Running field if non-nil, zero value otherwise.

### GetRunningOk

`func (o *AgentApp) GetRunningOk() (*bool, bool)`

GetRunningOk returns a tuple with the Running field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunning

`func (o *AgentApp) SetRunning(v bool)`

SetRunning sets Running field to given value.

### HasRunning

`func (o *AgentApp) HasRunning() bool`

HasRunning returns a boolean if a field has been set.

### GetDiskUsage

`func (o *AgentApp) GetDiskUsage() float32`

GetDiskUsage returns the DiskUsage field if non-nil, zero value otherwise.

### GetDiskUsageOk

`func (o *AgentApp) GetDiskUsageOk() (*float32, bool)`

GetDiskUsageOk returns a tuple with the DiskUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskUsage

`func (o *AgentApp) SetDiskUsage(v float32)`

SetDiskUsage sets DiskUsage field to given value.

### HasDiskUsage

`func (o *AgentApp) HasDiskUsage() bool`

HasDiskUsage returns a boolean if a field has been set.

### GetDate

`func (o *AgentApp) GetDate() float32`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *AgentApp) GetDateOk() (*float32, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *AgentApp) SetDate(v float32)`

SetDate sets Date field to given value.

### HasDate

`func (o *AgentApp) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetApplicationType

`func (o *AgentApp) GetApplicationType() string`

GetApplicationType returns the ApplicationType field if non-nil, zero value otherwise.

### GetApplicationTypeOk

`func (o *AgentApp) GetApplicationTypeOk() (*string, bool)`

GetApplicationTypeOk returns a tuple with the ApplicationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationType

`func (o *AgentApp) SetApplicationType(v string)`

SetApplicationType sets ApplicationType field to given value.


### GetName

`func (o *AgentApp) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AgentApp) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AgentApp) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AgentApp) HasName() bool`

HasName returns a boolean if a field has been set.

### GetBundleId

`func (o *AgentApp) GetBundleId() string`

GetBundleId returns the BundleId field if non-nil, zero value otherwise.

### GetBundleIdOk

`func (o *AgentApp) GetBundleIdOk() (*string, bool)`

GetBundleIdOk returns a tuple with the BundleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleId

`func (o *AgentApp) SetBundleId(v string)`

SetBundleId sets BundleId field to given value.


### GetBundlePath

`func (o *AgentApp) GetBundlePath() string`

GetBundlePath returns the BundlePath field if non-nil, zero value otherwise.

### GetBundlePathOk

`func (o *AgentApp) GetBundlePathOk() (*string, bool)`

GetBundlePathOk returns a tuple with the BundlePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundlePath

`func (o *AgentApp) SetBundlePath(v string)`

SetBundlePath sets BundlePath field to given value.

### HasBundlePath

`func (o *AgentApp) HasBundlePath() bool`

HasBundlePath returns a boolean if a field has been set.

### GetBundleDataPath

`func (o *AgentApp) GetBundleDataPath() string`

GetBundleDataPath returns the BundleDataPath field if non-nil, zero value otherwise.

### GetBundleDataPathOk

`func (o *AgentApp) GetBundleDataPathOk() (*string, bool)`

GetBundleDataPathOk returns a tuple with the BundleDataPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleDataPath

`func (o *AgentApp) SetBundleDataPath(v string)`

SetBundleDataPath sets BundleDataPath field to given value.

### HasBundleDataPath

`func (o *AgentApp) HasBundleDataPath() bool`

HasBundleDataPath returns a boolean if a field has been set.

### GetIsLaunchable

`func (o *AgentApp) GetIsLaunchable() bool`

GetIsLaunchable returns the IsLaunchable field if non-nil, zero value otherwise.

### GetIsLaunchableOk

`func (o *AgentApp) GetIsLaunchableOk() (*bool, bool)`

GetIsLaunchableOk returns a tuple with the IsLaunchable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsLaunchable

`func (o *AgentApp) SetIsLaunchable(v bool)`

SetIsLaunchable sets IsLaunchable field to given value.

### HasIsLaunchable

`func (o *AgentApp) HasIsLaunchable() bool`

HasIsLaunchable returns a boolean if a field has been set.

### GetIcon

`func (o *AgentApp) GetIcon() string`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *AgentApp) GetIconOk() (*string, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *AgentApp) SetIcon(v string)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *AgentApp) HasIcon() bool`

HasIcon returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


