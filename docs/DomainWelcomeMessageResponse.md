# DomainWelcomeMessageResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Unique identifier for the welcome message. | 
**Domain** | **string** | Domain identifier. | 
**Message** | **string** | Sanitized welcome message text. | 
**Enabled** | **bool** | Whether the welcome message is shown to users. | 
**CreatedAt** | **time.Time** | Creation timestamp (ISO 8601). | 
**UpdatedAt** | **time.Time** | Last update timestamp (ISO 8601). | 

## Methods

### NewDomainWelcomeMessageResponse

`func NewDomainWelcomeMessageResponse(identifier string, domain string, message string, enabled bool, createdAt time.Time, updatedAt time.Time, ) *DomainWelcomeMessageResponse`

NewDomainWelcomeMessageResponse instantiates a new DomainWelcomeMessageResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainWelcomeMessageResponseWithDefaults

`func NewDomainWelcomeMessageResponseWithDefaults() *DomainWelcomeMessageResponse`

NewDomainWelcomeMessageResponseWithDefaults instantiates a new DomainWelcomeMessageResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *DomainWelcomeMessageResponse) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *DomainWelcomeMessageResponse) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *DomainWelcomeMessageResponse) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetDomain

`func (o *DomainWelcomeMessageResponse) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *DomainWelcomeMessageResponse) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *DomainWelcomeMessageResponse) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetMessage

`func (o *DomainWelcomeMessageResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *DomainWelcomeMessageResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *DomainWelcomeMessageResponse) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetEnabled

`func (o *DomainWelcomeMessageResponse) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DomainWelcomeMessageResponse) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DomainWelcomeMessageResponse) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetCreatedAt

`func (o *DomainWelcomeMessageResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DomainWelcomeMessageResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DomainWelcomeMessageResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *DomainWelcomeMessageResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DomainWelcomeMessageResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DomainWelcomeMessageResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


