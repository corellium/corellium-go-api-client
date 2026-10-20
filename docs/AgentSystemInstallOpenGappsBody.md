# AgentSystemInstallOpenGappsBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | URL to download the OpenGApps package from. | 
**Hash** | **string** | Expected SHA-256 hash of the downloaded package. | 
**Fingerprint** | **string** | Build fingerprint to install the package against. | 

## Methods

### NewAgentSystemInstallOpenGappsBody

`func NewAgentSystemInstallOpenGappsBody(url string, hash string, fingerprint string, ) *AgentSystemInstallOpenGappsBody`

NewAgentSystemInstallOpenGappsBody instantiates a new AgentSystemInstallOpenGappsBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentSystemInstallOpenGappsBodyWithDefaults

`func NewAgentSystemInstallOpenGappsBodyWithDefaults() *AgentSystemInstallOpenGappsBody`

NewAgentSystemInstallOpenGappsBodyWithDefaults instantiates a new AgentSystemInstallOpenGappsBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *AgentSystemInstallOpenGappsBody) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *AgentSystemInstallOpenGappsBody) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *AgentSystemInstallOpenGappsBody) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetHash

`func (o *AgentSystemInstallOpenGappsBody) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *AgentSystemInstallOpenGappsBody) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *AgentSystemInstallOpenGappsBody) SetHash(v string)`

SetHash sets Hash field to given value.


### GetFingerprint

`func (o *AgentSystemInstallOpenGappsBody) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *AgentSystemInstallOpenGappsBody) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *AgentSystemInstallOpenGappsBody) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


