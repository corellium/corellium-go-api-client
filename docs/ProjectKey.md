# ProjectKey

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | **string** | Kind of authorized key: an SSH key for SSH-based devices or an ADB key for Android. | 
**Label** | Pointer to **NullableString** | Descriptive label for the key. | [optional] 
**Key** | **string** | The public key authorized to access devices in the project, in OpenSSH authorized_keys format. | 
**Id** | **string** | Project key identifier. | 
**Project** | **string** | Identifier of the project the key belongs to. | 
**Fingerprint** | **NullableString** | Public key fingerprint. | 
**CreatedAt** | **time.Time** | Time the key was created. | 
**UpdatedAt** | **time.Time** | Time the key was last updated. | 

## Methods

### NewProjectKey

`func NewProjectKey(kind string, key string, id string, project string, fingerprint NullableString, createdAt time.Time, updatedAt time.Time, ) *ProjectKey`

NewProjectKey instantiates a new ProjectKey object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectKeyWithDefaults

`func NewProjectKeyWithDefaults() *ProjectKey`

NewProjectKeyWithDefaults instantiates a new ProjectKey object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *ProjectKey) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ProjectKey) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ProjectKey) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLabel

`func (o *ProjectKey) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ProjectKey) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ProjectKey) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *ProjectKey) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *ProjectKey) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *ProjectKey) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetKey

`func (o *ProjectKey) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *ProjectKey) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *ProjectKey) SetKey(v string)`

SetKey sets Key field to given value.


### GetId

`func (o *ProjectKey) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectKey) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectKey) SetId(v string)`

SetId sets Id field to given value.


### GetProject

`func (o *ProjectKey) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ProjectKey) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ProjectKey) SetProject(v string)`

SetProject sets Project field to given value.


### GetFingerprint

`func (o *ProjectKey) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *ProjectKey) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *ProjectKey) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.


### SetFingerprintNil

`func (o *ProjectKey) SetFingerprintNil(b bool)`

 SetFingerprintNil sets the value for Fingerprint to be an explicit nil

### UnsetFingerprint
`func (o *ProjectKey) UnsetFingerprint()`

UnsetFingerprint ensures that no value is present for Fingerprint, not even an explicit nil
### GetCreatedAt

`func (o *ProjectKey) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectKey) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectKey) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ProjectKey) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ProjectKey) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ProjectKey) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


