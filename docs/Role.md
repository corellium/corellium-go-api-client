# Role

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | [**RoleName**](RoleName.md) |  | 
**Project** | Pointer to **string** | Project identifier (when scoped to a project). | [optional] 
**Deployment** | Pointer to **string** | Deployment identifier (when scoped to a deployment). | [optional] 
**User** | Pointer to **string** | User identifier (when granted to a user). | [optional] 
**Team** | Pointer to **string** | Team identifier (when granted to a team). | [optional] 

## Methods

### NewRole

`func NewRole(role RoleName, ) *Role`

NewRole instantiates a new Role object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleWithDefaults

`func NewRoleWithDefaults() *Role`

NewRoleWithDefaults instantiates a new Role object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *Role) GetRole() RoleName`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *Role) GetRoleOk() (*RoleName, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *Role) SetRole(v RoleName)`

SetRole sets Role field to given value.


### GetProject

`func (o *Role) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *Role) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *Role) SetProject(v string)`

SetProject sets Project field to given value.

### HasProject

`func (o *Role) HasProject() bool`

HasProject returns a boolean if a field has been set.

### GetDeployment

`func (o *Role) GetDeployment() string`

GetDeployment returns the Deployment field if non-nil, zero value otherwise.

### GetDeploymentOk

`func (o *Role) GetDeploymentOk() (*string, bool)`

GetDeploymentOk returns a tuple with the Deployment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployment

`func (o *Role) SetDeployment(v string)`

SetDeployment sets Deployment field to given value.

### HasDeployment

`func (o *Role) HasDeployment() bool`

HasDeployment returns a boolean if a field has been set.

### GetUser

`func (o *Role) GetUser() string`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *Role) GetUserOk() (*string, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *Role) SetUser(v string)`

SetUser sets User field to given value.

### HasUser

`func (o *Role) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetTeam

`func (o *Role) GetTeam() string`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *Role) GetTeamOk() (*string, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *Role) SetTeam(v string)`

SetTeam sets Team field to given value.

### HasTeam

`func (o *Role) HasTeam() bool`

HasTeam returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


