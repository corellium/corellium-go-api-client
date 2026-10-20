# LoggingV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Development** | Pointer to **NullableBool** | Denotes whether it&#39;s in development | [optional] 
**ThrowWarnings** | Pointer to **NullableBool** | Denotes whether to throw warnings | [optional] 

## Methods

### NewLoggingV1

`func NewLoggingV1() *LoggingV1`

NewLoggingV1 instantiates a new LoggingV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoggingV1WithDefaults

`func NewLoggingV1WithDefaults() *LoggingV1`

NewLoggingV1WithDefaults instantiates a new LoggingV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevelopment

`func (o *LoggingV1) GetDevelopment() bool`

GetDevelopment returns the Development field if non-nil, zero value otherwise.

### GetDevelopmentOk

`func (o *LoggingV1) GetDevelopmentOk() (*bool, bool)`

GetDevelopmentOk returns a tuple with the Development field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevelopment

`func (o *LoggingV1) SetDevelopment(v bool)`

SetDevelopment sets Development field to given value.

### HasDevelopment

`func (o *LoggingV1) HasDevelopment() bool`

HasDevelopment returns a boolean if a field has been set.

### SetDevelopmentNil

`func (o *LoggingV1) SetDevelopmentNil(b bool)`

 SetDevelopmentNil sets the value for Development to be an explicit nil

### UnsetDevelopment
`func (o *LoggingV1) UnsetDevelopment()`

UnsetDevelopment ensures that no value is present for Development, not even an explicit nil
### GetThrowWarnings

`func (o *LoggingV1) GetThrowWarnings() bool`

GetThrowWarnings returns the ThrowWarnings field if non-nil, zero value otherwise.

### GetThrowWarningsOk

`func (o *LoggingV1) GetThrowWarningsOk() (*bool, bool)`

GetThrowWarningsOk returns a tuple with the ThrowWarnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThrowWarnings

`func (o *LoggingV1) SetThrowWarnings(v bool)`

SetThrowWarnings sets ThrowWarnings field to given value.

### HasThrowWarnings

`func (o *LoggingV1) HasThrowWarnings() bool`

HasThrowWarnings returns a boolean if a field has been set.

### SetThrowWarningsNil

`func (o *LoggingV1) SetThrowWarningsNil(b bool)`

 SetThrowWarningsNil sets the value for ThrowWarnings to be an explicit nil

### UnsetThrowWarnings
`func (o *LoggingV1) UnsetThrowWarnings()`

UnsetThrowWarnings ensures that no value is present for ThrowWarnings, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


