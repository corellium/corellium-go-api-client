# DeploymentVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductVersion** | **string** | Deployed Corellium product version. | 
**CoordinatorVersion** | **NullableString** | Coordinator artifact version. | 
**BuildCommit** | **NullableString** | Full coordinator source commit SHA. | 
**BuildDate** | **NullableTime** | Coordinator artifact build time in RFC 3339 UTC format. | 

## Methods

### NewDeploymentVersion

`func NewDeploymentVersion(productVersion string, coordinatorVersion NullableString, buildCommit NullableString, buildDate NullableTime, ) *DeploymentVersion`

NewDeploymentVersion instantiates a new DeploymentVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeploymentVersionWithDefaults

`func NewDeploymentVersionWithDefaults() *DeploymentVersion`

NewDeploymentVersionWithDefaults instantiates a new DeploymentVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductVersion

`func (o *DeploymentVersion) GetProductVersion() string`

GetProductVersion returns the ProductVersion field if non-nil, zero value otherwise.

### GetProductVersionOk

`func (o *DeploymentVersion) GetProductVersionOk() (*string, bool)`

GetProductVersionOk returns a tuple with the ProductVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductVersion

`func (o *DeploymentVersion) SetProductVersion(v string)`

SetProductVersion sets ProductVersion field to given value.


### GetCoordinatorVersion

`func (o *DeploymentVersion) GetCoordinatorVersion() string`

GetCoordinatorVersion returns the CoordinatorVersion field if non-nil, zero value otherwise.

### GetCoordinatorVersionOk

`func (o *DeploymentVersion) GetCoordinatorVersionOk() (*string, bool)`

GetCoordinatorVersionOk returns a tuple with the CoordinatorVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinatorVersion

`func (o *DeploymentVersion) SetCoordinatorVersion(v string)`

SetCoordinatorVersion sets CoordinatorVersion field to given value.


### SetCoordinatorVersionNil

`func (o *DeploymentVersion) SetCoordinatorVersionNil(b bool)`

 SetCoordinatorVersionNil sets the value for CoordinatorVersion to be an explicit nil

### UnsetCoordinatorVersion
`func (o *DeploymentVersion) UnsetCoordinatorVersion()`

UnsetCoordinatorVersion ensures that no value is present for CoordinatorVersion, not even an explicit nil
### GetBuildCommit

`func (o *DeploymentVersion) GetBuildCommit() string`

GetBuildCommit returns the BuildCommit field if non-nil, zero value otherwise.

### GetBuildCommitOk

`func (o *DeploymentVersion) GetBuildCommitOk() (*string, bool)`

GetBuildCommitOk returns a tuple with the BuildCommit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildCommit

`func (o *DeploymentVersion) SetBuildCommit(v string)`

SetBuildCommit sets BuildCommit field to given value.


### SetBuildCommitNil

`func (o *DeploymentVersion) SetBuildCommitNil(b bool)`

 SetBuildCommitNil sets the value for BuildCommit to be an explicit nil

### UnsetBuildCommit
`func (o *DeploymentVersion) UnsetBuildCommit()`

UnsetBuildCommit ensures that no value is present for BuildCommit, not even an explicit nil
### GetBuildDate

`func (o *DeploymentVersion) GetBuildDate() time.Time`

GetBuildDate returns the BuildDate field if non-nil, zero value otherwise.

### GetBuildDateOk

`func (o *DeploymentVersion) GetBuildDateOk() (*time.Time, bool)`

GetBuildDateOk returns a tuple with the BuildDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildDate

`func (o *DeploymentVersion) SetBuildDate(v time.Time)`

SetBuildDate sets BuildDate field to given value.


### SetBuildDateNil

`func (o *DeploymentVersion) SetBuildDateNil(b bool)`

 SetBuildDateNil sets the value for BuildDate to be an explicit nil

### UnsetBuildDate
`func (o *DeploymentVersion) UnsetBuildDate()`

UnsetBuildDate ensures that no value is present for BuildDate, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


