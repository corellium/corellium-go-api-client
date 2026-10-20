# FetchFirmwareAssetsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Added** | **[]string** | Asset URLs newly fetched and stored. | 
**Existing** | **[]string** | Asset URLs already present. | 
**Failed** | [**[]FetchFirmwareAssetsResponseFailedInner**](FetchFirmwareAssetsResponseFailedInner.md) | Assets that could not be fetched. | 

## Methods

### NewFetchFirmwareAssetsResponse

`func NewFetchFirmwareAssetsResponse(added []string, existing []string, failed []FetchFirmwareAssetsResponseFailedInner, ) *FetchFirmwareAssetsResponse`

NewFetchFirmwareAssetsResponse instantiates a new FetchFirmwareAssetsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFetchFirmwareAssetsResponseWithDefaults

`func NewFetchFirmwareAssetsResponseWithDefaults() *FetchFirmwareAssetsResponse`

NewFetchFirmwareAssetsResponseWithDefaults instantiates a new FetchFirmwareAssetsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdded

`func (o *FetchFirmwareAssetsResponse) GetAdded() []string`

GetAdded returns the Added field if non-nil, zero value otherwise.

### GetAddedOk

`func (o *FetchFirmwareAssetsResponse) GetAddedOk() (*[]string, bool)`

GetAddedOk returns a tuple with the Added field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdded

`func (o *FetchFirmwareAssetsResponse) SetAdded(v []string)`

SetAdded sets Added field to given value.


### GetExisting

`func (o *FetchFirmwareAssetsResponse) GetExisting() []string`

GetExisting returns the Existing field if non-nil, zero value otherwise.

### GetExistingOk

`func (o *FetchFirmwareAssetsResponse) GetExistingOk() (*[]string, bool)`

GetExistingOk returns a tuple with the Existing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExisting

`func (o *FetchFirmwareAssetsResponse) SetExisting(v []string)`

SetExisting sets Existing field to given value.


### GetFailed

`func (o *FetchFirmwareAssetsResponse) GetFailed() []FetchFirmwareAssetsResponseFailedInner`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *FetchFirmwareAssetsResponse) GetFailedOk() (*[]FetchFirmwareAssetsResponseFailedInner, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *FetchFirmwareAssetsResponse) SetFailed(v []FetchFirmwareAssetsResponseFailedInner)`

SetFailed sets Failed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


