# ServiceEndpointSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServiceName** | Pointer to **string** | Service name (e.g. mast, c3po, iptables-nat). | [optional] 
**Path** | **string** | Endpoint path, following /:apiVersion/. | 
**Method** | **string** | HTTP method (e.g. GET, POST). | 
**Permissions** | **[]string** | Required permissions (e.g. projectMember, cloud-administrator, domain-administrator, administrator). | 

## Methods

### NewServiceEndpointSchema

`func NewServiceEndpointSchema(path string, method string, permissions []string, ) *ServiceEndpointSchema`

NewServiceEndpointSchema instantiates a new ServiceEndpointSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceEndpointSchemaWithDefaults

`func NewServiceEndpointSchemaWithDefaults() *ServiceEndpointSchema`

NewServiceEndpointSchemaWithDefaults instantiates a new ServiceEndpointSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServiceName

`func (o *ServiceEndpointSchema) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *ServiceEndpointSchema) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *ServiceEndpointSchema) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *ServiceEndpointSchema) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.

### GetPath

`func (o *ServiceEndpointSchema) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ServiceEndpointSchema) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ServiceEndpointSchema) SetPath(v string)`

SetPath sets Path field to given value.


### GetMethod

`func (o *ServiceEndpointSchema) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *ServiceEndpointSchema) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *ServiceEndpointSchema) SetMethod(v string)`

SetMethod sets Method field to given value.


### GetPermissions

`func (o *ServiceEndpointSchema) GetPermissions() []string`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *ServiceEndpointSchema) GetPermissionsOk() (*[]string, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *ServiceEndpointSchema) SetPermissions(v []string)`

SetPermissions sets Permissions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


