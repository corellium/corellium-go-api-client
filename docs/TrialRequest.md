# TrialRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** | Requester email. | 
**Name** | **NullableString** | Requester name. | 
**BillingType** | **NullableString** | Billing type. | 
**BillingId** | **NullableString** | Billing backend identifier. | 
**Code** | **NullableString** | Sign-up code. | 
**Enterprise** | **bool** | Whether an enterprise domain is requested. | 
**Granted** | **NullableBool** | Whether the request was granted. | 
**Phone** | **NullableString** | Phone number. | 
**Country** | **NullableString** | Country. | 
**Organization** | **NullableString** | Organization. | 
**OrganizationType** | **NullableString** | Organization type. | 
**Metadata** | **map[string]interface{}** | Sign-up metadata. | 
**CreatedAt** | **float32** | Creation timestamp (ms). | 
**UpdatedAt** | **float32** | Update timestamp (ms). | 
**DisplayStatus** | **string** | Computed display status of the trial request. | 

## Methods

### NewTrialRequest

`func NewTrialRequest(email string, name NullableString, billingType NullableString, billingId NullableString, code NullableString, enterprise bool, granted NullableBool, phone NullableString, country NullableString, organization NullableString, organizationType NullableString, metadata map[string]interface{}, createdAt float32, updatedAt float32, displayStatus string, ) *TrialRequest`

NewTrialRequest instantiates a new TrialRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrialRequestWithDefaults

`func NewTrialRequestWithDefaults() *TrialRequest`

NewTrialRequestWithDefaults instantiates a new TrialRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *TrialRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *TrialRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *TrialRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetName

`func (o *TrialRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TrialRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TrialRequest) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *TrialRequest) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *TrialRequest) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetBillingType

`func (o *TrialRequest) GetBillingType() string`

GetBillingType returns the BillingType field if non-nil, zero value otherwise.

### GetBillingTypeOk

`func (o *TrialRequest) GetBillingTypeOk() (*string, bool)`

GetBillingTypeOk returns a tuple with the BillingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingType

`func (o *TrialRequest) SetBillingType(v string)`

SetBillingType sets BillingType field to given value.


### SetBillingTypeNil

`func (o *TrialRequest) SetBillingTypeNil(b bool)`

 SetBillingTypeNil sets the value for BillingType to be an explicit nil

### UnsetBillingType
`func (o *TrialRequest) UnsetBillingType()`

UnsetBillingType ensures that no value is present for BillingType, not even an explicit nil
### GetBillingId

`func (o *TrialRequest) GetBillingId() string`

GetBillingId returns the BillingId field if non-nil, zero value otherwise.

### GetBillingIdOk

`func (o *TrialRequest) GetBillingIdOk() (*string, bool)`

GetBillingIdOk returns a tuple with the BillingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingId

`func (o *TrialRequest) SetBillingId(v string)`

SetBillingId sets BillingId field to given value.


### SetBillingIdNil

`func (o *TrialRequest) SetBillingIdNil(b bool)`

 SetBillingIdNil sets the value for BillingId to be an explicit nil

### UnsetBillingId
`func (o *TrialRequest) UnsetBillingId()`

UnsetBillingId ensures that no value is present for BillingId, not even an explicit nil
### GetCode

`func (o *TrialRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TrialRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TrialRequest) SetCode(v string)`

SetCode sets Code field to given value.


### SetCodeNil

`func (o *TrialRequest) SetCodeNil(b bool)`

 SetCodeNil sets the value for Code to be an explicit nil

### UnsetCode
`func (o *TrialRequest) UnsetCode()`

UnsetCode ensures that no value is present for Code, not even an explicit nil
### GetEnterprise

`func (o *TrialRequest) GetEnterprise() bool`

GetEnterprise returns the Enterprise field if non-nil, zero value otherwise.

### GetEnterpriseOk

`func (o *TrialRequest) GetEnterpriseOk() (*bool, bool)`

GetEnterpriseOk returns a tuple with the Enterprise field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterprise

`func (o *TrialRequest) SetEnterprise(v bool)`

SetEnterprise sets Enterprise field to given value.


### GetGranted

`func (o *TrialRequest) GetGranted() bool`

GetGranted returns the Granted field if non-nil, zero value otherwise.

### GetGrantedOk

`func (o *TrialRequest) GetGrantedOk() (*bool, bool)`

GetGrantedOk returns a tuple with the Granted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranted

`func (o *TrialRequest) SetGranted(v bool)`

SetGranted sets Granted field to given value.


### SetGrantedNil

`func (o *TrialRequest) SetGrantedNil(b bool)`

 SetGrantedNil sets the value for Granted to be an explicit nil

### UnsetGranted
`func (o *TrialRequest) UnsetGranted()`

UnsetGranted ensures that no value is present for Granted, not even an explicit nil
### GetPhone

`func (o *TrialRequest) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *TrialRequest) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *TrialRequest) SetPhone(v string)`

SetPhone sets Phone field to given value.


### SetPhoneNil

`func (o *TrialRequest) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *TrialRequest) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetCountry

`func (o *TrialRequest) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *TrialRequest) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *TrialRequest) SetCountry(v string)`

SetCountry sets Country field to given value.


### SetCountryNil

`func (o *TrialRequest) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *TrialRequest) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetOrganization

`func (o *TrialRequest) GetOrganization() string`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *TrialRequest) GetOrganizationOk() (*string, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *TrialRequest) SetOrganization(v string)`

SetOrganization sets Organization field to given value.


### SetOrganizationNil

`func (o *TrialRequest) SetOrganizationNil(b bool)`

 SetOrganizationNil sets the value for Organization to be an explicit nil

### UnsetOrganization
`func (o *TrialRequest) UnsetOrganization()`

UnsetOrganization ensures that no value is present for Organization, not even an explicit nil
### GetOrganizationType

`func (o *TrialRequest) GetOrganizationType() string`

GetOrganizationType returns the OrganizationType field if non-nil, zero value otherwise.

### GetOrganizationTypeOk

`func (o *TrialRequest) GetOrganizationTypeOk() (*string, bool)`

GetOrganizationTypeOk returns a tuple with the OrganizationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationType

`func (o *TrialRequest) SetOrganizationType(v string)`

SetOrganizationType sets OrganizationType field to given value.


### SetOrganizationTypeNil

`func (o *TrialRequest) SetOrganizationTypeNil(b bool)`

 SetOrganizationTypeNil sets the value for OrganizationType to be an explicit nil

### UnsetOrganizationType
`func (o *TrialRequest) UnsetOrganizationType()`

UnsetOrganizationType ensures that no value is present for OrganizationType, not even an explicit nil
### GetMetadata

`func (o *TrialRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *TrialRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *TrialRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *TrialRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *TrialRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCreatedAt

`func (o *TrialRequest) GetCreatedAt() float32`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TrialRequest) GetCreatedAtOk() (*float32, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TrialRequest) SetCreatedAt(v float32)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *TrialRequest) GetUpdatedAt() float32`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *TrialRequest) GetUpdatedAtOk() (*float32, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *TrialRequest) SetUpdatedAt(v float32)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetDisplayStatus

`func (o *TrialRequest) GetDisplayStatus() string`

GetDisplayStatus returns the DisplayStatus field if non-nil, zero value otherwise.

### GetDisplayStatusOk

`func (o *TrialRequest) GetDisplayStatusOk() (*string, bool)`

GetDisplayStatusOk returns a tuple with the DisplayStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayStatus

`func (o *TrialRequest) SetDisplayStatus(v string)`

SetDisplayStatus sets DisplayStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


