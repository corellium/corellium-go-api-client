# TeamV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Team ID | 
**Label** | **string** | Team Label | 
**Users** | Pointer to [**[]User**](User.md) | Users | [optional] 

## Methods

### NewTeamV1

`func NewTeamV1(id string, label string, ) *TeamV1`

NewTeamV1 instantiates a new TeamV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTeamV1WithDefaults

`func NewTeamV1WithDefaults() *TeamV1`

NewTeamV1WithDefaults instantiates a new TeamV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TeamV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TeamV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TeamV1) SetId(v string)`

SetId sets Id field to given value.


### GetLabel

`func (o *TeamV1) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *TeamV1) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *TeamV1) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetUsers

`func (o *TeamV1) GetUsers() []User`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *TeamV1) GetUsersOk() (*[]User, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *TeamV1) SetUsers(v []User)`

SetUsers sets Users field to given value.

### HasUsers

`func (o *TeamV1) HasUsers() bool`

HasUsers returns a boolean if a field has been set.

### SetUsersNil

`func (o *TeamV1) SetUsersNil(b bool)`

 SetUsersNil sets the value for Users to be an explicit nil

### UnsetUsers
`func (o *TeamV1) UnsetUsers()`

UnsetUsers ensures that no value is present for Users, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


