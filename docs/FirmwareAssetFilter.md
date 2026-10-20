# FirmwareAssetFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | Pointer to **string** | Filter by exact URL. | [optional] 
**Domain** | Pointer to **string** | Filter by exact domain. | [optional] 

## Methods

### NewFirmwareAssetFilter

`func NewFirmwareAssetFilter() *FirmwareAssetFilter`

NewFirmwareAssetFilter instantiates a new FirmwareAssetFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareAssetFilterWithDefaults

`func NewFirmwareAssetFilterWithDefaults() *FirmwareAssetFilter`

NewFirmwareAssetFilterWithDefaults instantiates a new FirmwareAssetFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *FirmwareAssetFilter) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FirmwareAssetFilter) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FirmwareAssetFilter) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *FirmwareAssetFilter) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetDomain

`func (o *FirmwareAssetFilter) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *FirmwareAssetFilter) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *FirmwareAssetFilter) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *FirmwareAssetFilter) HasDomain() bool`

HasDomain returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


