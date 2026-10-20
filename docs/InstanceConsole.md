# InstanceConsole

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Console display name. | 
**Id** | **string** | Console port identifier (e.g. port-cons). Used to select this console when getting the console websocket URL. | 
**Port** | **string** | TCP port number. | 
**Hash** | **string** | Hash for console authentication. | 
**Info** | **string** | Encrypted info for console authentication. | 

## Methods

### NewInstanceConsole

`func NewInstanceConsole(name string, id string, port string, hash string, info string, ) *InstanceConsole`

NewInstanceConsole instantiates a new InstanceConsole object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceConsoleWithDefaults

`func NewInstanceConsoleWithDefaults() *InstanceConsole`

NewInstanceConsoleWithDefaults instantiates a new InstanceConsole object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *InstanceConsole) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InstanceConsole) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InstanceConsole) SetName(v string)`

SetName sets Name field to given value.


### GetId

`func (o *InstanceConsole) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InstanceConsole) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InstanceConsole) SetId(v string)`

SetId sets Id field to given value.


### GetPort

`func (o *InstanceConsole) GetPort() string`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *InstanceConsole) GetPortOk() (*string, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *InstanceConsole) SetPort(v string)`

SetPort sets Port field to given value.


### GetHash

`func (o *InstanceConsole) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *InstanceConsole) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *InstanceConsole) SetHash(v string)`

SetHash sets Hash field to given value.


### GetInfo

`func (o *InstanceConsole) GetInfo() string`

GetInfo returns the Info field if non-nil, zero value otherwise.

### GetInfoOk

`func (o *InstanceConsole) GetInfoOk() (*string, bool)`

GetInfoOk returns a tuple with the Info field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfo

`func (o *InstanceConsole) SetInfo(v string)`

SetInfo sets Info field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


