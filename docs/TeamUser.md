# TeamUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | User identifier. | 
**Label** | **string** | User label. | 
**Name** | Pointer to **string** | Username. | [optional] 
**Email** | Pointer to **string** | User email. | [optional] 
**Administrator** | Pointer to **NullableBool** | Whether the user is a domain administrator. | [optional] 
**CanEditUserAttributes** | Pointer to **bool** | Whether the user can edit user attributes. | [optional] 
**ClusterAdministrator** | Pointer to **bool** | Whether the user is a cluster administrator. | [optional] 
**IsFederatedUser** | Pointer to **bool** | Whether the user authenticates via a federated provider. | [optional] 

## Methods

### NewTeamUser

`func NewTeamUser(id string, label string, ) *TeamUser`

NewTeamUser instantiates a new TeamUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTeamUserWithDefaults

`func NewTeamUserWithDefaults() *TeamUser`

NewTeamUserWithDefaults instantiates a new TeamUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TeamUser) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TeamUser) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TeamUser) SetId(v string)`

SetId sets Id field to given value.


### GetLabel

`func (o *TeamUser) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *TeamUser) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *TeamUser) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetName

`func (o *TeamUser) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TeamUser) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TeamUser) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *TeamUser) HasName() bool`

HasName returns a boolean if a field has been set.

### GetEmail

`func (o *TeamUser) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *TeamUser) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *TeamUser) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *TeamUser) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetAdministrator

`func (o *TeamUser) GetAdministrator() bool`

GetAdministrator returns the Administrator field if non-nil, zero value otherwise.

### GetAdministratorOk

`func (o *TeamUser) GetAdministratorOk() (*bool, bool)`

GetAdministratorOk returns a tuple with the Administrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministrator

`func (o *TeamUser) SetAdministrator(v bool)`

SetAdministrator sets Administrator field to given value.

### HasAdministrator

`func (o *TeamUser) HasAdministrator() bool`

HasAdministrator returns a boolean if a field has been set.

### SetAdministratorNil

`func (o *TeamUser) SetAdministratorNil(b bool)`

 SetAdministratorNil sets the value for Administrator to be an explicit nil

### UnsetAdministrator
`func (o *TeamUser) UnsetAdministrator()`

UnsetAdministrator ensures that no value is present for Administrator, not even an explicit nil
### GetCanEditUserAttributes

`func (o *TeamUser) GetCanEditUserAttributes() bool`

GetCanEditUserAttributes returns the CanEditUserAttributes field if non-nil, zero value otherwise.

### GetCanEditUserAttributesOk

`func (o *TeamUser) GetCanEditUserAttributesOk() (*bool, bool)`

GetCanEditUserAttributesOk returns a tuple with the CanEditUserAttributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanEditUserAttributes

`func (o *TeamUser) SetCanEditUserAttributes(v bool)`

SetCanEditUserAttributes sets CanEditUserAttributes field to given value.

### HasCanEditUserAttributes

`func (o *TeamUser) HasCanEditUserAttributes() bool`

HasCanEditUserAttributes returns a boolean if a field has been set.

### GetClusterAdministrator

`func (o *TeamUser) GetClusterAdministrator() bool`

GetClusterAdministrator returns the ClusterAdministrator field if non-nil, zero value otherwise.

### GetClusterAdministratorOk

`func (o *TeamUser) GetClusterAdministratorOk() (*bool, bool)`

GetClusterAdministratorOk returns a tuple with the ClusterAdministrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterAdministrator

`func (o *TeamUser) SetClusterAdministrator(v bool)`

SetClusterAdministrator sets ClusterAdministrator field to given value.

### HasClusterAdministrator

`func (o *TeamUser) HasClusterAdministrator() bool`

HasClusterAdministrator returns a boolean if a field has been set.

### GetIsFederatedUser

`func (o *TeamUser) GetIsFederatedUser() bool`

GetIsFederatedUser returns the IsFederatedUser field if non-nil, zero value otherwise.

### GetIsFederatedUserOk

`func (o *TeamUser) GetIsFederatedUserOk() (*bool, bool)`

GetIsFederatedUserOk returns a tuple with the IsFederatedUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFederatedUser

`func (o *TeamUser) SetIsFederatedUser(v bool)`

SetIsFederatedUser sets IsFederatedUser field to given value.

### HasIsFederatedUser

`func (o *TeamUser) HasIsFederatedUser() bool`

HasIsFederatedUser returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


