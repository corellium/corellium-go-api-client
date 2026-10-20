# MessageBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Number** | **string** | Source phone number. | 
**Message** | **string** | SMS message body. | 
**Raw** | **string** | Hex-encoded raw message bytes. | 

## Methods

### NewMessageBody

`func NewMessageBody(number string, message string, raw string, ) *MessageBody`

NewMessageBody instantiates a new MessageBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageBodyWithDefaults

`func NewMessageBodyWithDefaults() *MessageBody`

NewMessageBodyWithDefaults instantiates a new MessageBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNumber

`func (o *MessageBody) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *MessageBody) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *MessageBody) SetNumber(v string)`

SetNumber sets Number field to given value.


### GetMessage

`func (o *MessageBody) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *MessageBody) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *MessageBody) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetRaw

`func (o *MessageBody) GetRaw() string`

GetRaw returns the Raw field if non-nil, zero value otherwise.

### GetRawOk

`func (o *MessageBody) GetRawOk() (*string, bool)`

GetRawOk returns a tuple with the Raw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRaw

`func (o *MessageBody) SetRaw(v string)`

SetRaw sets Raw field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


