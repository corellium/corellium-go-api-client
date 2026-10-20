# CreateActivityExportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Export task ID, in the form &#x60;activity-export/&lt;UUID&gt;&#x60;. Pass only the &#x60;&lt;UUID&gt;&#x60; part to &#x60;v3GetActivityExportStatus&#x60; and &#x60;v3DownloadActivity&#x60;. | 

## Methods

### NewCreateActivityExportResponse

`func NewCreateActivityExportResponse(id string, ) *CreateActivityExportResponse`

NewCreateActivityExportResponse instantiates a new CreateActivityExportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateActivityExportResponseWithDefaults

`func NewCreateActivityExportResponseWithDefaults() *CreateActivityExportResponse`

NewCreateActivityExportResponseWithDefaults instantiates a new CreateActivityExportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateActivityExportResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateActivityExportResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateActivityExportResponse) SetId(v string)`

SetId sets Id field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


