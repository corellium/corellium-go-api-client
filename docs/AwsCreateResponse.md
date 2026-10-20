# AwsCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ready** | **bool** | Whether the account is ready. | 
**IsAuthed** | **bool** | Whether the user is authenticated. | 

## Methods

### NewAwsCreateResponse

`func NewAwsCreateResponse(ready bool, isAuthed bool, ) *AwsCreateResponse`

NewAwsCreateResponse instantiates a new AwsCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAwsCreateResponseWithDefaults

`func NewAwsCreateResponseWithDefaults() *AwsCreateResponse`

NewAwsCreateResponseWithDefaults instantiates a new AwsCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReady

`func (o *AwsCreateResponse) GetReady() bool`

GetReady returns the Ready field if non-nil, zero value otherwise.

### GetReadyOk

`func (o *AwsCreateResponse) GetReadyOk() (*bool, bool)`

GetReadyOk returns a tuple with the Ready field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReady

`func (o *AwsCreateResponse) SetReady(v bool)`

SetReady sets Ready field to given value.


### GetIsAuthed

`func (o *AwsCreateResponse) GetIsAuthed() bool`

GetIsAuthed returns the IsAuthed field if non-nil, zero value otherwise.

### GetIsAuthedOk

`func (o *AwsCreateResponse) GetIsAuthedOk() (*bool, bool)`

GetIsAuthedOk returns a tuple with the IsAuthed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAuthed

`func (o *AwsCreateResponse) SetIsAuthed(v bool)`

SetIsAuthed sets IsAuthed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


