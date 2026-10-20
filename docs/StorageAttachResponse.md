# StorageAttachResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** | Job status. | 
**Message** | **string** | Human-readable status message. | 
**Id** | **string** | Storage device identifier. | 

## Methods

### NewStorageAttachResponse

`func NewStorageAttachResponse(status string, message string, id string, ) *StorageAttachResponse`

NewStorageAttachResponse instantiates a new StorageAttachResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStorageAttachResponseWithDefaults

`func NewStorageAttachResponseWithDefaults() *StorageAttachResponse`

NewStorageAttachResponseWithDefaults instantiates a new StorageAttachResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *StorageAttachResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StorageAttachResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StorageAttachResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetMessage

`func (o *StorageAttachResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *StorageAttachResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *StorageAttachResponse) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetId

`func (o *StorageAttachResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StorageAttachResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StorageAttachResponse) SetId(v string)`

SetId sets Id field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


