# SamlGroupMapping

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GroupName** | **string** | Group name in the IdP. | 
**Role** | **string** | Role granted in Corellium (e.g. admin, member). | 
**Team** | **string** | Associated Corellium team. | 

## Methods

### NewSamlGroupMapping

`func NewSamlGroupMapping(groupName string, role string, team string, ) *SamlGroupMapping`

NewSamlGroupMapping instantiates a new SamlGroupMapping object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSamlGroupMappingWithDefaults

`func NewSamlGroupMappingWithDefaults() *SamlGroupMapping`

NewSamlGroupMappingWithDefaults instantiates a new SamlGroupMapping object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroupName

`func (o *SamlGroupMapping) GetGroupName() string`

GetGroupName returns the GroupName field if non-nil, zero value otherwise.

### GetGroupNameOk

`func (o *SamlGroupMapping) GetGroupNameOk() (*string, bool)`

GetGroupNameOk returns a tuple with the GroupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupName

`func (o *SamlGroupMapping) SetGroupName(v string)`

SetGroupName sets GroupName field to given value.


### GetRole

`func (o *SamlGroupMapping) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *SamlGroupMapping) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *SamlGroupMapping) SetRole(v string)`

SetRole sets Role field to given value.


### GetTeam

`func (o *SamlGroupMapping) GetTeam() string`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *SamlGroupMapping) GetTeamOk() (*string, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *SamlGroupMapping) SetTeam(v string)`

SetTeam sets Team field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


