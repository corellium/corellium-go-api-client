# ExtensionV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **NullableString** | Identifier | [optional] 
**Enabled** | Pointer to **NullableBool** | If true, instances requiring this extension can be created or started | [optional] 
**CreatedAt** | Pointer to **NullableString** | Created Date in ISO-8601 format e.g. 2022-05-06T02:39:23.000Z | [optional] 
**UpdatedAt** | Pointer to **NullableString** | Updated Date in ISO-8601 format e.g. 2022-05-06T02:39:23.000Z | [optional] 
**ImageId** | Pointer to **NullableString** | Image Id | [optional] 
**State** | Pointer to **NullableString** | State | [optional] 
**Flavors** | Pointer to **[]map[string]interface{}** | Array of Flavor definitions | [optional] 

## Methods

### NewExtensionV1

`func NewExtensionV1() *ExtensionV1`

NewExtensionV1 instantiates a new ExtensionV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExtensionV1WithDefaults

`func NewExtensionV1WithDefaults() *ExtensionV1`

NewExtensionV1WithDefaults instantiates a new ExtensionV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *ExtensionV1) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ExtensionV1) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ExtensionV1) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *ExtensionV1) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### SetIdentifierNil

`func (o *ExtensionV1) SetIdentifierNil(b bool)`

 SetIdentifierNil sets the value for Identifier to be an explicit nil

### UnsetIdentifier
`func (o *ExtensionV1) UnsetIdentifier()`

UnsetIdentifier ensures that no value is present for Identifier, not even an explicit nil
### GetEnabled

`func (o *ExtensionV1) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ExtensionV1) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ExtensionV1) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ExtensionV1) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### SetEnabledNil

`func (o *ExtensionV1) SetEnabledNil(b bool)`

 SetEnabledNil sets the value for Enabled to be an explicit nil

### UnsetEnabled
`func (o *ExtensionV1) UnsetEnabled()`

UnsetEnabled ensures that no value is present for Enabled, not even an explicit nil
### GetCreatedAt

`func (o *ExtensionV1) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ExtensionV1) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ExtensionV1) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ExtensionV1) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *ExtensionV1) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ExtensionV1) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *ExtensionV1) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ExtensionV1) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ExtensionV1) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ExtensionV1) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *ExtensionV1) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *ExtensionV1) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetImageId

`func (o *ExtensionV1) GetImageId() string`

GetImageId returns the ImageId field if non-nil, zero value otherwise.

### GetImageIdOk

`func (o *ExtensionV1) GetImageIdOk() (*string, bool)`

GetImageIdOk returns a tuple with the ImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageId

`func (o *ExtensionV1) SetImageId(v string)`

SetImageId sets ImageId field to given value.

### HasImageId

`func (o *ExtensionV1) HasImageId() bool`

HasImageId returns a boolean if a field has been set.

### SetImageIdNil

`func (o *ExtensionV1) SetImageIdNil(b bool)`

 SetImageIdNil sets the value for ImageId to be an explicit nil

### UnsetImageId
`func (o *ExtensionV1) UnsetImageId()`

UnsetImageId ensures that no value is present for ImageId, not even an explicit nil
### GetState

`func (o *ExtensionV1) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ExtensionV1) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ExtensionV1) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ExtensionV1) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *ExtensionV1) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *ExtensionV1) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetFlavors

`func (o *ExtensionV1) GetFlavors() []map[string]interface{}`

GetFlavors returns the Flavors field if non-nil, zero value otherwise.

### GetFlavorsOk

`func (o *ExtensionV1) GetFlavorsOk() (*[]map[string]interface{}, bool)`

GetFlavorsOk returns a tuple with the Flavors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavors

`func (o *ExtensionV1) SetFlavors(v []map[string]interface{})`

SetFlavors sets Flavors field to given value.

### HasFlavors

`func (o *ExtensionV1) HasFlavors() bool`

HasFlavors returns a boolean if a field has been set.

### SetFlavorsNil

`func (o *ExtensionV1) SetFlavorsNil(b bool)`

 SetFlavorsNil sets the value for Flavors to be an explicit nil

### UnsetFlavors
`func (o *ExtensionV1) UnsetFlavors()`

UnsetFlavors ensures that no value is present for Flavors, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


