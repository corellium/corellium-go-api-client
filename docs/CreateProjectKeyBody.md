# CreateProjectKeyBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | **string** | Kind of authorized key: an SSH key for SSH-based devices or an ADB key for Android. | 
**Label** | Pointer to **NullableString** | Descriptive label for the key. | [optional] 
**Key** | **string** | The public key authorized to access devices in the project, in OpenSSH authorized_keys format. | 

## Methods

### NewCreateProjectKeyBody

`func NewCreateProjectKeyBody(kind string, key string, ) *CreateProjectKeyBody`

NewCreateProjectKeyBody instantiates a new CreateProjectKeyBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateProjectKeyBodyWithDefaults

`func NewCreateProjectKeyBodyWithDefaults() *CreateProjectKeyBody`

NewCreateProjectKeyBodyWithDefaults instantiates a new CreateProjectKeyBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *CreateProjectKeyBody) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CreateProjectKeyBody) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CreateProjectKeyBody) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLabel

`func (o *CreateProjectKeyBody) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateProjectKeyBody) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateProjectKeyBody) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *CreateProjectKeyBody) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *CreateProjectKeyBody) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *CreateProjectKeyBody) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetKey

`func (o *CreateProjectKeyBody) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CreateProjectKeyBody) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CreateProjectKeyBody) SetKey(v string)`

SetKey sets Key field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


