# ManaV2B2bExtranetProducerPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** | Description for the service | [optional] 
**global_object_device_summaries** | [**Dict[str, ManaV2GlobalObjectServiceSummaries]**](ManaV2GlobalObjectServiceSummaries.md) |  | [optional] 
**global_object_summaries** | [**Dict[str, ManaV2GlobalObjectServiceSummaries]**](ManaV2GlobalObjectServiceSummaries.md) |  | [optional] 
**nat_pools** | **List[str]** |  | 
**prefix_tags** | [**List[ManaV2B2bExtranetPrefixTag]**](ManaV2B2bExtranetPrefixTag.md) |  | [optional] 
**profiles** | [**List[ManaV2ApplicationProfile]**](ManaV2ApplicationProfile.md) |  | [optional] 
**service_lan_segment** | **int** | LAN segment for the service (required) | 
**service_prefixes** | **List[str]** |  | 
**sites** | [**List[ManaV2B2bSiteInformation]**](ManaV2B2bSiteInformation.md) |  | 
**sla** | [**ManaV2SlaInformation**](ManaV2SlaInformation.md) |  | [optional] 
**status** | **str** |  | [optional] 
**type** | **str** | Type of the service whether it is application or peering (required) | 
**unmatched_customers** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_producer_policy import ManaV2B2bExtranetProducerPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetProducerPolicy from a JSON string
mana_v2_b2b_extranet_producer_policy_instance = ManaV2B2bExtranetProducerPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetProducerPolicy.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_producer_policy_dict = mana_v2_b2b_extranet_producer_policy_instance.to_dict()
# create an instance of ManaV2B2bExtranetProducerPolicy from a dict
mana_v2_b2b_extranet_producer_policy_from_dict = ManaV2B2bExtranetProducerPolicy.from_dict(mana_v2_b2b_extranet_producer_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


