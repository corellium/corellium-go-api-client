# WebPlayerCreatedSession

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Session identifier. | 
**Token** | **string** | Session token to hand to the Web Player in your page. It grants access only to this one device and only to the enabled features, until &#x60;expiration&#x60;. | 
**Expiration** | **time.Time** | Session expiration timestamp. | 
**Domain** | Pointer to [**WebPlayerSessionDomain**](WebPlayerSessionDomain.md) |  | [optional] 
**Time** | Pointer to **float32** | Server timestamp (ms) when the session was created. | [optional] 
**Disabled** | Pointer to **bool** | Present and set when the domain is disabled (public flag). | [optional] 

## Methods

### NewWebPlayerCreatedSession

`func NewWebPlayerCreatedSession(identifier string, token string, expiration time.Time, ) *WebPlayerCreatedSession`

NewWebPlayerCreatedSession instantiates a new WebPlayerCreatedSession object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebPlayerCreatedSessionWithDefaults

`func NewWebPlayerCreatedSessionWithDefaults() *WebPlayerCreatedSession`

NewWebPlayerCreatedSessionWithDefaults instantiates a new WebPlayerCreatedSession object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *WebPlayerCreatedSession) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *WebPlayerCreatedSession) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *WebPlayerCreatedSession) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetToken

`func (o *WebPlayerCreatedSession) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *WebPlayerCreatedSession) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *WebPlayerCreatedSession) SetToken(v string)`

SetToken sets Token field to given value.


### GetExpiration

`func (o *WebPlayerCreatedSession) GetExpiration() time.Time`

GetExpiration returns the Expiration field if non-nil, zero value otherwise.

### GetExpirationOk

`func (o *WebPlayerCreatedSession) GetExpirationOk() (*time.Time, bool)`

GetExpirationOk returns a tuple with the Expiration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiration

`func (o *WebPlayerCreatedSession) SetExpiration(v time.Time)`

SetExpiration sets Expiration field to given value.


### GetDomain

`func (o *WebPlayerCreatedSession) GetDomain() WebPlayerSessionDomain`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *WebPlayerCreatedSession) GetDomainOk() (*WebPlayerSessionDomain, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *WebPlayerCreatedSession) SetDomain(v WebPlayerSessionDomain)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *WebPlayerCreatedSession) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetTime

`func (o *WebPlayerCreatedSession) GetTime() float32`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *WebPlayerCreatedSession) GetTimeOk() (*float32, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *WebPlayerCreatedSession) SetTime(v float32)`

SetTime sets Time field to given value.

### HasTime

`func (o *WebPlayerCreatedSession) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetDisabled

`func (o *WebPlayerCreatedSession) GetDisabled() bool`

GetDisabled returns the Disabled field if non-nil, zero value otherwise.

### GetDisabledOk

`func (o *WebPlayerCreatedSession) GetDisabledOk() (*bool, bool)`

GetDisabledOk returns a tuple with the Disabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabled

`func (o *WebPlayerCreatedSession) SetDisabled(v bool)`

SetDisabled sets Disabled field to given value.

### HasDisabled

`func (o *WebPlayerCreatedSession) HasDisabled() bool`

HasDisabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


