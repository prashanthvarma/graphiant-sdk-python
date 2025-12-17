# ManaV2B2bExtranetMatchServiceToCustomer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID of the service being subscribed by the customer (required) | 
**lan_segment** | **int** |  | [optional] 
**nat** | [**List[ManaV2B2bNat]**](ManaV2B2bNat.md) |  | 
**num_customers** | **int** | Number of customers subscribed to the service | [optional] 
**service_prefixes** | [**List[ManaV2B2bExtranetPrefixTag]**](ManaV2B2bExtranetPrefixTag.md) |  | 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_match_service_to_customer import ManaV2B2bExtranetMatchServiceToCustomer

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetMatchServiceToCustomer from a JSON string
mana_v2_b2b_extranet_match_service_to_customer_instance = ManaV2B2bExtranetMatchServiceToCustomer.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetMatchServiceToCustomer.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_match_service_to_customer_dict = mana_v2_b2b_extranet_match_service_to_customer_instance.to_dict()
# create an instance of ManaV2B2bExtranetMatchServiceToCustomer from a dict
mana_v2_b2b_extranet_match_service_to_customer_from_dict = ManaV2B2bExtranetMatchServiceToCustomer.from_dict(mana_v2_b2b_extranet_match_service_to_customer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


