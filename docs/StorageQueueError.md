# StorageQueueError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | Error summary. | 
**Details** | **string** | Underlying error message. | 
**Suggestion** | **string** | Suggested remediation. | 

## Methods

### NewStorageQueueError

`func NewStorageQueueError(error_ string, details string, suggestion string, ) *StorageQueueError`

NewStorageQueueError instantiates a new StorageQueueError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStorageQueueErrorWithDefaults

`func NewStorageQueueErrorWithDefaults() *StorageQueueError`

NewStorageQueueErrorWithDefaults instantiates a new StorageQueueError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *StorageQueueError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *StorageQueueError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *StorageQueueError) SetError(v string)`

SetError sets Error field to given value.


### GetDetails

`func (o *StorageQueueError) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *StorageQueueError) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *StorageQueueError) SetDetails(v string)`

SetDetails sets Details field to given value.


### GetSuggestion

`func (o *StorageQueueError) GetSuggestion() string`

GetSuggestion returns the Suggestion field if non-nil, zero value otherwise.

### GetSuggestionOk

`func (o *StorageQueueError) GetSuggestionOk() (*string, bool)`

GetSuggestionOk returns a tuple with the Suggestion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestion

`func (o *StorageQueueError) SetSuggestion(v string)`

SetSuggestion sets Suggestion field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


