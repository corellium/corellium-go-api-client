# TestAssessmentInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Invert** | Pointer to **NullableBool** | Optional, default false. When true, run every check EXCEPT those matched by &#x60;grep&#x60;. Has no effect without &#x60;grep&#x60;. | [optional] 
**Grep** | Pointer to **string** | A JavaScript regular expression; only checks whose check ID, group ID, or category ID matches it are run. Without anchors (&#x60;^&#x60;, &#x60;$&#x60;) it can match anywhere in the ID, so &#x60;masvs-storage&#x60; selects every storage check. Characters such as &#x60;.&#x60; have their regular-expression meaning. To add flags, wrap the pattern in slashes, for example &#x60;/^masvs-network-1-ios-/i&#x60;. Omit to run every applicable check. | [optional] 

## Methods

### NewTestAssessmentInput

`func NewTestAssessmentInput() *TestAssessmentInput`

NewTestAssessmentInput instantiates a new TestAssessmentInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTestAssessmentInputWithDefaults

`func NewTestAssessmentInputWithDefaults() *TestAssessmentInput`

NewTestAssessmentInputWithDefaults instantiates a new TestAssessmentInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInvert

`func (o *TestAssessmentInput) GetInvert() bool`

GetInvert returns the Invert field if non-nil, zero value otherwise.

### GetInvertOk

`func (o *TestAssessmentInput) GetInvertOk() (*bool, bool)`

GetInvertOk returns a tuple with the Invert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvert

`func (o *TestAssessmentInput) SetInvert(v bool)`

SetInvert sets Invert field to given value.

### HasInvert

`func (o *TestAssessmentInput) HasInvert() bool`

HasInvert returns a boolean if a field has been set.

### SetInvertNil

`func (o *TestAssessmentInput) SetInvertNil(b bool)`

 SetInvertNil sets the value for Invert to be an explicit nil

### UnsetInvert
`func (o *TestAssessmentInput) UnsetInvert()`

UnsetInvert ensures that no value is present for Invert, not even an explicit nil
### GetGrep

`func (o *TestAssessmentInput) GetGrep() string`

GetGrep returns the Grep field if non-nil, zero value otherwise.

### GetGrepOk

`func (o *TestAssessmentInput) GetGrepOk() (*string, bool)`

GetGrepOk returns a tuple with the Grep field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrep

`func (o *TestAssessmentInput) SetGrep(v string)`

SetGrep sets Grep field to given value.

### HasGrep

`func (o *TestAssessmentInput) HasGrep() bool`

HasGrep returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


