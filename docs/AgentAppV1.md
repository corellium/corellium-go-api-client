# AgentAppV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | Pointer to **[]string** |  | [optional] 
**Running** | Pointer to **NullableBool** |  | [optional] 
**DiskUsage** | Pointer to **NullableFloat32** |  | [optional] 
**Date** | Pointer to **NullableFloat32** |  | [optional] 
**ApplicationType** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**BundleID** | Pointer to **NullableString** |  | [optional] 
**BundlePath** | Pointer to **NullableString** |  | [optional] 
**BundleDataPath** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAgentAppV1

`func NewAgentAppV1() *AgentAppV1`

NewAgentAppV1 instantiates a new AgentAppV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentAppV1WithDefaults

`func NewAgentAppV1WithDefaults() *AgentAppV1`

NewAgentAppV1WithDefaults instantiates a new AgentAppV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *AgentAppV1) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *AgentAppV1) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *AgentAppV1) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *AgentAppV1) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *AgentAppV1) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *AgentAppV1) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetRunning

`func (o *AgentAppV1) GetRunning() bool`

GetRunning returns the Running field if non-nil, zero value otherwise.

### GetRunningOk

`func (o *AgentAppV1) GetRunningOk() (*bool, bool)`

GetRunningOk returns a tuple with the Running field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunning

`func (o *AgentAppV1) SetRunning(v bool)`

SetRunning sets Running field to given value.

### HasRunning

`func (o *AgentAppV1) HasRunning() bool`

HasRunning returns a boolean if a field has been set.

### SetRunningNil

`func (o *AgentAppV1) SetRunningNil(b bool)`

 SetRunningNil sets the value for Running to be an explicit nil

### UnsetRunning
`func (o *AgentAppV1) UnsetRunning()`

UnsetRunning ensures that no value is present for Running, not even an explicit nil
### GetDiskUsage

`func (o *AgentAppV1) GetDiskUsage() float32`

GetDiskUsage returns the DiskUsage field if non-nil, zero value otherwise.

### GetDiskUsageOk

`func (o *AgentAppV1) GetDiskUsageOk() (*float32, bool)`

GetDiskUsageOk returns a tuple with the DiskUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskUsage

`func (o *AgentAppV1) SetDiskUsage(v float32)`

SetDiskUsage sets DiskUsage field to given value.

### HasDiskUsage

`func (o *AgentAppV1) HasDiskUsage() bool`

HasDiskUsage returns a boolean if a field has been set.

### SetDiskUsageNil

`func (o *AgentAppV1) SetDiskUsageNil(b bool)`

 SetDiskUsageNil sets the value for DiskUsage to be an explicit nil

### UnsetDiskUsage
`func (o *AgentAppV1) UnsetDiskUsage()`

UnsetDiskUsage ensures that no value is present for DiskUsage, not even an explicit nil
### GetDate

`func (o *AgentAppV1) GetDate() float32`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *AgentAppV1) GetDateOk() (*float32, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *AgentAppV1) SetDate(v float32)`

SetDate sets Date field to given value.

### HasDate

`func (o *AgentAppV1) HasDate() bool`

HasDate returns a boolean if a field has been set.

### SetDateNil

`func (o *AgentAppV1) SetDateNil(b bool)`

 SetDateNil sets the value for Date to be an explicit nil

### UnsetDate
`func (o *AgentAppV1) UnsetDate()`

UnsetDate ensures that no value is present for Date, not even an explicit nil
### GetApplicationType

`func (o *AgentAppV1) GetApplicationType() string`

GetApplicationType returns the ApplicationType field if non-nil, zero value otherwise.

### GetApplicationTypeOk

`func (o *AgentAppV1) GetApplicationTypeOk() (*string, bool)`

GetApplicationTypeOk returns a tuple with the ApplicationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationType

`func (o *AgentAppV1) SetApplicationType(v string)`

SetApplicationType sets ApplicationType field to given value.

### HasApplicationType

`func (o *AgentAppV1) HasApplicationType() bool`

HasApplicationType returns a boolean if a field has been set.

### SetApplicationTypeNil

`func (o *AgentAppV1) SetApplicationTypeNil(b bool)`

 SetApplicationTypeNil sets the value for ApplicationType to be an explicit nil

### UnsetApplicationType
`func (o *AgentAppV1) UnsetApplicationType()`

UnsetApplicationType ensures that no value is present for ApplicationType, not even an explicit nil
### GetName

`func (o *AgentAppV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AgentAppV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AgentAppV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AgentAppV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AgentAppV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AgentAppV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetBundleID

`func (o *AgentAppV1) GetBundleID() string`

GetBundleID returns the BundleID field if non-nil, zero value otherwise.

### GetBundleIDOk

`func (o *AgentAppV1) GetBundleIDOk() (*string, bool)`

GetBundleIDOk returns a tuple with the BundleID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleID

`func (o *AgentAppV1) SetBundleID(v string)`

SetBundleID sets BundleID field to given value.

### HasBundleID

`func (o *AgentAppV1) HasBundleID() bool`

HasBundleID returns a boolean if a field has been set.

### SetBundleIDNil

`func (o *AgentAppV1) SetBundleIDNil(b bool)`

 SetBundleIDNil sets the value for BundleID to be an explicit nil

### UnsetBundleID
`func (o *AgentAppV1) UnsetBundleID()`

UnsetBundleID ensures that no value is present for BundleID, not even an explicit nil
### GetBundlePath

`func (o *AgentAppV1) GetBundlePath() string`

GetBundlePath returns the BundlePath field if non-nil, zero value otherwise.

### GetBundlePathOk

`func (o *AgentAppV1) GetBundlePathOk() (*string, bool)`

GetBundlePathOk returns a tuple with the BundlePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundlePath

`func (o *AgentAppV1) SetBundlePath(v string)`

SetBundlePath sets BundlePath field to given value.

### HasBundlePath

`func (o *AgentAppV1) HasBundlePath() bool`

HasBundlePath returns a boolean if a field has been set.

### SetBundlePathNil

`func (o *AgentAppV1) SetBundlePathNil(b bool)`

 SetBundlePathNil sets the value for BundlePath to be an explicit nil

### UnsetBundlePath
`func (o *AgentAppV1) UnsetBundlePath()`

UnsetBundlePath ensures that no value is present for BundlePath, not even an explicit nil
### GetBundleDataPath

`func (o *AgentAppV1) GetBundleDataPath() string`

GetBundleDataPath returns the BundleDataPath field if non-nil, zero value otherwise.

### GetBundleDataPathOk

`func (o *AgentAppV1) GetBundleDataPathOk() (*string, bool)`

GetBundleDataPathOk returns a tuple with the BundleDataPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleDataPath

`func (o *AgentAppV1) SetBundleDataPath(v string)`

SetBundleDataPath sets BundleDataPath field to given value.

### HasBundleDataPath

`func (o *AgentAppV1) HasBundleDataPath() bool`

HasBundleDataPath returns a boolean if a field has been set.

### SetBundleDataPathNil

`func (o *AgentAppV1) SetBundleDataPathNil(b bool)`

 SetBundleDataPathNil sets the value for BundleDataPath to be an explicit nil

### UnsetBundleDataPath
`func (o *AgentAppV1) UnsetBundleDataPath()`

UnsetBundleDataPath ensures that no value is present for BundleDataPath, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


