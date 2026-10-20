# AgentRemoteItStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RemoteItStatus** | **string** | Installation state of the Remote.It package. | 
**ClaimCode** | Pointer to **string** | Remote.It claim code, present once the package is installed and claimable. | [optional] 

## Methods

### NewAgentRemoteItStatus

`func NewAgentRemoteItStatus(remoteItStatus string, ) *AgentRemoteItStatus`

NewAgentRemoteItStatus instantiates a new AgentRemoteItStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentRemoteItStatusWithDefaults

`func NewAgentRemoteItStatusWithDefaults() *AgentRemoteItStatus`

NewAgentRemoteItStatusWithDefaults instantiates a new AgentRemoteItStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRemoteItStatus

`func (o *AgentRemoteItStatus) GetRemoteItStatus() string`

GetRemoteItStatus returns the RemoteItStatus field if non-nil, zero value otherwise.

### GetRemoteItStatusOk

`func (o *AgentRemoteItStatus) GetRemoteItStatusOk() (*string, bool)`

GetRemoteItStatusOk returns a tuple with the RemoteItStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteItStatus

`func (o *AgentRemoteItStatus) SetRemoteItStatus(v string)`

SetRemoteItStatus sets RemoteItStatus field to given value.


### GetClaimCode

`func (o *AgentRemoteItStatus) GetClaimCode() string`

GetClaimCode returns the ClaimCode field if non-nil, zero value otherwise.

### GetClaimCodeOk

`func (o *AgentRemoteItStatus) GetClaimCodeOk() (*string, bool)`

GetClaimCodeOk returns a tuple with the ClaimCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimCode

`func (o *AgentRemoteItStatus) SetClaimCode(v string)`

SetClaimCode sets ClaimCode field to given value.

### HasClaimCode

`func (o *AgentRemoteItStatus) HasClaimCode() bool`

HasClaimCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


