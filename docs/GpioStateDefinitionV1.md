# GpioStateDefinitionV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BitCount** | **float32** | count of bits in members of this bank | 
**Banks** | [**[][]Bit**]([]Bit.md) | bits for each bank of this name as an array of arrays | 

## Methods

### NewGpioStateDefinitionV1

`func NewGpioStateDefinitionV1(bitCount float32, banks [][]Bit, ) *GpioStateDefinitionV1`

NewGpioStateDefinitionV1 instantiates a new GpioStateDefinitionV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGpioStateDefinitionV1WithDefaults

`func NewGpioStateDefinitionV1WithDefaults() *GpioStateDefinitionV1`

NewGpioStateDefinitionV1WithDefaults instantiates a new GpioStateDefinitionV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBitCount

`func (o *GpioStateDefinitionV1) GetBitCount() float32`

GetBitCount returns the BitCount field if non-nil, zero value otherwise.

### GetBitCountOk

`func (o *GpioStateDefinitionV1) GetBitCountOk() (*float32, bool)`

GetBitCountOk returns a tuple with the BitCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBitCount

`func (o *GpioStateDefinitionV1) SetBitCount(v float32)`

SetBitCount sets BitCount field to given value.


### GetBanks

`func (o *GpioStateDefinitionV1) GetBanks() [][]Bit`

GetBanks returns the Banks field if non-nil, zero value otherwise.

### GetBanksOk

`func (o *GpioStateDefinitionV1) GetBanksOk() (*[][]Bit, bool)`

GetBanksOk returns a tuple with the Banks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBanks

`func (o *GpioStateDefinitionV1) SetBanks(v [][]Bit)`

SetBanks sets Banks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


