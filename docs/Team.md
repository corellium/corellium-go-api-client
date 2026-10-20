# Team

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Team identifier (or \&quot;all-users\&quot; for the implicit team). | 
**Label** | **NullableString** | Team label; null when the team has no name set. | 
**Users** | [**[]TeamUser**](TeamUser.md) | Members of the team. | 

## Methods

### NewTeam

`func NewTeam(id string, label NullableString, users []TeamUser, ) *Team`

NewTeam instantiates a new Team object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTeamWithDefaults

`func NewTeamWithDefaults() *Team`

NewTeamWithDefaults instantiates a new Team object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Team) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Team) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Team) SetId(v string)`

SetId sets Id field to given value.


### GetLabel

`func (o *Team) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *Team) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *Team) SetLabel(v string)`

SetLabel sets Label field to given value.


### SetLabelNil

`func (o *Team) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *Team) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetUsers

`func (o *Team) GetUsers() []TeamUser`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *Team) GetUsersOk() (*[]TeamUser, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *Team) SetUsers(v []TeamUser)`

SetUsers sets Users field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


