# DomainListItemProjectsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Project identifier. | 
**Name** | **string** | Project name. | 
**Quotas** | [**DomainListItemProjectsInnerQuotas**](DomainListItemProjectsInnerQuotas.md) |  | 
**Usage** | [**DomainListItemProjectsInnerUsage**](DomainListItemProjectsInnerUsage.md) |  | 
**Instances** | [**[]DomainListItemProjectsInnerInstancesInner**](DomainListItemProjectsInnerInstancesInner.md) | Instances in the project. | 
**Images** | Pointer to [**[]DomainListItemProjectsInnerInstancesInnerImagesInner**](DomainListItemProjectsInnerInstancesInnerImagesInner.md) | Images in the project. | [optional] 

## Methods

### NewDomainListItemProjectsInner

`func NewDomainListItemProjectsInner(identifier string, name string, quotas DomainListItemProjectsInnerQuotas, usage DomainListItemProjectsInnerUsage, instances []DomainListItemProjectsInnerInstancesInner, ) *DomainListItemProjectsInner`

NewDomainListItemProjectsInner instantiates a new DomainListItemProjectsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListItemProjectsInnerWithDefaults

`func NewDomainListItemProjectsInnerWithDefaults() *DomainListItemProjectsInner`

NewDomainListItemProjectsInnerWithDefaults instantiates a new DomainListItemProjectsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *DomainListItemProjectsInner) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *DomainListItemProjectsInner) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *DomainListItemProjectsInner) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetName

`func (o *DomainListItemProjectsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DomainListItemProjectsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DomainListItemProjectsInner) SetName(v string)`

SetName sets Name field to given value.


### GetQuotas

`func (o *DomainListItemProjectsInner) GetQuotas() DomainListItemProjectsInnerQuotas`

GetQuotas returns the Quotas field if non-nil, zero value otherwise.

### GetQuotasOk

`func (o *DomainListItemProjectsInner) GetQuotasOk() (*DomainListItemProjectsInnerQuotas, bool)`

GetQuotasOk returns a tuple with the Quotas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotas

`func (o *DomainListItemProjectsInner) SetQuotas(v DomainListItemProjectsInnerQuotas)`

SetQuotas sets Quotas field to given value.


### GetUsage

`func (o *DomainListItemProjectsInner) GetUsage() DomainListItemProjectsInnerUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *DomainListItemProjectsInner) GetUsageOk() (*DomainListItemProjectsInnerUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *DomainListItemProjectsInner) SetUsage(v DomainListItemProjectsInnerUsage)`

SetUsage sets Usage field to given value.


### GetInstances

`func (o *DomainListItemProjectsInner) GetInstances() []DomainListItemProjectsInnerInstancesInner`

GetInstances returns the Instances field if non-nil, zero value otherwise.

### GetInstancesOk

`func (o *DomainListItemProjectsInner) GetInstancesOk() (*[]DomainListItemProjectsInnerInstancesInner, bool)`

GetInstancesOk returns a tuple with the Instances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstances

`func (o *DomainListItemProjectsInner) SetInstances(v []DomainListItemProjectsInnerInstancesInner)`

SetInstances sets Instances field to given value.


### GetImages

`func (o *DomainListItemProjectsInner) GetImages() []DomainListItemProjectsInnerInstancesInnerImagesInner`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *DomainListItemProjectsInner) GetImagesOk() (*[]DomainListItemProjectsInnerInstancesInnerImagesInner, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *DomainListItemProjectsInner) SetImages(v []DomainListItemProjectsInnerInstancesInnerImagesInner)`

SetImages sets Images field to given value.

### HasImages

`func (o *DomainListItemProjectsInner) HasImages() bool`

HasImages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


