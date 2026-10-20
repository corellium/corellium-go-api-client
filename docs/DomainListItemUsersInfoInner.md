# DomainListItemUsersInfoInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | User identifier. | 
**Label** | **string** | User label. | 
**Name** | **string** | Username. | 
**Email** | **string** | User email. | 
**Administrator** | **bool** | Whether the user is a domain administrator. | 
**ClusterAdministrator** | **bool** | Whether the user is a cluster administrator. | 
**LastLogin** | **NullableTime** | ISO timestamp of last login. | 
**Teams** | **float32** | Number of teams the user belongs to. | 

## Methods

### NewDomainListItemUsersInfoInner

`func NewDomainListItemUsersInfoInner(id string, label string, name string, email string, administrator bool, clusterAdministrator bool, lastLogin NullableTime, teams float32, ) *DomainListItemUsersInfoInner`

NewDomainListItemUsersInfoInner instantiates a new DomainListItemUsersInfoInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListItemUsersInfoInnerWithDefaults

`func NewDomainListItemUsersInfoInnerWithDefaults() *DomainListItemUsersInfoInner`

NewDomainListItemUsersInfoInnerWithDefaults instantiates a new DomainListItemUsersInfoInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DomainListItemUsersInfoInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DomainListItemUsersInfoInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DomainListItemUsersInfoInner) SetId(v string)`

SetId sets Id field to given value.


### GetLabel

`func (o *DomainListItemUsersInfoInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *DomainListItemUsersInfoInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *DomainListItemUsersInfoInner) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetName

`func (o *DomainListItemUsersInfoInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DomainListItemUsersInfoInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DomainListItemUsersInfoInner) SetName(v string)`

SetName sets Name field to given value.


### GetEmail

`func (o *DomainListItemUsersInfoInner) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *DomainListItemUsersInfoInner) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *DomainListItemUsersInfoInner) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetAdministrator

`func (o *DomainListItemUsersInfoInner) GetAdministrator() bool`

GetAdministrator returns the Administrator field if non-nil, zero value otherwise.

### GetAdministratorOk

`func (o *DomainListItemUsersInfoInner) GetAdministratorOk() (*bool, bool)`

GetAdministratorOk returns a tuple with the Administrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministrator

`func (o *DomainListItemUsersInfoInner) SetAdministrator(v bool)`

SetAdministrator sets Administrator field to given value.


### GetClusterAdministrator

`func (o *DomainListItemUsersInfoInner) GetClusterAdministrator() bool`

GetClusterAdministrator returns the ClusterAdministrator field if non-nil, zero value otherwise.

### GetClusterAdministratorOk

`func (o *DomainListItemUsersInfoInner) GetClusterAdministratorOk() (*bool, bool)`

GetClusterAdministratorOk returns a tuple with the ClusterAdministrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterAdministrator

`func (o *DomainListItemUsersInfoInner) SetClusterAdministrator(v bool)`

SetClusterAdministrator sets ClusterAdministrator field to given value.


### GetLastLogin

`func (o *DomainListItemUsersInfoInner) GetLastLogin() time.Time`

GetLastLogin returns the LastLogin field if non-nil, zero value otherwise.

### GetLastLoginOk

`func (o *DomainListItemUsersInfoInner) GetLastLoginOk() (*time.Time, bool)`

GetLastLoginOk returns a tuple with the LastLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLogin

`func (o *DomainListItemUsersInfoInner) SetLastLogin(v time.Time)`

SetLastLogin sets LastLogin field to given value.


### SetLastLoginNil

`func (o *DomainListItemUsersInfoInner) SetLastLoginNil(b bool)`

 SetLastLoginNil sets the value for LastLogin to be an explicit nil

### UnsetLastLogin
`func (o *DomainListItemUsersInfoInner) UnsetLastLogin()`

UnsetLastLogin ensures that no value is present for LastLogin, not even an explicit nil
### GetTeams

`func (o *DomainListItemUsersInfoInner) GetTeams() float32`

GetTeams returns the Teams field if non-nil, zero value otherwise.

### GetTeamsOk

`func (o *DomainListItemUsersInfoInner) GetTeamsOk() (*float32, bool)`

GetTeamsOk returns a tuple with the Teams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeams

`func (o *DomainListItemUsersInfoInner) SetTeams(v float32)`

SetTeams sets Teams field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


