# TunnelEncapsulation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **string** | * &#x60;ipsec-transport&#x60; - IPsec - Transport * &#x60;ipsec-tunnel&#x60; - IPsec - Tunnel * &#x60;ip-ip&#x60; - IP-in-IP * &#x60;gre&#x60; - GRE | [optional] 
**Label** | Pointer to **string** |  | [optional] 

## Methods

### NewTunnelEncapsulation

`func NewTunnelEncapsulation() *TunnelEncapsulation`

NewTunnelEncapsulation instantiates a new TunnelEncapsulation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTunnelEncapsulationWithDefaults

`func NewTunnelEncapsulationWithDefaults() *TunnelEncapsulation`

NewTunnelEncapsulationWithDefaults instantiates a new TunnelEncapsulation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *TunnelEncapsulation) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *TunnelEncapsulation) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *TunnelEncapsulation) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *TunnelEncapsulation) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetLabel

`func (o *TunnelEncapsulation) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *TunnelEncapsulation) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *TunnelEncapsulation) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *TunnelEncapsulation) HasLabel() bool`

HasLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


