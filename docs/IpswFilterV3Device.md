# IpswFilterV3Device

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Product** | Pointer to **NullableString** | Device product regex pattern (e.g. \&quot;iPhone16,.*\&quot;). | [optional] 

## Methods

### NewIpswFilterV3Device

`func NewIpswFilterV3Device() *IpswFilterV3Device`

NewIpswFilterV3Device instantiates a new IpswFilterV3Device object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpswFilterV3DeviceWithDefaults

`func NewIpswFilterV3DeviceWithDefaults() *IpswFilterV3Device`

NewIpswFilterV3DeviceWithDefaults instantiates a new IpswFilterV3Device object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProduct

`func (o *IpswFilterV3Device) GetProduct() string`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *IpswFilterV3Device) GetProductOk() (*string, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *IpswFilterV3Device) SetProduct(v string)`

SetProduct sets Product field to given value.

### HasProduct

`func (o *IpswFilterV3Device) HasProduct() bool`

HasProduct returns a boolean if a field has been set.

### SetProductNil

`func (o *IpswFilterV3Device) SetProductNil(b bool)`

 SetProductNil sets the value for Product to be an explicit nil

### UnsetProduct
`func (o *IpswFilterV3Device) UnsetProduct()`

UnsetProduct ensures that no value is present for Product, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


