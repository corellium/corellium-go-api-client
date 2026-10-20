# DomainWelcomeMessageResponseV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Unique identifier for the welcome message (UUID) | 
**Domain** | **string** | Domain identifier (UUID) | 
**Message** | **string** | Sanitized welcome message text | 
**CreatedAt** | **string** | Creation timestamp (ISO 8601) | 
**UpdatedAt** | **string** | Last update timestamp (ISO 8601) | 

## Methods

### NewDomainWelcomeMessageResponseV1

`func NewDomainWelcomeMessageResponseV1(identifier string, domain string, message string, createdAt string, updatedAt string, ) *DomainWelcomeMessageResponseV1`

NewDomainWelcomeMessageResponseV1 instantiates a new DomainWelcomeMessageResponseV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainWelcomeMessageResponseV1WithDefaults

`func NewDomainWelcomeMessageResponseV1WithDefaults() *DomainWelcomeMessageResponseV1`

NewDomainWelcomeMessageResponseV1WithDefaults instantiates a new DomainWelcomeMessageResponseV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *DomainWelcomeMessageResponseV1) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *DomainWelcomeMessageResponseV1) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *DomainWelcomeMessageResponseV1) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetDomain

`func (o *DomainWelcomeMessageResponseV1) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *DomainWelcomeMessageResponseV1) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *DomainWelcomeMessageResponseV1) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetMessage

`func (o *DomainWelcomeMessageResponseV1) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *DomainWelcomeMessageResponseV1) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *DomainWelcomeMessageResponseV1) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetCreatedAt

`func (o *DomainWelcomeMessageResponseV1) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DomainWelcomeMessageResponseV1) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DomainWelcomeMessageResponseV1) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *DomainWelcomeMessageResponseV1) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DomainWelcomeMessageResponseV1) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DomainWelcomeMessageResponseV1) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


