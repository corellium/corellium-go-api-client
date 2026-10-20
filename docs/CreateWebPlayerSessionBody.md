# CreateWebPlayerSessionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **string** | Project the device is in. | 
**InstanceId** | **string** | The device (instance) the viewer will see and control. | 
**ExpiresIn** | **float32** | How long the session token stays valid, in seconds. At least 1800 (30 minutes). Renewing the token keeps the same length. | 
**Features** | [**WebPlayerFeatures**](WebPlayerFeatures.md) |  | 
**ClientId** | Pointer to **string** | Optional client-supplied tracking string. | [optional] 

## Methods

### NewCreateWebPlayerSessionBody

`func NewCreateWebPlayerSessionBody(projectId string, instanceId string, expiresIn float32, features WebPlayerFeatures, ) *CreateWebPlayerSessionBody`

NewCreateWebPlayerSessionBody instantiates a new CreateWebPlayerSessionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWebPlayerSessionBodyWithDefaults

`func NewCreateWebPlayerSessionBodyWithDefaults() *CreateWebPlayerSessionBody`

NewCreateWebPlayerSessionBodyWithDefaults instantiates a new CreateWebPlayerSessionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CreateWebPlayerSessionBody) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateWebPlayerSessionBody) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateWebPlayerSessionBody) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetInstanceId

`func (o *CreateWebPlayerSessionBody) GetInstanceId() string`

GetInstanceId returns the InstanceId field if non-nil, zero value otherwise.

### GetInstanceIdOk

`func (o *CreateWebPlayerSessionBody) GetInstanceIdOk() (*string, bool)`

GetInstanceIdOk returns a tuple with the InstanceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceId

`func (o *CreateWebPlayerSessionBody) SetInstanceId(v string)`

SetInstanceId sets InstanceId field to given value.


### GetExpiresIn

`func (o *CreateWebPlayerSessionBody) GetExpiresIn() float32`

GetExpiresIn returns the ExpiresIn field if non-nil, zero value otherwise.

### GetExpiresInOk

`func (o *CreateWebPlayerSessionBody) GetExpiresInOk() (*float32, bool)`

GetExpiresInOk returns a tuple with the ExpiresIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresIn

`func (o *CreateWebPlayerSessionBody) SetExpiresIn(v float32)`

SetExpiresIn sets ExpiresIn field to given value.


### GetFeatures

`func (o *CreateWebPlayerSessionBody) GetFeatures() WebPlayerFeatures`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *CreateWebPlayerSessionBody) GetFeaturesOk() (*WebPlayerFeatures, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *CreateWebPlayerSessionBody) SetFeatures(v WebPlayerFeatures)`

SetFeatures sets Features field to given value.


### GetClientId

`func (o *CreateWebPlayerSessionBody) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *CreateWebPlayerSessionBody) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *CreateWebPlayerSessionBody) SetClientId(v string)`

SetClientId sets ClientId field to given value.

### HasClientId

`func (o *CreateWebPlayerSessionBody) HasClientId() bool`

HasClientId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


