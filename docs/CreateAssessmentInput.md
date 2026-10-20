# CreateAssessmentInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InstanceId** | **string** | Identifier of the instance to assess. | 
**BundleId** | **string** | Bundle identifier of the application to assess. | 
**WordlistId** | Pointer to **string** | ID of a wordlist: a plain-text file listing sensitive values (one per line), such as test passwords or account numbers, that MATRIX then looks for while testing the app. Upload the file first with &#x60;POST /v3/images&#x60; with &#x60;instanceId&#x60; set to this instance (use &#x60;type: \&quot;mast-wordlist\&quot;&#x60;), then pass the returned image ID here. The server only checks that an image with this ID exists on the instance, not its type, so make sure you pass the right file. The request fails if the image cannot be found. Deleting the assessment also deletes this file. | [optional] 
**FridaScriptId** | Pointer to **string** | ID of your own Frida script (JavaScript) to load into the app while it is being monitored, for example to bypass certificate pinning or reach code paths that are hard to trigger. Upload it first with &#x60;POST /v3/images&#x60; with &#x60;instanceId&#x60; set to this instance (use &#x60;type: \&quot;mast-frida\&quot;&#x60;). The server only checks that an image with this ID exists on the instance, not its type. The request fails if the image cannot be found. The script is not deleted when the assessment is. | [optional] 
**CreatedBy** | Pointer to **string** | Identifier of the user creating the assessment. Assigned server-side from the auth context; client-supplied values are ignored. | [optional] 

## Methods

### NewCreateAssessmentInput

`func NewCreateAssessmentInput(instanceId string, bundleId string, ) *CreateAssessmentInput`

NewCreateAssessmentInput instantiates a new CreateAssessmentInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAssessmentInputWithDefaults

`func NewCreateAssessmentInputWithDefaults() *CreateAssessmentInput`

NewCreateAssessmentInputWithDefaults instantiates a new CreateAssessmentInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInstanceId

`func (o *CreateAssessmentInput) GetInstanceId() string`

GetInstanceId returns the InstanceId field if non-nil, zero value otherwise.

### GetInstanceIdOk

`func (o *CreateAssessmentInput) GetInstanceIdOk() (*string, bool)`

GetInstanceIdOk returns a tuple with the InstanceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceId

`func (o *CreateAssessmentInput) SetInstanceId(v string)`

SetInstanceId sets InstanceId field to given value.


### GetBundleId

`func (o *CreateAssessmentInput) GetBundleId() string`

GetBundleId returns the BundleId field if non-nil, zero value otherwise.

### GetBundleIdOk

`func (o *CreateAssessmentInput) GetBundleIdOk() (*string, bool)`

GetBundleIdOk returns a tuple with the BundleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleId

`func (o *CreateAssessmentInput) SetBundleId(v string)`

SetBundleId sets BundleId field to given value.


### GetWordlistId

`func (o *CreateAssessmentInput) GetWordlistId() string`

GetWordlistId returns the WordlistId field if non-nil, zero value otherwise.

### GetWordlistIdOk

`func (o *CreateAssessmentInput) GetWordlistIdOk() (*string, bool)`

GetWordlistIdOk returns a tuple with the WordlistId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWordlistId

`func (o *CreateAssessmentInput) SetWordlistId(v string)`

SetWordlistId sets WordlistId field to given value.

### HasWordlistId

`func (o *CreateAssessmentInput) HasWordlistId() bool`

HasWordlistId returns a boolean if a field has been set.

### GetFridaScriptId

`func (o *CreateAssessmentInput) GetFridaScriptId() string`

GetFridaScriptId returns the FridaScriptId field if non-nil, zero value otherwise.

### GetFridaScriptIdOk

`func (o *CreateAssessmentInput) GetFridaScriptIdOk() (*string, bool)`

GetFridaScriptIdOk returns a tuple with the FridaScriptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFridaScriptId

`func (o *CreateAssessmentInput) SetFridaScriptId(v string)`

SetFridaScriptId sets FridaScriptId field to given value.

### HasFridaScriptId

`func (o *CreateAssessmentInput) HasFridaScriptId() bool`

HasFridaScriptId returns a boolean if a field has been set.

### GetCreatedBy

`func (o *CreateAssessmentInput) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *CreateAssessmentInput) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *CreateAssessmentInput) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *CreateAssessmentInput) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


