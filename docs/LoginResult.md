# LoginResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Token** | **string** | Signed JWT bearer session token, newly regenerated on every successful login. | 
**Expiration** | **time.Time** | Token expiration timestamp. | 
**User** | Pointer to [**LoginResultUser**](LoginResultUser.md) |  | [optional] 
**Domain** | Pointer to [**LoginResultDomain**](LoginResultDomain.md) |  | [optional] 
**Time** | Pointer to **float32** | Server time when the session was issued, in milliseconds. | [optional] 
**Identifier** | Pointer to **string** | Webplayer session identifier. Present only on a Webplayer token renewal. | [optional] 
**Disabled** | Pointer to [**LoginResultDisabled**](LoginResultDisabled.md) |  | [optional] 
**MissingTOTP** | Pointer to **bool** | Present when the domain requires TOTP but the user has not enrolled. | [optional] 

## Methods

### NewLoginResult

`func NewLoginResult(token string, expiration time.Time, ) *LoginResult`

NewLoginResult instantiates a new LoginResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginResultWithDefaults

`func NewLoginResultWithDefaults() *LoginResult`

NewLoginResultWithDefaults instantiates a new LoginResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToken

`func (o *LoginResult) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *LoginResult) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *LoginResult) SetToken(v string)`

SetToken sets Token field to given value.


### GetExpiration

`func (o *LoginResult) GetExpiration() time.Time`

GetExpiration returns the Expiration field if non-nil, zero value otherwise.

### GetExpirationOk

`func (o *LoginResult) GetExpirationOk() (*time.Time, bool)`

GetExpirationOk returns a tuple with the Expiration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiration

`func (o *LoginResult) SetExpiration(v time.Time)`

SetExpiration sets Expiration field to given value.


### GetUser

`func (o *LoginResult) GetUser() LoginResultUser`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *LoginResult) GetUserOk() (*LoginResultUser, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *LoginResult) SetUser(v LoginResultUser)`

SetUser sets User field to given value.

### HasUser

`func (o *LoginResult) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetDomain

`func (o *LoginResult) GetDomain() LoginResultDomain`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *LoginResult) GetDomainOk() (*LoginResultDomain, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *LoginResult) SetDomain(v LoginResultDomain)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *LoginResult) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetTime

`func (o *LoginResult) GetTime() float32`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *LoginResult) GetTimeOk() (*float32, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *LoginResult) SetTime(v float32)`

SetTime sets Time field to given value.

### HasTime

`func (o *LoginResult) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetIdentifier

`func (o *LoginResult) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *LoginResult) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *LoginResult) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *LoginResult) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetDisabled

`func (o *LoginResult) GetDisabled() LoginResultDisabled`

GetDisabled returns the Disabled field if non-nil, zero value otherwise.

### GetDisabledOk

`func (o *LoginResult) GetDisabledOk() (*LoginResultDisabled, bool)`

GetDisabledOk returns a tuple with the Disabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabled

`func (o *LoginResult) SetDisabled(v LoginResultDisabled)`

SetDisabled sets Disabled field to given value.

### HasDisabled

`func (o *LoginResult) HasDisabled() bool`

HasDisabled returns a boolean if a field has been set.

### GetMissingTOTP

`func (o *LoginResult) GetMissingTOTP() bool`

GetMissingTOTP returns the MissingTOTP field if non-nil, zero value otherwise.

### GetMissingTOTPOk

`func (o *LoginResult) GetMissingTOTPOk() (*bool, bool)`

GetMissingTOTPOk returns a tuple with the MissingTOTP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMissingTOTP

`func (o *LoginResult) SetMissingTOTP(v bool)`

SetMissingTOTP sets MissingTOTP field to given value.

### HasMissingTOTP

`func (o *LoginResult) HasMissingTOTP() bool`

HasMissingTOTP returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


