# ClusterConfigCoordinatorConfigEnsureDomain

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **string** |  | 
**DomainName** | **string** |  | 
**Quotas** | [**ClusterConfigCoordinatorConfigEnsureDomainQuotas**](ClusterConfigCoordinatorConfigEnsureDomainQuotas.md) |  | 
**Properties** | [**ClusterConfigCoordinatorConfigEnsureDomainProperties**](ClusterConfigCoordinatorConfigEnsureDomainProperties.md) |  | 
**AdminPasswordHash** | **string** |  | 
**AdminUserCloudAdministrator** | **bool** |  | 
**IsIndividualAggregate** | **bool** |  | 

## Methods

### NewClusterConfigCoordinatorConfigEnsureDomain

`func NewClusterConfigCoordinatorConfigEnsureDomain(domain string, domainName string, quotas ClusterConfigCoordinatorConfigEnsureDomainQuotas, properties ClusterConfigCoordinatorConfigEnsureDomainProperties, adminPasswordHash string, adminUserCloudAdministrator bool, isIndividualAggregate bool, ) *ClusterConfigCoordinatorConfigEnsureDomain`

NewClusterConfigCoordinatorConfigEnsureDomain instantiates a new ClusterConfigCoordinatorConfigEnsureDomain object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterConfigCoordinatorConfigEnsureDomainWithDefaults

`func NewClusterConfigCoordinatorConfigEnsureDomainWithDefaults() *ClusterConfigCoordinatorConfigEnsureDomain`

NewClusterConfigCoordinatorConfigEnsureDomainWithDefaults instantiates a new ClusterConfigCoordinatorConfigEnsureDomain object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetDomainName

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetDomainName() string`

GetDomainName returns the DomainName field if non-nil, zero value otherwise.

### GetDomainNameOk

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetDomainNameOk() (*string, bool)`

GetDomainNameOk returns a tuple with the DomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainName

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) SetDomainName(v string)`

SetDomainName sets DomainName field to given value.


### GetQuotas

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetQuotas() ClusterConfigCoordinatorConfigEnsureDomainQuotas`

GetQuotas returns the Quotas field if non-nil, zero value otherwise.

### GetQuotasOk

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetQuotasOk() (*ClusterConfigCoordinatorConfigEnsureDomainQuotas, bool)`

GetQuotasOk returns a tuple with the Quotas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotas

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) SetQuotas(v ClusterConfigCoordinatorConfigEnsureDomainQuotas)`

SetQuotas sets Quotas field to given value.


### GetProperties

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetProperties() ClusterConfigCoordinatorConfigEnsureDomainProperties`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetPropertiesOk() (*ClusterConfigCoordinatorConfigEnsureDomainProperties, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) SetProperties(v ClusterConfigCoordinatorConfigEnsureDomainProperties)`

SetProperties sets Properties field to given value.


### GetAdminPasswordHash

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetAdminPasswordHash() string`

GetAdminPasswordHash returns the AdminPasswordHash field if non-nil, zero value otherwise.

### GetAdminPasswordHashOk

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetAdminPasswordHashOk() (*string, bool)`

GetAdminPasswordHashOk returns a tuple with the AdminPasswordHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminPasswordHash

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) SetAdminPasswordHash(v string)`

SetAdminPasswordHash sets AdminPasswordHash field to given value.


### GetAdminUserCloudAdministrator

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetAdminUserCloudAdministrator() bool`

GetAdminUserCloudAdministrator returns the AdminUserCloudAdministrator field if non-nil, zero value otherwise.

### GetAdminUserCloudAdministratorOk

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetAdminUserCloudAdministratorOk() (*bool, bool)`

GetAdminUserCloudAdministratorOk returns a tuple with the AdminUserCloudAdministrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminUserCloudAdministrator

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) SetAdminUserCloudAdministrator(v bool)`

SetAdminUserCloudAdministrator sets AdminUserCloudAdministrator field to given value.


### GetIsIndividualAggregate

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetIsIndividualAggregate() bool`

GetIsIndividualAggregate returns the IsIndividualAggregate field if non-nil, zero value otherwise.

### GetIsIndividualAggregateOk

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) GetIsIndividualAggregateOk() (*bool, bool)`

GetIsIndividualAggregateOk returns a tuple with the IsIndividualAggregate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsIndividualAggregate

`func (o *ClusterConfigCoordinatorConfigEnsureDomain) SetIsIndividualAggregate(v bool)`

SetIsIndividualAggregate sets IsIndividualAggregate field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


