# WebPlayerSession

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Session identifier. | 
**Token** | **string** | Session token to hand to the Web Player in your page. It grants access only to this one device and only to the enabled features, until &#x60;expiration&#x60;. | 
**Expiration** | **time.Time** | Session expiration timestamp. | 

## Methods

### NewWebPlayerSession

`func NewWebPlayerSession(identifier string, token string, expiration time.Time, ) *WebPlayerSession`

NewWebPlayerSession instantiates a new WebPlayerSession object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebPlayerSessionWithDefaults

`func NewWebPlayerSessionWithDefaults() *WebPlayerSession`

NewWebPlayerSessionWithDefaults instantiates a new WebPlayerSession object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *WebPlayerSession) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *WebPlayerSession) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *WebPlayerSession) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetToken

`func (o *WebPlayerSession) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *WebPlayerSession) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *WebPlayerSession) SetToken(v string)`

SetToken sets Token field to given value.


### GetExpiration

`func (o *WebPlayerSession) GetExpiration() time.Time`

GetExpiration returns the Expiration field if non-nil, zero value otherwise.

### GetExpirationOk

`func (o *WebPlayerSession) GetExpirationOk() (*time.Time, bool)`

GetExpirationOk returns a tuple with the Expiration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiration

`func (o *WebPlayerSession) SetExpiration(v time.Time)`

SetExpiration sets Expiration field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


