# CloudNotificationItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Notification identifier. | 
**AdminOnly** | **bool** | Whether the notification is admin-only. | 
**Quiet** | **bool** | Whether the notification is quiet. | 
**Scope** | **string** | Notification scope. | 
**Level** | **float32** | Alert level. | 
**Title** | **string** | Notification title. | 
**Message** | **string** | Notification message. | 
**Metadata** | **map[string]interface{}** | Additional metadata. | 
**CreatedAt** | **time.Time** | ISO timestamp of creation. | 
**UpdatedAt** | **time.Time** | ISO timestamp of last update. | 

## Methods

### NewCloudNotificationItem

`func NewCloudNotificationItem(identifier string, adminOnly bool, quiet bool, scope string, level float32, title string, message string, metadata map[string]interface{}, createdAt time.Time, updatedAt time.Time, ) *CloudNotificationItem`

NewCloudNotificationItem instantiates a new CloudNotificationItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCloudNotificationItemWithDefaults

`func NewCloudNotificationItemWithDefaults() *CloudNotificationItem`

NewCloudNotificationItemWithDefaults instantiates a new CloudNotificationItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *CloudNotificationItem) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *CloudNotificationItem) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *CloudNotificationItem) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetAdminOnly

`func (o *CloudNotificationItem) GetAdminOnly() bool`

GetAdminOnly returns the AdminOnly field if non-nil, zero value otherwise.

### GetAdminOnlyOk

`func (o *CloudNotificationItem) GetAdminOnlyOk() (*bool, bool)`

GetAdminOnlyOk returns a tuple with the AdminOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminOnly

`func (o *CloudNotificationItem) SetAdminOnly(v bool)`

SetAdminOnly sets AdminOnly field to given value.


### GetQuiet

`func (o *CloudNotificationItem) GetQuiet() bool`

GetQuiet returns the Quiet field if non-nil, zero value otherwise.

### GetQuietOk

`func (o *CloudNotificationItem) GetQuietOk() (*bool, bool)`

GetQuietOk returns a tuple with the Quiet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuiet

`func (o *CloudNotificationItem) SetQuiet(v bool)`

SetQuiet sets Quiet field to given value.


### GetScope

`func (o *CloudNotificationItem) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *CloudNotificationItem) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *CloudNotificationItem) SetScope(v string)`

SetScope sets Scope field to given value.


### GetLevel

`func (o *CloudNotificationItem) GetLevel() float32`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *CloudNotificationItem) GetLevelOk() (*float32, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *CloudNotificationItem) SetLevel(v float32)`

SetLevel sets Level field to given value.


### GetTitle

`func (o *CloudNotificationItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CloudNotificationItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CloudNotificationItem) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetMessage

`func (o *CloudNotificationItem) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CloudNotificationItem) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CloudNotificationItem) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetMetadata

`func (o *CloudNotificationItem) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CloudNotificationItem) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CloudNotificationItem) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *CloudNotificationItem) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *CloudNotificationItem) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCreatedAt

`func (o *CloudNotificationItem) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CloudNotificationItem) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CloudNotificationItem) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CloudNotificationItem) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CloudNotificationItem) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CloudNotificationItem) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


