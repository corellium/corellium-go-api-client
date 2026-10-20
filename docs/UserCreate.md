# UserCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** | The user name. | [optional] 
**Label** | Pointer to **NullableString** | The user label (e.g., \&quot;Domain Administrator\&quot;). | [optional] 
**Password** | Pointer to **NullableString** | The password (optional) if using SSO. | [optional] 
**Email** | Pointer to **NullableString** | The email (optional) if onsite. | [optional] 
**Administrator** | Pointer to **NullableBool** | Whether the user is a domain administrator. Only users with the Domain Administrator role can set this. | [optional] 
**ClusterAdministrator** | Pointer to **NullableBool** | Whether the user is a cluster administrator. Only users with the Cluster Administrator role can set this. | [optional] 

## Methods

### NewUserCreate

`func NewUserCreate() *UserCreate`

NewUserCreate instantiates a new UserCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserCreateWithDefaults

`func NewUserCreateWithDefaults() *UserCreate`

NewUserCreateWithDefaults instantiates a new UserCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UserCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserCreate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UserCreate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *UserCreate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *UserCreate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetLabel

`func (o *UserCreate) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *UserCreate) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *UserCreate) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *UserCreate) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *UserCreate) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *UserCreate) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetPassword

`func (o *UserCreate) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *UserCreate) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *UserCreate) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *UserCreate) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### SetPasswordNil

`func (o *UserCreate) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *UserCreate) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil
### GetEmail

`func (o *UserCreate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserCreate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserCreate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *UserCreate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *UserCreate) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *UserCreate) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetAdministrator

`func (o *UserCreate) GetAdministrator() bool`

GetAdministrator returns the Administrator field if non-nil, zero value otherwise.

### GetAdministratorOk

`func (o *UserCreate) GetAdministratorOk() (*bool, bool)`

GetAdministratorOk returns a tuple with the Administrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministrator

`func (o *UserCreate) SetAdministrator(v bool)`

SetAdministrator sets Administrator field to given value.

### HasAdministrator

`func (o *UserCreate) HasAdministrator() bool`

HasAdministrator returns a boolean if a field has been set.

### SetAdministratorNil

`func (o *UserCreate) SetAdministratorNil(b bool)`

 SetAdministratorNil sets the value for Administrator to be an explicit nil

### UnsetAdministrator
`func (o *UserCreate) UnsetAdministrator()`

UnsetAdministrator ensures that no value is present for Administrator, not even an explicit nil
### GetClusterAdministrator

`func (o *UserCreate) GetClusterAdministrator() bool`

GetClusterAdministrator returns the ClusterAdministrator field if non-nil, zero value otherwise.

### GetClusterAdministratorOk

`func (o *UserCreate) GetClusterAdministratorOk() (*bool, bool)`

GetClusterAdministratorOk returns a tuple with the ClusterAdministrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterAdministrator

`func (o *UserCreate) SetClusterAdministrator(v bool)`

SetClusterAdministrator sets ClusterAdministrator field to given value.

### HasClusterAdministrator

`func (o *UserCreate) HasClusterAdministrator() bool`

HasClusterAdministrator returns a boolean if a field has been set.

### SetClusterAdministratorNil

`func (o *UserCreate) SetClusterAdministratorNil(b bool)`

 SetClusterAdministratorNil sets the value for ClusterAdministrator to be an explicit nil

### UnsetClusterAdministrator
`func (o *UserCreate) UnsetClusterAdministrator()`

UnsetClusterAdministrator ensures that no value is present for ClusterAdministrator, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


