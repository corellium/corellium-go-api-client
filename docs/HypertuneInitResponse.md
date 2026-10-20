# HypertuneInitResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CommitId** | Pointer to **float32** | Hypertune configuration commit ID. | [optional] 
**Hash** | Pointer to **string** | Hypertune configuration state hash. | [optional] 
**ReducedExpression** | Pointer to **map[string]interface{}** | Reduced Hypertune evaluation expression. | [optional] 
**Splits** | Pointer to **map[string]interface{}** | Hypertune split configuration. | [optional] 
**CommitConfig** | Pointer to **map[string]interface{}** | Hypertune commit configuration. | [optional] 

## Methods

### NewHypertuneInitResponse

`func NewHypertuneInitResponse() *HypertuneInitResponse`

NewHypertuneInitResponse instantiates a new HypertuneInitResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHypertuneInitResponseWithDefaults

`func NewHypertuneInitResponseWithDefaults() *HypertuneInitResponse`

NewHypertuneInitResponseWithDefaults instantiates a new HypertuneInitResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommitId

`func (o *HypertuneInitResponse) GetCommitId() float32`

GetCommitId returns the CommitId field if non-nil, zero value otherwise.

### GetCommitIdOk

`func (o *HypertuneInitResponse) GetCommitIdOk() (*float32, bool)`

GetCommitIdOk returns a tuple with the CommitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommitId

`func (o *HypertuneInitResponse) SetCommitId(v float32)`

SetCommitId sets CommitId field to given value.

### HasCommitId

`func (o *HypertuneInitResponse) HasCommitId() bool`

HasCommitId returns a boolean if a field has been set.

### GetHash

`func (o *HypertuneInitResponse) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *HypertuneInitResponse) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *HypertuneInitResponse) SetHash(v string)`

SetHash sets Hash field to given value.

### HasHash

`func (o *HypertuneInitResponse) HasHash() bool`

HasHash returns a boolean if a field has been set.

### GetReducedExpression

`func (o *HypertuneInitResponse) GetReducedExpression() map[string]interface{}`

GetReducedExpression returns the ReducedExpression field if non-nil, zero value otherwise.

### GetReducedExpressionOk

`func (o *HypertuneInitResponse) GetReducedExpressionOk() (*map[string]interface{}, bool)`

GetReducedExpressionOk returns a tuple with the ReducedExpression field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReducedExpression

`func (o *HypertuneInitResponse) SetReducedExpression(v map[string]interface{})`

SetReducedExpression sets ReducedExpression field to given value.

### HasReducedExpression

`func (o *HypertuneInitResponse) HasReducedExpression() bool`

HasReducedExpression returns a boolean if a field has been set.

### GetSplits

`func (o *HypertuneInitResponse) GetSplits() map[string]interface{}`

GetSplits returns the Splits field if non-nil, zero value otherwise.

### GetSplitsOk

`func (o *HypertuneInitResponse) GetSplitsOk() (*map[string]interface{}, bool)`

GetSplitsOk returns a tuple with the Splits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSplits

`func (o *HypertuneInitResponse) SetSplits(v map[string]interface{})`

SetSplits sets Splits field to given value.

### HasSplits

`func (o *HypertuneInitResponse) HasSplits() bool`

HasSplits returns a boolean if a field has been set.

### GetCommitConfig

`func (o *HypertuneInitResponse) GetCommitConfig() map[string]interface{}`

GetCommitConfig returns the CommitConfig field if non-nil, zero value otherwise.

### GetCommitConfigOk

`func (o *HypertuneInitResponse) GetCommitConfigOk() (*map[string]interface{}, bool)`

GetCommitConfigOk returns a tuple with the CommitConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommitConfig

`func (o *HypertuneInitResponse) SetCommitConfig(v map[string]interface{})`

SetCommitConfig sets CommitConfig field to given value.

### HasCommitConfig

`func (o *HypertuneInitResponse) HasCommitConfig() bool`

HasCommitConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


