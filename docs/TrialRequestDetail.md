# TrialRequestDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Trial request identifier. | 
**Metadata** | **map[string]interface{}** | Additional metadata. | 
**Organization** | [**NullableTrialRequestDetailOrganization**](TrialRequestDetailOrganization.md) |  | 
**Devices** | **[]map[string]string** | Devices requested (e.g. [{ ios: \&quot;iOS\&quot; }]). | 
**UseCases** | **[]map[string]string** | Use cases (e.g. [{ malware: \&quot;Malware Research\&quot; }]). | 
**Email** | **string** | Contact email. | 
**Name** | **string** | Contact name. | 
**BillingType** | **string** | Billing type. | 
**BillingBackend** | **NullableString** | Billing backend (e.g. stripe). | 
**BillingId** | **NullableString** | External billing identifier. | 
**ProductId** | **NullableString** | Stripe product identifier. | 
**Code** | **string** | Trial coupon code. | 
**Enterprise** | **bool** | Whether the request is for enterprise. | 
**Granted** | **bool** | Whether the trial has been granted. | 
**Phone** | **NullableString** | Contact phone number. | 
**Country** | **NullableString** | Country code. | 
**OrganizationType** | **NullableString** | Organization type. | 
**Industry** | **NullableString** | Industry. | 
**Role** | **NullableString** | Job role. | 
**Solution** | **NullableString** | Solution of interest. | 
**Domain** | **NullableString** | Associated domain identifier. | 
**StartedAt** | **NullableTime** | ISO timestamp of trial start. | 
**GrantedAt** | **NullableTime** | ISO timestamp of when trial was granted. | 
**DeniedAt** | **NullableTime** | ISO timestamp of when trial was denied. | 
**PlanName** | **NullableString** | Trial plan name. | 
**EndsAt** | **NullableTime** | ISO timestamp of when trial ends. | 
**GrantMethod** | **NullableString** | Method used to grant the trial. | 
**Duration** | **NullableFloat32** | Trial duration in days (override). | 
**TrialUnits** | **NullableFloat32** | Trial usage units remaining. | 
**CreatedAt** | **time.Time** | ISO timestamp of creation. | 
**UpdatedAt** | **time.Time** | ISO timestamp of last update. | 

## Methods

### NewTrialRequestDetail

`func NewTrialRequestDetail(identifier string, metadata map[string]interface{}, organization NullableTrialRequestDetailOrganization, devices []map[string]string, useCases []map[string]string, email string, name string, billingType string, billingBackend NullableString, billingId NullableString, productId NullableString, code string, enterprise bool, granted bool, phone NullableString, country NullableString, organizationType NullableString, industry NullableString, role NullableString, solution NullableString, domain NullableString, startedAt NullableTime, grantedAt NullableTime, deniedAt NullableTime, planName NullableString, endsAt NullableTime, grantMethod NullableString, duration NullableFloat32, trialUnits NullableFloat32, createdAt time.Time, updatedAt time.Time, ) *TrialRequestDetail`

NewTrialRequestDetail instantiates a new TrialRequestDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrialRequestDetailWithDefaults

`func NewTrialRequestDetailWithDefaults() *TrialRequestDetail`

NewTrialRequestDetailWithDefaults instantiates a new TrialRequestDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *TrialRequestDetail) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *TrialRequestDetail) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *TrialRequestDetail) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetMetadata

`func (o *TrialRequestDetail) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *TrialRequestDetail) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *TrialRequestDetail) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *TrialRequestDetail) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *TrialRequestDetail) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetOrganization

`func (o *TrialRequestDetail) GetOrganization() TrialRequestDetailOrganization`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *TrialRequestDetail) GetOrganizationOk() (*TrialRequestDetailOrganization, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *TrialRequestDetail) SetOrganization(v TrialRequestDetailOrganization)`

SetOrganization sets Organization field to given value.


### SetOrganizationNil

`func (o *TrialRequestDetail) SetOrganizationNil(b bool)`

 SetOrganizationNil sets the value for Organization to be an explicit nil

### UnsetOrganization
`func (o *TrialRequestDetail) UnsetOrganization()`

UnsetOrganization ensures that no value is present for Organization, not even an explicit nil
### GetDevices

`func (o *TrialRequestDetail) GetDevices() []map[string]string`

GetDevices returns the Devices field if non-nil, zero value otherwise.

### GetDevicesOk

`func (o *TrialRequestDetail) GetDevicesOk() (*[]map[string]string, bool)`

GetDevicesOk returns a tuple with the Devices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevices

`func (o *TrialRequestDetail) SetDevices(v []map[string]string)`

SetDevices sets Devices field to given value.


### SetDevicesNil

`func (o *TrialRequestDetail) SetDevicesNil(b bool)`

 SetDevicesNil sets the value for Devices to be an explicit nil

### UnsetDevices
`func (o *TrialRequestDetail) UnsetDevices()`

UnsetDevices ensures that no value is present for Devices, not even an explicit nil
### GetUseCases

`func (o *TrialRequestDetail) GetUseCases() []map[string]string`

GetUseCases returns the UseCases field if non-nil, zero value otherwise.

### GetUseCasesOk

`func (o *TrialRequestDetail) GetUseCasesOk() (*[]map[string]string, bool)`

GetUseCasesOk returns a tuple with the UseCases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCases

`func (o *TrialRequestDetail) SetUseCases(v []map[string]string)`

SetUseCases sets UseCases field to given value.


### SetUseCasesNil

`func (o *TrialRequestDetail) SetUseCasesNil(b bool)`

 SetUseCasesNil sets the value for UseCases to be an explicit nil

### UnsetUseCases
`func (o *TrialRequestDetail) UnsetUseCases()`

UnsetUseCases ensures that no value is present for UseCases, not even an explicit nil
### GetEmail

`func (o *TrialRequestDetail) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *TrialRequestDetail) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *TrialRequestDetail) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetName

`func (o *TrialRequestDetail) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TrialRequestDetail) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TrialRequestDetail) SetName(v string)`

SetName sets Name field to given value.


### GetBillingType

`func (o *TrialRequestDetail) GetBillingType() string`

GetBillingType returns the BillingType field if non-nil, zero value otherwise.

### GetBillingTypeOk

`func (o *TrialRequestDetail) GetBillingTypeOk() (*string, bool)`

GetBillingTypeOk returns a tuple with the BillingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingType

`func (o *TrialRequestDetail) SetBillingType(v string)`

SetBillingType sets BillingType field to given value.


### GetBillingBackend

`func (o *TrialRequestDetail) GetBillingBackend() string`

GetBillingBackend returns the BillingBackend field if non-nil, zero value otherwise.

### GetBillingBackendOk

`func (o *TrialRequestDetail) GetBillingBackendOk() (*string, bool)`

GetBillingBackendOk returns a tuple with the BillingBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingBackend

`func (o *TrialRequestDetail) SetBillingBackend(v string)`

SetBillingBackend sets BillingBackend field to given value.


### SetBillingBackendNil

`func (o *TrialRequestDetail) SetBillingBackendNil(b bool)`

 SetBillingBackendNil sets the value for BillingBackend to be an explicit nil

### UnsetBillingBackend
`func (o *TrialRequestDetail) UnsetBillingBackend()`

UnsetBillingBackend ensures that no value is present for BillingBackend, not even an explicit nil
### GetBillingId

`func (o *TrialRequestDetail) GetBillingId() string`

GetBillingId returns the BillingId field if non-nil, zero value otherwise.

### GetBillingIdOk

`func (o *TrialRequestDetail) GetBillingIdOk() (*string, bool)`

GetBillingIdOk returns a tuple with the BillingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingId

`func (o *TrialRequestDetail) SetBillingId(v string)`

SetBillingId sets BillingId field to given value.


### SetBillingIdNil

`func (o *TrialRequestDetail) SetBillingIdNil(b bool)`

 SetBillingIdNil sets the value for BillingId to be an explicit nil

### UnsetBillingId
`func (o *TrialRequestDetail) UnsetBillingId()`

UnsetBillingId ensures that no value is present for BillingId, not even an explicit nil
### GetProductId

`func (o *TrialRequestDetail) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *TrialRequestDetail) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *TrialRequestDetail) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### SetProductIdNil

`func (o *TrialRequestDetail) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *TrialRequestDetail) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetCode

`func (o *TrialRequestDetail) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TrialRequestDetail) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TrialRequestDetail) SetCode(v string)`

SetCode sets Code field to given value.


### GetEnterprise

`func (o *TrialRequestDetail) GetEnterprise() bool`

GetEnterprise returns the Enterprise field if non-nil, zero value otherwise.

### GetEnterpriseOk

`func (o *TrialRequestDetail) GetEnterpriseOk() (*bool, bool)`

GetEnterpriseOk returns a tuple with the Enterprise field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterprise

`func (o *TrialRequestDetail) SetEnterprise(v bool)`

SetEnterprise sets Enterprise field to given value.


### GetGranted

`func (o *TrialRequestDetail) GetGranted() bool`

GetGranted returns the Granted field if non-nil, zero value otherwise.

### GetGrantedOk

`func (o *TrialRequestDetail) GetGrantedOk() (*bool, bool)`

GetGrantedOk returns a tuple with the Granted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranted

`func (o *TrialRequestDetail) SetGranted(v bool)`

SetGranted sets Granted field to given value.


### GetPhone

`func (o *TrialRequestDetail) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *TrialRequestDetail) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *TrialRequestDetail) SetPhone(v string)`

SetPhone sets Phone field to given value.


### SetPhoneNil

`func (o *TrialRequestDetail) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *TrialRequestDetail) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetCountry

`func (o *TrialRequestDetail) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *TrialRequestDetail) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *TrialRequestDetail) SetCountry(v string)`

SetCountry sets Country field to given value.


### SetCountryNil

`func (o *TrialRequestDetail) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *TrialRequestDetail) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetOrganizationType

`func (o *TrialRequestDetail) GetOrganizationType() string`

GetOrganizationType returns the OrganizationType field if non-nil, zero value otherwise.

### GetOrganizationTypeOk

`func (o *TrialRequestDetail) GetOrganizationTypeOk() (*string, bool)`

GetOrganizationTypeOk returns a tuple with the OrganizationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationType

`func (o *TrialRequestDetail) SetOrganizationType(v string)`

SetOrganizationType sets OrganizationType field to given value.


### SetOrganizationTypeNil

`func (o *TrialRequestDetail) SetOrganizationTypeNil(b bool)`

 SetOrganizationTypeNil sets the value for OrganizationType to be an explicit nil

### UnsetOrganizationType
`func (o *TrialRequestDetail) UnsetOrganizationType()`

UnsetOrganizationType ensures that no value is present for OrganizationType, not even an explicit nil
### GetIndustry

`func (o *TrialRequestDetail) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *TrialRequestDetail) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *TrialRequestDetail) SetIndustry(v string)`

SetIndustry sets Industry field to given value.


### SetIndustryNil

`func (o *TrialRequestDetail) SetIndustryNil(b bool)`

 SetIndustryNil sets the value for Industry to be an explicit nil

### UnsetIndustry
`func (o *TrialRequestDetail) UnsetIndustry()`

UnsetIndustry ensures that no value is present for Industry, not even an explicit nil
### GetRole

`func (o *TrialRequestDetail) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *TrialRequestDetail) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *TrialRequestDetail) SetRole(v string)`

SetRole sets Role field to given value.


### SetRoleNil

`func (o *TrialRequestDetail) SetRoleNil(b bool)`

 SetRoleNil sets the value for Role to be an explicit nil

### UnsetRole
`func (o *TrialRequestDetail) UnsetRole()`

UnsetRole ensures that no value is present for Role, not even an explicit nil
### GetSolution

`func (o *TrialRequestDetail) GetSolution() string`

GetSolution returns the Solution field if non-nil, zero value otherwise.

### GetSolutionOk

`func (o *TrialRequestDetail) GetSolutionOk() (*string, bool)`

GetSolutionOk returns a tuple with the Solution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSolution

`func (o *TrialRequestDetail) SetSolution(v string)`

SetSolution sets Solution field to given value.


### SetSolutionNil

`func (o *TrialRequestDetail) SetSolutionNil(b bool)`

 SetSolutionNil sets the value for Solution to be an explicit nil

### UnsetSolution
`func (o *TrialRequestDetail) UnsetSolution()`

UnsetSolution ensures that no value is present for Solution, not even an explicit nil
### GetDomain

`func (o *TrialRequestDetail) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *TrialRequestDetail) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *TrialRequestDetail) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *TrialRequestDetail) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *TrialRequestDetail) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetStartedAt

`func (o *TrialRequestDetail) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *TrialRequestDetail) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *TrialRequestDetail) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### SetStartedAtNil

`func (o *TrialRequestDetail) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *TrialRequestDetail) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetGrantedAt

`func (o *TrialRequestDetail) GetGrantedAt() time.Time`

GetGrantedAt returns the GrantedAt field if non-nil, zero value otherwise.

### GetGrantedAtOk

`func (o *TrialRequestDetail) GetGrantedAtOk() (*time.Time, bool)`

GetGrantedAtOk returns a tuple with the GrantedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrantedAt

`func (o *TrialRequestDetail) SetGrantedAt(v time.Time)`

SetGrantedAt sets GrantedAt field to given value.


### SetGrantedAtNil

`func (o *TrialRequestDetail) SetGrantedAtNil(b bool)`

 SetGrantedAtNil sets the value for GrantedAt to be an explicit nil

### UnsetGrantedAt
`func (o *TrialRequestDetail) UnsetGrantedAt()`

UnsetGrantedAt ensures that no value is present for GrantedAt, not even an explicit nil
### GetDeniedAt

`func (o *TrialRequestDetail) GetDeniedAt() time.Time`

GetDeniedAt returns the DeniedAt field if non-nil, zero value otherwise.

### GetDeniedAtOk

`func (o *TrialRequestDetail) GetDeniedAtOk() (*time.Time, bool)`

GetDeniedAtOk returns a tuple with the DeniedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeniedAt

`func (o *TrialRequestDetail) SetDeniedAt(v time.Time)`

SetDeniedAt sets DeniedAt field to given value.


### SetDeniedAtNil

`func (o *TrialRequestDetail) SetDeniedAtNil(b bool)`

 SetDeniedAtNil sets the value for DeniedAt to be an explicit nil

### UnsetDeniedAt
`func (o *TrialRequestDetail) UnsetDeniedAt()`

UnsetDeniedAt ensures that no value is present for DeniedAt, not even an explicit nil
### GetPlanName

`func (o *TrialRequestDetail) GetPlanName() string`

GetPlanName returns the PlanName field if non-nil, zero value otherwise.

### GetPlanNameOk

`func (o *TrialRequestDetail) GetPlanNameOk() (*string, bool)`

GetPlanNameOk returns a tuple with the PlanName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanName

`func (o *TrialRequestDetail) SetPlanName(v string)`

SetPlanName sets PlanName field to given value.


### SetPlanNameNil

`func (o *TrialRequestDetail) SetPlanNameNil(b bool)`

 SetPlanNameNil sets the value for PlanName to be an explicit nil

### UnsetPlanName
`func (o *TrialRequestDetail) UnsetPlanName()`

UnsetPlanName ensures that no value is present for PlanName, not even an explicit nil
### GetEndsAt

`func (o *TrialRequestDetail) GetEndsAt() time.Time`

GetEndsAt returns the EndsAt field if non-nil, zero value otherwise.

### GetEndsAtOk

`func (o *TrialRequestDetail) GetEndsAtOk() (*time.Time, bool)`

GetEndsAtOk returns a tuple with the EndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndsAt

`func (o *TrialRequestDetail) SetEndsAt(v time.Time)`

SetEndsAt sets EndsAt field to given value.


### SetEndsAtNil

`func (o *TrialRequestDetail) SetEndsAtNil(b bool)`

 SetEndsAtNil sets the value for EndsAt to be an explicit nil

### UnsetEndsAt
`func (o *TrialRequestDetail) UnsetEndsAt()`

UnsetEndsAt ensures that no value is present for EndsAt, not even an explicit nil
### GetGrantMethod

`func (o *TrialRequestDetail) GetGrantMethod() string`

GetGrantMethod returns the GrantMethod field if non-nil, zero value otherwise.

### GetGrantMethodOk

`func (o *TrialRequestDetail) GetGrantMethodOk() (*string, bool)`

GetGrantMethodOk returns a tuple with the GrantMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrantMethod

`func (o *TrialRequestDetail) SetGrantMethod(v string)`

SetGrantMethod sets GrantMethod field to given value.


### SetGrantMethodNil

`func (o *TrialRequestDetail) SetGrantMethodNil(b bool)`

 SetGrantMethodNil sets the value for GrantMethod to be an explicit nil

### UnsetGrantMethod
`func (o *TrialRequestDetail) UnsetGrantMethod()`

UnsetGrantMethod ensures that no value is present for GrantMethod, not even an explicit nil
### GetDuration

`func (o *TrialRequestDetail) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TrialRequestDetail) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TrialRequestDetail) SetDuration(v float32)`

SetDuration sets Duration field to given value.


### SetDurationNil

`func (o *TrialRequestDetail) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *TrialRequestDetail) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetTrialUnits

`func (o *TrialRequestDetail) GetTrialUnits() float32`

GetTrialUnits returns the TrialUnits field if non-nil, zero value otherwise.

### GetTrialUnitsOk

`func (o *TrialRequestDetail) GetTrialUnitsOk() (*float32, bool)`

GetTrialUnitsOk returns a tuple with the TrialUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialUnits

`func (o *TrialRequestDetail) SetTrialUnits(v float32)`

SetTrialUnits sets TrialUnits field to given value.


### SetTrialUnitsNil

`func (o *TrialRequestDetail) SetTrialUnitsNil(b bool)`

 SetTrialUnitsNil sets the value for TrialUnits to be an explicit nil

### UnsetTrialUnits
`func (o *TrialRequestDetail) UnsetTrialUnits()`

UnsetTrialUnits ensures that no value is present for TrialUnits, not even an explicit nil
### GetCreatedAt

`func (o *TrialRequestDetail) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TrialRequestDetail) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TrialRequestDetail) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *TrialRequestDetail) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *TrialRequestDetail) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *TrialRequestDetail) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


