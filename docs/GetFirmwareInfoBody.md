# GetFirmwareInfoBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | Pointer to **string** | Password to decrypt an encrypted firmware file. | [optional] 
**Extended** | Pointer to **bool** | Include extended info such as board config, bdid, cpid, platform, and the matched device. | [optional] 

## Methods

### NewGetFirmwareInfoBody

`func NewGetFirmwareInfoBody() *GetFirmwareInfoBody`

NewGetFirmwareInfoBody instantiates a new GetFirmwareInfoBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetFirmwareInfoBodyWithDefaults

`func NewGetFirmwareInfoBodyWithDefaults() *GetFirmwareInfoBody`

NewGetFirmwareInfoBodyWithDefaults instantiates a new GetFirmwareInfoBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *GetFirmwareInfoBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *GetFirmwareInfoBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *GetFirmwareInfoBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *GetFirmwareInfoBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetExtended

`func (o *GetFirmwareInfoBody) GetExtended() bool`

GetExtended returns the Extended field if non-nil, zero value otherwise.

### GetExtendedOk

`func (o *GetFirmwareInfoBody) GetExtendedOk() (*bool, bool)`

GetExtendedOk returns a tuple with the Extended field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtended

`func (o *GetFirmwareInfoBody) SetExtended(v bool)`

SetExtended sets Extended field to given value.

### HasExtended

`func (o *GetFirmwareInfoBody) HasExtended() bool`

HasExtended returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


