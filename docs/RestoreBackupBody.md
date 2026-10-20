# RestoreBackupBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | Pointer to **string** | Password of the backup file. Needed only if the backup is encrypted; leave it out for an unencrypted backup. | [optional] 

## Methods

### NewRestoreBackupBody

`func NewRestoreBackupBody() *RestoreBackupBody`

NewRestoreBackupBody instantiates a new RestoreBackupBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRestoreBackupBodyWithDefaults

`func NewRestoreBackupBodyWithDefaults() *RestoreBackupBody`

NewRestoreBackupBodyWithDefaults instantiates a new RestoreBackupBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *RestoreBackupBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *RestoreBackupBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *RestoreBackupBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *RestoreBackupBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


