# CreateCloudAdminTrialRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** | Contact email address. | 
**Name** | **string** | Contact name. | 
**Phone** | **string** | Contact phone number. | 
**Country** | **string** | Country code. | 
**Company** | **string** | Company name. | 
**Industry** | **string** | Industry. | 
**Role** | **string** | Job role. | 
**Solution** | Pointer to **string** | Solution of interest. | [optional] 
**ProductId** | **string** | Stripe product identifier for the trial. | 
**Granted** | Pointer to **bool** | Whether the trial is pre-granted. | [optional] 
**NumberOfApps** | Pointer to **float32** | Number of apps. | [optional] 
**TeamSize** | Pointer to **float32** | Team size. | [optional] 
**SendEmail** | Pointer to **bool** | Whether to send the trial-granted email. | [optional] 
**Duration** | Pointer to **float32** | Override trial duration in days. | [optional] 

## Methods

### NewCreateCloudAdminTrialRequestBody

`func NewCreateCloudAdminTrialRequestBody(email string, name string, phone string, country string, company string, industry string, role string, productId string, ) *CreateCloudAdminTrialRequestBody`

NewCreateCloudAdminTrialRequestBody instantiates a new CreateCloudAdminTrialRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCloudAdminTrialRequestBodyWithDefaults

`func NewCreateCloudAdminTrialRequestBodyWithDefaults() *CreateCloudAdminTrialRequestBody`

NewCreateCloudAdminTrialRequestBodyWithDefaults instantiates a new CreateCloudAdminTrialRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *CreateCloudAdminTrialRequestBody) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateCloudAdminTrialRequestBody) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateCloudAdminTrialRequestBody) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetName

`func (o *CreateCloudAdminTrialRequestBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateCloudAdminTrialRequestBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateCloudAdminTrialRequestBody) SetName(v string)`

SetName sets Name field to given value.


### GetPhone

`func (o *CreateCloudAdminTrialRequestBody) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CreateCloudAdminTrialRequestBody) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CreateCloudAdminTrialRequestBody) SetPhone(v string)`

SetPhone sets Phone field to given value.


### GetCountry

`func (o *CreateCloudAdminTrialRequestBody) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CreateCloudAdminTrialRequestBody) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CreateCloudAdminTrialRequestBody) SetCountry(v string)`

SetCountry sets Country field to given value.


### GetCompany

`func (o *CreateCloudAdminTrialRequestBody) GetCompany() string`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *CreateCloudAdminTrialRequestBody) GetCompanyOk() (*string, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *CreateCloudAdminTrialRequestBody) SetCompany(v string)`

SetCompany sets Company field to given value.


### GetIndustry

`func (o *CreateCloudAdminTrialRequestBody) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *CreateCloudAdminTrialRequestBody) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *CreateCloudAdminTrialRequestBody) SetIndustry(v string)`

SetIndustry sets Industry field to given value.


### GetRole

`func (o *CreateCloudAdminTrialRequestBody) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *CreateCloudAdminTrialRequestBody) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *CreateCloudAdminTrialRequestBody) SetRole(v string)`

SetRole sets Role field to given value.


### GetSolution

`func (o *CreateCloudAdminTrialRequestBody) GetSolution() string`

GetSolution returns the Solution field if non-nil, zero value otherwise.

### GetSolutionOk

`func (o *CreateCloudAdminTrialRequestBody) GetSolutionOk() (*string, bool)`

GetSolutionOk returns a tuple with the Solution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSolution

`func (o *CreateCloudAdminTrialRequestBody) SetSolution(v string)`

SetSolution sets Solution field to given value.

### HasSolution

`func (o *CreateCloudAdminTrialRequestBody) HasSolution() bool`

HasSolution returns a boolean if a field has been set.

### GetProductId

`func (o *CreateCloudAdminTrialRequestBody) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateCloudAdminTrialRequestBody) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateCloudAdminTrialRequestBody) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetGranted

`func (o *CreateCloudAdminTrialRequestBody) GetGranted() bool`

GetGranted returns the Granted field if non-nil, zero value otherwise.

### GetGrantedOk

`func (o *CreateCloudAdminTrialRequestBody) GetGrantedOk() (*bool, bool)`

GetGrantedOk returns a tuple with the Granted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranted

`func (o *CreateCloudAdminTrialRequestBody) SetGranted(v bool)`

SetGranted sets Granted field to given value.

### HasGranted

`func (o *CreateCloudAdminTrialRequestBody) HasGranted() bool`

HasGranted returns a boolean if a field has been set.

### GetNumberOfApps

`func (o *CreateCloudAdminTrialRequestBody) GetNumberOfApps() float32`

GetNumberOfApps returns the NumberOfApps field if non-nil, zero value otherwise.

### GetNumberOfAppsOk

`func (o *CreateCloudAdminTrialRequestBody) GetNumberOfAppsOk() (*float32, bool)`

GetNumberOfAppsOk returns a tuple with the NumberOfApps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfApps

`func (o *CreateCloudAdminTrialRequestBody) SetNumberOfApps(v float32)`

SetNumberOfApps sets NumberOfApps field to given value.

### HasNumberOfApps

`func (o *CreateCloudAdminTrialRequestBody) HasNumberOfApps() bool`

HasNumberOfApps returns a boolean if a field has been set.

### GetTeamSize

`func (o *CreateCloudAdminTrialRequestBody) GetTeamSize() float32`

GetTeamSize returns the TeamSize field if non-nil, zero value otherwise.

### GetTeamSizeOk

`func (o *CreateCloudAdminTrialRequestBody) GetTeamSizeOk() (*float32, bool)`

GetTeamSizeOk returns a tuple with the TeamSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamSize

`func (o *CreateCloudAdminTrialRequestBody) SetTeamSize(v float32)`

SetTeamSize sets TeamSize field to given value.

### HasTeamSize

`func (o *CreateCloudAdminTrialRequestBody) HasTeamSize() bool`

HasTeamSize returns a boolean if a field has been set.

### GetSendEmail

`func (o *CreateCloudAdminTrialRequestBody) GetSendEmail() bool`

GetSendEmail returns the SendEmail field if non-nil, zero value otherwise.

### GetSendEmailOk

`func (o *CreateCloudAdminTrialRequestBody) GetSendEmailOk() (*bool, bool)`

GetSendEmailOk returns a tuple with the SendEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendEmail

`func (o *CreateCloudAdminTrialRequestBody) SetSendEmail(v bool)`

SetSendEmail sets SendEmail field to given value.

### HasSendEmail

`func (o *CreateCloudAdminTrialRequestBody) HasSendEmail() bool`

HasSendEmail returns a boolean if a field has been set.

### GetDuration

`func (o *CreateCloudAdminTrialRequestBody) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *CreateCloudAdminTrialRequestBody) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *CreateCloudAdminTrialRequestBody) SetDuration(v float32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *CreateCloudAdminTrialRequestBody) HasDuration() bool`

HasDuration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


