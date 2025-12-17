# ManaV2B2bExtranetPeeringServiceProducerPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** | Description for the service | [optional] 
**global_object_ops** | [**Dict[str, ManaV2GlobalObjectServiceOps]**](ManaV2GlobalObjectServiceOps.md) |  | [optional] 
**prefix_tags** | [**List[ManaV2B2bExtranetPrefixTag]**](ManaV2B2bExtranetPrefixTag.md) |  | 
**service_lan_segment** | **int** | LAN segment ID for the service (required) | 
**site** | [**List[ManaV2B2bSiteInformation]**](ManaV2B2bSiteInformation.md) |  | 
**type** | **str** | Type of the service whether it is application or peering (required) | 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_peering_service_producer_policy import ManaV2B2bExtranetPeeringServiceProducerPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetPeeringServiceProducerPolicy from a JSON string
mana_v2_b2b_extranet_peering_service_producer_policy_instance = ManaV2B2bExtranetPeeringServiceProducerPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetPeeringServiceProducerPolicy.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_peering_service_producer_policy_dict = mana_v2_b2b_extranet_peering_service_producer_policy_instance.to_dict()
# create an instance of ManaV2B2bExtranetPeeringServiceProducerPolicy from a dict
mana_v2_b2b_extranet_peering_service_producer_policy_from_dict = ManaV2B2bExtranetPeeringServiceProducerPolicy.from_dict(mana_v2_b2b_extranet_peering_service_producer_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


