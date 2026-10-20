# OpenVPNNetworkConnection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | User friendly name for network connection. | 
**Provider** | **string** | Type of network connection. | 
**Config** | Pointer to [**NullableOpenVPNConfig**](OpenVPNConfig.md) |  | [optional] 
**Identifier** | **string** | Unique identifier for the network connection. | 
**Projects** | Pointer to [**map[string]OpenVPNNetworkConnectionProjectsValue**](OpenVPNNetworkConnectionProjectsValue.md) | Network states mapped by project IDs. | [optional] 
**CreatedAt** | **time.Time** | Timestamp when the network connection was created. | 
**UpdatedAt** | **time.Time** | Timestamp when the network connection was last updated. | 
**CreatedBy** | **string** | User ID of the creator. | 
**UpdatedBy** | **string** | User ID of the last updater. | 

## Methods

### NewOpenVPNNetworkConnection

`func NewOpenVPNNetworkConnection(name string, provider string, identifier string, createdAt time.Time, updatedAt time.Time, createdBy string, updatedBy string, ) *OpenVPNNetworkConnection`

NewOpenVPNNetworkConnection instantiates a new OpenVPNNetworkConnection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenVPNNetworkConnectionWithDefaults

`func NewOpenVPNNetworkConnectionWithDefaults() *OpenVPNNetworkConnection`

NewOpenVPNNetworkConnectionWithDefaults instantiates a new OpenVPNNetworkConnection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *OpenVPNNetworkConnection) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OpenVPNNetworkConnection) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OpenVPNNetworkConnection) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *OpenVPNNetworkConnection) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *OpenVPNNetworkConnection) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *OpenVPNNetworkConnection) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetConfig

`func (o *OpenVPNNetworkConnection) GetConfig() OpenVPNConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *OpenVPNNetworkConnection) GetConfigOk() (*OpenVPNConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *OpenVPNNetworkConnection) SetConfig(v OpenVPNConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *OpenVPNNetworkConnection) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### SetConfigNil

`func (o *OpenVPNNetworkConnection) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *OpenVPNNetworkConnection) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetIdentifier

`func (o *OpenVPNNetworkConnection) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *OpenVPNNetworkConnection) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *OpenVPNNetworkConnection) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetProjects

`func (o *OpenVPNNetworkConnection) GetProjects() map[string]OpenVPNNetworkConnectionProjectsValue`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *OpenVPNNetworkConnection) GetProjectsOk() (*map[string]OpenVPNNetworkConnectionProjectsValue, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *OpenVPNNetworkConnection) SetProjects(v map[string]OpenVPNNetworkConnectionProjectsValue)`

SetProjects sets Projects field to given value.

### HasProjects

`func (o *OpenVPNNetworkConnection) HasProjects() bool`

HasProjects returns a boolean if a field has been set.

### GetCreatedAt

`func (o *OpenVPNNetworkConnection) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OpenVPNNetworkConnection) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OpenVPNNetworkConnection) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OpenVPNNetworkConnection) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OpenVPNNetworkConnection) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OpenVPNNetworkConnection) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetCreatedBy

`func (o *OpenVPNNetworkConnection) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *OpenVPNNetworkConnection) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *OpenVPNNetworkConnection) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetUpdatedBy

`func (o *OpenVPNNetworkConnection) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *OpenVPNNetworkConnection) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *OpenVPNNetworkConnection) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


