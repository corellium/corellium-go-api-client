# VLANNetworkConnection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | User friendly name for network connection. | 
**Provider** | **string** | Type of network connection. | 
**Config** | Pointer to [**NullableVLANConfig**](VLANConfig.md) |  | [optional] 
**Identifier** | **string** | Unique identifier for the network connection. | 
**Projects** | Pointer to [**map[string]OpenVPNNetworkConnectionProjectsValue**](OpenVPNNetworkConnectionProjectsValue.md) | Network states mapped by project IDs. | [optional] 
**CreatedAt** | **time.Time** | Timestamp when the network connection was created. | 
**UpdatedAt** | **time.Time** | Timestamp when the network connection was last updated. | 
**CreatedBy** | **string** | User ID of the creator. | 
**UpdatedBy** | **string** | User ID of the last updater. | 

## Methods

### NewVLANNetworkConnection

`func NewVLANNetworkConnection(name string, provider string, identifier string, createdAt time.Time, updatedAt time.Time, createdBy string, updatedBy string, ) *VLANNetworkConnection`

NewVLANNetworkConnection instantiates a new VLANNetworkConnection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVLANNetworkConnectionWithDefaults

`func NewVLANNetworkConnectionWithDefaults() *VLANNetworkConnection`

NewVLANNetworkConnectionWithDefaults instantiates a new VLANNetworkConnection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *VLANNetworkConnection) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VLANNetworkConnection) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VLANNetworkConnection) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *VLANNetworkConnection) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *VLANNetworkConnection) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *VLANNetworkConnection) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetConfig

`func (o *VLANNetworkConnection) GetConfig() VLANConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *VLANNetworkConnection) GetConfigOk() (*VLANConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *VLANNetworkConnection) SetConfig(v VLANConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *VLANNetworkConnection) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### SetConfigNil

`func (o *VLANNetworkConnection) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *VLANNetworkConnection) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetIdentifier

`func (o *VLANNetworkConnection) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *VLANNetworkConnection) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *VLANNetworkConnection) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetProjects

`func (o *VLANNetworkConnection) GetProjects() map[string]OpenVPNNetworkConnectionProjectsValue`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *VLANNetworkConnection) GetProjectsOk() (*map[string]OpenVPNNetworkConnectionProjectsValue, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *VLANNetworkConnection) SetProjects(v map[string]OpenVPNNetworkConnectionProjectsValue)`

SetProjects sets Projects field to given value.

### HasProjects

`func (o *VLANNetworkConnection) HasProjects() bool`

HasProjects returns a boolean if a field has been set.

### GetCreatedAt

`func (o *VLANNetworkConnection) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *VLANNetworkConnection) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *VLANNetworkConnection) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *VLANNetworkConnection) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *VLANNetworkConnection) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *VLANNetworkConnection) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetCreatedBy

`func (o *VLANNetworkConnection) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *VLANNetworkConnection) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *VLANNetworkConnection) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetUpdatedBy

`func (o *VLANNetworkConnection) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *VLANNetworkConnection) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *VLANNetworkConnection) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


