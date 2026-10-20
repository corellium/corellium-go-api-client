# InviteSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Teams** | Pointer to **[]string** | Teams the new user is added to when they sign up, by team ID (from &#x60;GET /v3/teams&#x60;). IDs of teams not in your domain are dropped. | [optional] 
**Projects** | Pointer to **[][]string** | Projects the new user gets access to when they sign up, as &#x60;[projectId, role]&#x60; pairs. IDs of projects not in your domain are dropped. | [optional] 

## Methods

### NewInviteSettings

`func NewInviteSettings() *InviteSettings`

NewInviteSettings instantiates a new InviteSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteSettingsWithDefaults

`func NewInviteSettingsWithDefaults() *InviteSettings`

NewInviteSettingsWithDefaults instantiates a new InviteSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTeams

`func (o *InviteSettings) GetTeams() []string`

GetTeams returns the Teams field if non-nil, zero value otherwise.

### GetTeamsOk

`func (o *InviteSettings) GetTeamsOk() (*[]string, bool)`

GetTeamsOk returns a tuple with the Teams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeams

`func (o *InviteSettings) SetTeams(v []string)`

SetTeams sets Teams field to given value.

### HasTeams

`func (o *InviteSettings) HasTeams() bool`

HasTeams returns a boolean if a field has been set.

### GetProjects

`func (o *InviteSettings) GetProjects() [][]string`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *InviteSettings) GetProjectsOk() (*[][]string, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *InviteSettings) SetProjects(v [][]string)`

SetProjects sets Projects field to given value.

### HasProjects

`func (o *InviteSettings) HasProjects() bool`

HasProjects returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


