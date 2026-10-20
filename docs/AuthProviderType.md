# AuthProviderType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProviderType** | **string** | Provider type identifier. | 
**Schema** | **map[string]interface{}** | JSON Schema describing the provider configuration. | 

## Methods

### NewAuthProviderType

`func NewAuthProviderType(providerType string, schema map[string]interface{}, ) *AuthProviderType`

NewAuthProviderType instantiates a new AuthProviderType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthProviderTypeWithDefaults

`func NewAuthProviderTypeWithDefaults() *AuthProviderType`

NewAuthProviderTypeWithDefaults instantiates a new AuthProviderType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProviderType

`func (o *AuthProviderType) GetProviderType() string`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *AuthProviderType) GetProviderTypeOk() (*string, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *AuthProviderType) SetProviderType(v string)`

SetProviderType sets ProviderType field to given value.


### GetSchema

`func (o *AuthProviderType) GetSchema() map[string]interface{}`

GetSchema returns the Schema field if non-nil, zero value otherwise.

### GetSchemaOk

`func (o *AuthProviderType) GetSchemaOk() (*map[string]interface{}, bool)`

GetSchemaOk returns a tuple with the Schema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchema

`func (o *AuthProviderType) SetSchema(v map[string]interface{})`

SetSchema sets Schema field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


