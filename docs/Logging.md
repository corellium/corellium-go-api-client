# Logging

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Development** | **bool** | Denotes whether it&#39;s in development. | 
**ThrowWarnings** | **bool** | Denotes whether to throw warnings. | 

## Methods

### NewLogging

`func NewLogging(development bool, throwWarnings bool, ) *Logging`

NewLogging instantiates a new Logging object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoggingWithDefaults

`func NewLoggingWithDefaults() *Logging`

NewLoggingWithDefaults instantiates a new Logging object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevelopment

`func (o *Logging) GetDevelopment() bool`

GetDevelopment returns the Development field if non-nil, zero value otherwise.

### GetDevelopmentOk

`func (o *Logging) GetDevelopmentOk() (*bool, bool)`

GetDevelopmentOk returns a tuple with the Development field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevelopment

`func (o *Logging) SetDevelopment(v bool)`

SetDevelopment sets Development field to given value.


### GetThrowWarnings

`func (o *Logging) GetThrowWarnings() bool`

GetThrowWarnings returns the ThrowWarnings field if non-nil, zero value otherwise.

### GetThrowWarningsOk

`func (o *Logging) GetThrowWarningsOk() (*bool, bool)`

GetThrowWarningsOk returns a tuple with the ThrowWarnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThrowWarnings

`func (o *Logging) SetThrowWarnings(v bool)`

SetThrowWarnings sets ThrowWarnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


