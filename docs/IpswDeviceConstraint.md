# IpswDeviceConstraint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Product** | Pointer to **NullableString** | Device product regex pattern (e.g. \&quot;iPhone16,.*\&quot;) | [optional] 

## Methods

### NewIpswDeviceConstraint

`func NewIpswDeviceConstraint() *IpswDeviceConstraint`

NewIpswDeviceConstraint instantiates a new IpswDeviceConstraint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpswDeviceConstraintWithDefaults

`func NewIpswDeviceConstraintWithDefaults() *IpswDeviceConstraint`

NewIpswDeviceConstraintWithDefaults instantiates a new IpswDeviceConstraint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProduct

`func (o *IpswDeviceConstraint) GetProduct() string`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *IpswDeviceConstraint) GetProductOk() (*string, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *IpswDeviceConstraint) SetProduct(v string)`

SetProduct sets Product field to given value.

### HasProduct

`func (o *IpswDeviceConstraint) HasProduct() bool`

HasProduct returns a boolean if a field has been set.

### SetProductNil

`func (o *IpswDeviceConstraint) SetProductNil(b bool)`

 SetProductNil sets the value for Product to be an explicit nil

### UnsetProduct
`func (o *IpswDeviceConstraint) UnsetProduct()`

UnsetProduct ensures that no value is present for Product, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


