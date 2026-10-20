# RestoreBackupData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | Pointer to **NullableString** | Required for encrypted backup | [optional] 

## Methods

### NewRestoreBackupData

`func NewRestoreBackupData() *RestoreBackupData`

NewRestoreBackupData instantiates a new RestoreBackupData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRestoreBackupDataWithDefaults

`func NewRestoreBackupDataWithDefaults() *RestoreBackupData`

NewRestoreBackupDataWithDefaults instantiates a new RestoreBackupData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *RestoreBackupData) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *RestoreBackupData) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *RestoreBackupData) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *RestoreBackupData) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### SetPasswordNil

`func (o *RestoreBackupData) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *RestoreBackupData) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


