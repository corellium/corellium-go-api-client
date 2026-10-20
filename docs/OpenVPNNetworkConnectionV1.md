# OpenVPNNetworkConnectionV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | UUIDv4 | 
**Provider** | **string** | Type of network connection. | 
**Name** | **string** | User specified name for this network connection. e.g., \&quot;My Network Connection\&quot; | 
**Config** | Pointer to [**NullableOpenVPNConfigV1**](OpenVPNConfigV1.md) |  | [optional] 
**Projects** | Pointer to [**map[string]ProjectNetworkState**](ProjectNetworkState.md) | An object where the keys are project IDs and the values are {@link ProjectNetworkState} objects representing the state of each project. | [optional] 
**CreatedAt** | **string** | Created Date in ISO-8601 format e.g., \&quot;2022-05-06T02:39:23.000Z\&quot; | 
**UpdatedAt** | **string** | Updated Date in ISO-8601 format e.g., \&quot;2022-05-06T02:39:23.000Z\&quot; | 
**CreatedBy** | **string** | UUIDv4 of the user who created this record. | 
**UpdatedBy** | **string** | UUIDv4 of the user who last updated this record. | 

## Methods

### NewOpenVPNNetworkConnectionV1

`func NewOpenVPNNetworkConnectionV1(identifier string, provider string, name string, createdAt string, updatedAt string, createdBy string, updatedBy string, ) *OpenVPNNetworkConnectionV1`

NewOpenVPNNetworkConnectionV1 instantiates a new OpenVPNNetworkConnectionV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenVPNNetworkConnectionV1WithDefaults

`func NewOpenVPNNetworkConnectionV1WithDefaults() *OpenVPNNetworkConnectionV1`

NewOpenVPNNetworkConnectionV1WithDefaults instantiates a new OpenVPNNetworkConnectionV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *OpenVPNNetworkConnectionV1) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *OpenVPNNetworkConnectionV1) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *OpenVPNNetworkConnectionV1) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetProvider

`func (o *OpenVPNNetworkConnectionV1) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *OpenVPNNetworkConnectionV1) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *OpenVPNNetworkConnectionV1) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetName

`func (o *OpenVPNNetworkConnectionV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OpenVPNNetworkConnectionV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OpenVPNNetworkConnectionV1) SetName(v string)`

SetName sets Name field to given value.


### GetConfig

`func (o *OpenVPNNetworkConnectionV1) GetConfig() OpenVPNConfigV1`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *OpenVPNNetworkConnectionV1) GetConfigOk() (*OpenVPNConfigV1, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *OpenVPNNetworkConnectionV1) SetConfig(v OpenVPNConfigV1)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *OpenVPNNetworkConnectionV1) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### SetConfigNil

`func (o *OpenVPNNetworkConnectionV1) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *OpenVPNNetworkConnectionV1) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetProjects

`func (o *OpenVPNNetworkConnectionV1) GetProjects() map[string]ProjectNetworkState`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *OpenVPNNetworkConnectionV1) GetProjectsOk() (*map[string]ProjectNetworkState, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *OpenVPNNetworkConnectionV1) SetProjects(v map[string]ProjectNetworkState)`

SetProjects sets Projects field to given value.

### HasProjects

`func (o *OpenVPNNetworkConnectionV1) HasProjects() bool`

HasProjects returns a boolean if a field has been set.

### SetProjectsNil

`func (o *OpenVPNNetworkConnectionV1) SetProjectsNil(b bool)`

 SetProjectsNil sets the value for Projects to be an explicit nil

### UnsetProjects
`func (o *OpenVPNNetworkConnectionV1) UnsetProjects()`

UnsetProjects ensures that no value is present for Projects, not even an explicit nil
### GetCreatedAt

`func (o *OpenVPNNetworkConnectionV1) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OpenVPNNetworkConnectionV1) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OpenVPNNetworkConnectionV1) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OpenVPNNetworkConnectionV1) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OpenVPNNetworkConnectionV1) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OpenVPNNetworkConnectionV1) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetCreatedBy

`func (o *OpenVPNNetworkConnectionV1) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *OpenVPNNetworkConnectionV1) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *OpenVPNNetworkConnectionV1) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetUpdatedBy

`func (o *OpenVPNNetworkConnectionV1) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *OpenVPNNetworkConnectionV1) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *OpenVPNNetworkConnectionV1) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


