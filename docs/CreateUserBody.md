# CreateUserBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | Pointer to **string** | Password (optional when using SSO). | [optional] 
**Administrator** | Pointer to **bool** | Whether the user is a domain administrator (domain admins only). | [optional] 
**Name** | **string** | Username. | 
**Label** | **string** | User label (e.g. \&quot;Domain Administrator\&quot;). | 
**Email** | Pointer to **string** | User email. | [optional] 
**ClusterAdministrator** | Pointer to **bool** | Whether the user is a cluster administrator (cluster admins only). | [optional] 

## Methods

### NewCreateUserBody

`func NewCreateUserBody(name string, label string, ) *CreateUserBody`

NewCreateUserBody instantiates a new CreateUserBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateUserBodyWithDefaults

`func NewCreateUserBodyWithDefaults() *CreateUserBody`

NewCreateUserBodyWithDefaults instantiates a new CreateUserBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *CreateUserBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *CreateUserBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *CreateUserBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *CreateUserBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetAdministrator

`func (o *CreateUserBody) GetAdministrator() bool`

GetAdministrator returns the Administrator field if non-nil, zero value otherwise.

### GetAdministratorOk

`func (o *CreateUserBody) GetAdministratorOk() (*bool, bool)`

GetAdministratorOk returns a tuple with the Administrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministrator

`func (o *CreateUserBody) SetAdministrator(v bool)`

SetAdministrator sets Administrator field to given value.

### HasAdministrator

`func (o *CreateUserBody) HasAdministrator() bool`

HasAdministrator returns a boolean if a field has been set.

### GetName

`func (o *CreateUserBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateUserBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateUserBody) SetName(v string)`

SetName sets Name field to given value.


### GetLabel

`func (o *CreateUserBody) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateUserBody) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateUserBody) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetEmail

`func (o *CreateUserBody) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateUserBody) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateUserBody) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CreateUserBody) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetClusterAdministrator

`func (o *CreateUserBody) GetClusterAdministrator() bool`

GetClusterAdministrator returns the ClusterAdministrator field if non-nil, zero value otherwise.

### GetClusterAdministratorOk

`func (o *CreateUserBody) GetClusterAdministratorOk() (*bool, bool)`

GetClusterAdministratorOk returns a tuple with the ClusterAdministrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterAdministrator

`func (o *CreateUserBody) SetClusterAdministrator(v bool)`

SetClusterAdministrator sets ClusterAdministrator field to given value.

### HasClusterAdministrator

`func (o *CreateUserBody) HasClusterAdministrator() bool`

HasClusterAdministrator returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


