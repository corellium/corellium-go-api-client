# AgentProfileListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Profiles** | **[]string** | Identifiers of the installed profiles. | 

## Methods

### NewAgentProfileListResponse

`func NewAgentProfileListResponse(profiles []string, ) *AgentProfileListResponse`

NewAgentProfileListResponse instantiates a new AgentProfileListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentProfileListResponseWithDefaults

`func NewAgentProfileListResponseWithDefaults() *AgentProfileListResponse`

NewAgentProfileListResponseWithDefaults instantiates a new AgentProfileListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProfiles

`func (o *AgentProfileListResponse) GetProfiles() []string`

GetProfiles returns the Profiles field if non-nil, zero value otherwise.

### GetProfilesOk

`func (o *AgentProfileListResponse) GetProfilesOk() (*[]string, bool)`

GetProfilesOk returns a tuple with the Profiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfiles

`func (o *AgentProfileListResponse) SetProfiles(v []string)`

SetProfiles sets Profiles field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


