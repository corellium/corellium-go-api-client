# RoleV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | **string** |  | 
**Project** | Pointer to **NullableString** | Project ID. Omitted for domain/global roles | [optional] 
**User** | Pointer to **NullableString** | User ID. Omitted for team roles | [optional] 
**Team** | Pointer to **NullableString** | Team ID. Present on team roles instead of user | [optional] 

## Methods

### NewRoleV1

`func NewRoleV1(role string, ) *RoleV1`

NewRoleV1 instantiates a new RoleV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleV1WithDefaults

`func NewRoleV1WithDefaults() *RoleV1`

NewRoleV1WithDefaults instantiates a new RoleV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *RoleV1) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *RoleV1) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *RoleV1) SetRole(v string)`

SetRole sets Role field to given value.


### GetProject

`func (o *RoleV1) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *RoleV1) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *RoleV1) SetProject(v string)`

SetProject sets Project field to given value.

### HasProject

`func (o *RoleV1) HasProject() bool`

HasProject returns a boolean if a field has been set.

### SetProjectNil

`func (o *RoleV1) SetProjectNil(b bool)`

 SetProjectNil sets the value for Project to be an explicit nil

### UnsetProject
`func (o *RoleV1) UnsetProject()`

UnsetProject ensures that no value is present for Project, not even an explicit nil
### GetUser

`func (o *RoleV1) GetUser() string`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *RoleV1) GetUserOk() (*string, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *RoleV1) SetUser(v string)`

SetUser sets User field to given value.

### HasUser

`func (o *RoleV1) HasUser() bool`

HasUser returns a boolean if a field has been set.

### SetUserNil

`func (o *RoleV1) SetUserNil(b bool)`

 SetUserNil sets the value for User to be an explicit nil

### UnsetUser
`func (o *RoleV1) UnsetUser()`

UnsetUser ensures that no value is present for User, not even an explicit nil
### GetTeam

`func (o *RoleV1) GetTeam() string`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *RoleV1) GetTeamOk() (*string, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *RoleV1) SetTeam(v string)`

SetTeam sets Team field to given value.

### HasTeam

`func (o *RoleV1) HasTeam() bool`

HasTeam returns a boolean if a field has been set.

### SetTeamNil

`func (o *RoleV1) SetTeamNil(b bool)`

 SetTeamNil sets the value for Team to be an explicit nil

### UnsetTeam
`func (o *RoleV1) UnsetTeam()`

UnsetTeam ensures that no value is present for Team, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


