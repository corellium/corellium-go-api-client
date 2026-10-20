# RegisterServiceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | **string** | Service password, must match the configured service password. | 
**NodeId** | **string** | Node identifier. | 
**Address** | **string** | Service address (IP:Port). | 
**ServiceName** | **string** | Service name (e.g. mast, c3po, iptables-nat). | 
**Endpoints** | Pointer to [**[]ServiceEndpointSchema**](ServiceEndpointSchema.md) | Endpoints this service exposes. Replaces any previously registered endpoints for this address. | [optional] 
**IdentityKey** | **string** | Identity key for mutual authentication. | 
**CaCert** | **string** | CA certificate. | 
**CertFingerprint** | **string** | Certificate fingerprint. | 

## Methods

### NewRegisterServiceBody

`func NewRegisterServiceBody(password string, nodeId string, address string, serviceName string, identityKey string, caCert string, certFingerprint string, ) *RegisterServiceBody`

NewRegisterServiceBody instantiates a new RegisterServiceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegisterServiceBodyWithDefaults

`func NewRegisterServiceBodyWithDefaults() *RegisterServiceBody`

NewRegisterServiceBodyWithDefaults instantiates a new RegisterServiceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *RegisterServiceBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *RegisterServiceBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *RegisterServiceBody) SetPassword(v string)`

SetPassword sets Password field to given value.


### GetNodeId

`func (o *RegisterServiceBody) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *RegisterServiceBody) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *RegisterServiceBody) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetAddress

`func (o *RegisterServiceBody) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *RegisterServiceBody) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *RegisterServiceBody) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetServiceName

`func (o *RegisterServiceBody) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *RegisterServiceBody) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *RegisterServiceBody) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.


### GetEndpoints

`func (o *RegisterServiceBody) GetEndpoints() []ServiceEndpointSchema`

GetEndpoints returns the Endpoints field if non-nil, zero value otherwise.

### GetEndpointsOk

`func (o *RegisterServiceBody) GetEndpointsOk() (*[]ServiceEndpointSchema, bool)`

GetEndpointsOk returns a tuple with the Endpoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpoints

`func (o *RegisterServiceBody) SetEndpoints(v []ServiceEndpointSchema)`

SetEndpoints sets Endpoints field to given value.

### HasEndpoints

`func (o *RegisterServiceBody) HasEndpoints() bool`

HasEndpoints returns a boolean if a field has been set.

### GetIdentityKey

`func (o *RegisterServiceBody) GetIdentityKey() string`

GetIdentityKey returns the IdentityKey field if non-nil, zero value otherwise.

### GetIdentityKeyOk

`func (o *RegisterServiceBody) GetIdentityKeyOk() (*string, bool)`

GetIdentityKeyOk returns a tuple with the IdentityKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityKey

`func (o *RegisterServiceBody) SetIdentityKey(v string)`

SetIdentityKey sets IdentityKey field to given value.


### GetCaCert

`func (o *RegisterServiceBody) GetCaCert() string`

GetCaCert returns the CaCert field if non-nil, zero value otherwise.

### GetCaCertOk

`func (o *RegisterServiceBody) GetCaCertOk() (*string, bool)`

GetCaCertOk returns a tuple with the CaCert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaCert

`func (o *RegisterServiceBody) SetCaCert(v string)`

SetCaCert sets CaCert field to given value.


### GetCertFingerprint

`func (o *RegisterServiceBody) GetCertFingerprint() string`

GetCertFingerprint returns the CertFingerprint field if non-nil, zero value otherwise.

### GetCertFingerprintOk

`func (o *RegisterServiceBody) GetCertFingerprintOk() (*string, bool)`

GetCertFingerprintOk returns a tuple with the CertFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertFingerprint

`func (o *RegisterServiceBody) SetCertFingerprint(v string)`

SetCertFingerprint sets CertFingerprint field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


